# 演示Markdown的各种语法
## 标题的写法
        下面的都是各种标题的示意 
       
### 一般的规则
        标题以“#”号开头，“#”号的个数代表标题的等级。只有1～6级，共6个等级。一级标题有一个#，二级标题有两个#，以此类推。
        特别注意 “#”号和标题直接必须有一个空格。如下所示
		# 一级标题
		## 二级标题
		### 三级标题
		#### 四级标题
		##### 五级标题
		###### 六级标题
        下面演示这六级标题的大小
### 标题的等级表示法
# 一级标题，大标题
## 二级标题， 中标题
### 三级标题
#### 四级标题
##### 五级标题

### 大标题和中标题的特殊写法
        大标题一般显示工程名。为了显示大标题，你只需要另起一行，写上=======。
        这是一个大标题
        ==========================================================
        效果如下

这是一个大标题
==========================================================
        这是一个中标题
        -----------------------------------
        效果如下
这是一个中标题
-----------------------------------

  
## 正文
### 文本框
        文本以两个“Tab”开头, 而且每行都需要2个“Tab”开头，
        可以自由换行， 
        也可以插入代码。比如
```c
int main() {
    std::cout << "Hello, Github!" << std::endl;
}
```
### 其他
#### 链接
        [显示的文字](地址)， 比如
        [我的github主页](https://github.com/xxmawhu)
[我的github主页](https://github.com/xxmawhu)


#### 插入图片
        [image](path/to/fig)

![image](/images/02.jpg)
![image](/images/ucaslogo.eps)
![image](/images/ucaslogo.png)
### 显示图片也可以用原生的html标签
<img src="http://su.bdimg.com/static/superplus/img/logo_white.png" />

###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com
[![image]](http://www.github.com/)
[image]: /images/02.jpg "github-02.jpg"

### 文字被些字符包围
> 文字被些字符包围
>
> 只要再文字前面加上>空格即可
>
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
> 但> 只能放在行首才有效

### 文字被些字符包围,多重包围
> 文字被些字符包围开始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
>
> > > > 但> 只能放在行首才有效

### 部分文字的高亮
如果你想使一段话部分文字高亮显示，来起到突出强调的作用，那么可以把它用\`\`包围起来。
注意这不是单引号，而是Tab键和数字1键左边的按键（注意使用英文输入法）。<br />
	example：
		Thank`You`. Please `Call` Me `Coder`
### 代码片段高亮显示
GitHub的markdown语法还支持部分语言的代码片段高亮显示。只需要在代码的上一行和下一行用\`\`\`标记。
```Java
	public static void main(String[] args){} //Java
```
```c
	int main(int argc,char *argv[]) //C
```
```javascript
	document.getElementById("myH1").innerHTML="Welcome to my Homepage";//javascript
```
```cpp
	string &operator+(const string& A,const string& B) //cpp
```
	
### list列表条目使用
写文章时经常会用到list列表条目。GitHub的markdown语法里也支持使用圆点符。编辑的时候使用的是星号*。
* 国籍：中国
* 城市：北京
* 大学：清华大学 
<br/>注意：星号*后面要有一个空格。否则显示为普通星号。

GitHub还支持多级别的list列表条目：

* 编程语言
	* 脚本语言
		* Python

### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>
    

