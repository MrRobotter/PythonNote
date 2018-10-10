### 第一个Python程序
#### 在交互式环境中编写程序
* 编写规范
在交互式环境的提示符`>>>`下，直接输入代码，按下回车就能得到执行结果。试试100+200,看下执行结果是不是300：
````
>>> 100+200
300

````

如果让Python打印出指定的文字，使用`print`语句，然后把希望打印的文字使用单引号或者双引号括起来，但是不能混用单引号和双引号：
如：
````
>>> print 'Hello'
Hello

````
或者

````
>>> print "Hello"
Hello

````
需要注意的是这里的单引号和双引号是英文状态下的。

* 这样的好处是一下就能得到结果，坏处是没法保存，下次还想运行的时候，需要在敲一遍代码。实际开发的时候我们是使用一个文本编辑器来写代码，写完了之后保存为一个文件，这样程序就可以反复运行了。

#### 使用文本编辑器
这里有两款文本编辑器：
* Sublime Text 我目前使用的是这款免费版，但是每次打开都很提示

* Notepad++ 

打开文本编辑器，输入一下代码：
````
print "LI NING,I LOVE YOU"
````
需要注意的是：`print`前不要有任何空格，即`print`要顶格然后选择一个目录，如：code/day1下，把文件保存为 `hello.py`，然后就可以打开终端，把当前目录切换到`hello.py`目录，就可以运行这个程序了：

````
zhangjunyangdeMacBook-Pro:day1 Young$ python hello.py
LI NING,I LOVE YOU
````
#### 文件命名规范
* 文件名只能是英文字母、数字和下划线的组合。
* 必须是以`.py`结尾
如果当前目录下没有该文件则报一下错误：
````
zhangjunyangdeMacBook-Pro:day1 Young$ python htll.py
python: can't open file 'htll.py': [Errno 2] No such file or directory
````
