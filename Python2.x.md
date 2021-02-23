# <bable style = "color: yellowgreen">Python2.x</bable>
始于2020年1月16日；环境python2.7.18

## 一、Python 基础教程
```
Python 是一种解释型、面向对象、动态数据类型的高级程序设计语言。

Python 由 Guido van Rossum 于 1989 年底发明，第一个公开发行版发行于 1991 年。

像 Perl 语言一样, Python 源代码同样遵循 GPL(GNU General Public License) 协议。

官方宣布，2020 年 1 月 1 日， 停止 Python 2 的更新。

Python 2.7 被确定为最后一个 Python 2.x 版本。
```

## 二、Python 简介

### Python 简介
```
Python 是一个高层次的结合了解释性、编译性、互动性和面向对象的脚本语言。

Python 的设计具有很强的可读性，相比其他语言经常使用英文关键字，其他语言的一些标点符号，它具有比其他语言更有特色语法结构。

1.Python 是一种解释型语言： 这意味着开发过程中没有了编译这个环节。类似于PHP和Perl语言。

2.Python 是交互式语言： 这意味着，您可以在一个 Python 提示符 >>> 后直接执行代码。

3.Python 是面向对象语言: 这意味着Python支持面向对象的风格或代码封装在对象的编程技术。

4.Python 是初学者的语言：Python 对初级程序员而言，是一种伟大的语言，它支持广泛的应用程序开发，从简单的文字处理到 WWW 浏览器再到游戏。
```

### Python 发展历史
```
Python 是由 Guido van Rossum 在八十年代末和九十年代初，在荷兰国家数学和计算机科学研究所设计出来的。

Python 本身也是由诸多其他语言发展而来的,这包括 ABC、Modula-3、C、C++、Algol-68、SmallTalk、Unix shell 和其他的脚本语言等等。

像 Perl 语言一样，Python 源代码同样遵循 GPL(GNU General Public License)协议。

现在 Python 是由一个核心开发团队在维护，Guido van Rossum 仍然占据着至关重要的作用，指导其进展。

Python 2.7 被确定为最后一个 Python 2.x 版本，它除了支持 Python 2.x 语法外，还支持部分 Python 3.1 语法。
```

### Python 特点
```
1.易于学习：Python有相对较少的关键字，结构简单，和一个明确定义的语法，学习起来更加简单。

2.易于阅读：Python代码定义的更清晰。

3.易于维护：Python的成功在于它的源代码是相当容易维护的。

4.一个广泛的标准库：Python的最大的优势之一是丰富的库，跨平台的，在UNIX，Windows和Macintosh兼容很好。

5.互动模式：互动模式的支持，您可以从终端输入执行代码并获得结果的语言，互动的测试和调试代码片断。

6.可移植：基于其开放源代码的特性，Python已经被移植（也就是使其工作）到许多平台。

7.可扩展：如果你需要一段运行很快的关键代码，或者是想要编写一些不愿开放的算法，你可以使用C或C++完成那部分程序，然后从你的Python程序中调用。

8.数据库：Python提供所有主要的商业数据库的接口。

9.GUI编程：Python支持GUI可以创建和移植到许多系统调用。

10.可嵌入: 你可以将Python嵌入到C/C++程序，让你的程序的用户获得"脚本化"的能力。
```

## 三、Python 环境搭建

### Python 环境搭建
```
本章节我们将向大家介绍如何在本地搭建Python开发环境。

Python可应用于多平台包括 Linux 和 Mac OS X。

你可以通过终端窗口输入 "python" 命令来查看本地是否已经安装Python以及Python的安装版本。
```

### Python 下载
```
Python最新源码，二进制文档，新闻资讯等可以在Python的官网查看到：

Python官网：https://www.python.org/

你可以在以下链接中下载 Python 的文档，你可以下载 HTML、PDF 和 PostScript 等格式的文档。

Python文档下载地址：https://www.python.org/doc/
```

### Python 安装
```
Python已经被移植在许多平台上（经过改动使它能够工作在不同平台上）。

您需要下载适用于您使用平台的二进制代码，然后安装Python。

如果您平台的二进制代码是不可用的，你需要使用C编译器手动编译源代码。

编译的源代码，功能上有更多的选择性， 为python安装提供了更多的灵活性。
```

### <bable style = "color: #ff6666">环境变量配置</bable>
<!-- <bable style = "color: yellow"> -->
```
程序和可执行文件可以在许多目录，而这些路径很可能不在操作系统提供可执行文件的搜索路径中。

path(路径)存储在环境变量中，这是由操作系统维护的一个命名的字符串。这些变量包含可用的命令行解释器和其他程序的信息。

Unix或Windows中路径变量为PATH（UNIX区分大小写，Windows不区分大小写）。

在Mac OS中，安装程序过程中改变了python的安装路径。如果你需要在其他目录引用Python，你必须在path中添加Python目录。
```
### Python 环境变量
```
下面几个重要的环境变量，它应用于Python：
变量名         描述
PYTHONPATH  	PYTHONPATH是Python搜索路径，默认我们import的模块都会从PYTHONPATH里面寻找。
PYTHONSTARTUP	Python启动后，先寻找PYTHONSTARTUP环境变量，然后执行此变量指定的文件中的代码。
PYTHONCASEOK	加入PYTHONCASEOK的环境变量, 就会使python导入模块的时候不区分大小写.
PYTHONHOME  	另一种模块搜索路径。它通常内嵌于的PYTHONSTARTUP或PYTHONPATH目录中，使得两个模块库更容易切换。
```

### 运行Python
```
有三种方式运行Python：
1、交互式解释器
2、命令行脚本
3、集成开发环境（IDE）：PyCharm
下载地址：https://www.jetbrains.com/pycharm/download/
```

## 四、Python 中文编码

### Python 中文编码
```
实例：
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
print( "你好，世界" )
```

## 五、Python 基础语法

### Python 基础语法
<br>
Python 语言与 Perl，C 和 Java 等语言有许多相似之处。但是，也存在一些差异。

在本章中我们将来学习 Python 的基础语法，让你快速学会 Python 编程。
### 第一个Python程序
<b>交互式编程</b>

交互式编程不需要创建脚本文件，是通过 Python 解释器的交互模式进来编写代码。

linux上你只需要在命令行中输入 Python 命令即可启动交互式编程,提示窗口如下：
```
C:\Users\TZBBZ>python
Python 3.9.1 (tags/v3.9.1:1e5d33e, Dec  7 2020, 17:08:21) [MSC v.1927 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print ("Hello, Python!")
Hello, Python!
>>>
```
<b>交互式编程</b>
通过脚本参数调用解释器开始执行脚本，直到脚本执行完毕。当脚本执行完成后，解释器不再有效。

让我们写一个简单的 Python 脚本程序。所有 Python 文件将以 .py 为扩展名。将以下的源代码拷贝至 test.py 文件中。
```
$ python test.py
```

### Python2.x中使用Python3.x的print函数
如果 Python2.x 版本想使用使用 Python3.x 的 print 函数，可以导入 __future__ 包，该包禁用 Python2.x 的 print 语句，采用 Python3.x 的 print 函数：
```
>>> list =["a", "b", "c"]
>>> print list    # python2.x 的 print 语句
['a', 'b', 'c']
>>> from __future__ import print_function  # 导入 __future__ 包
>>> print list     # Python2.x 的 print 语句被禁用，使用报错
  File "<stdin>", line 1
    print list
          ^
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(list)?
>>> print (list)   # 使用 Python3.x 的 print 函数
['a', 'b', 'c']
>>>
```
Python3.x 与 Python2.x 的许多兼容性设计的功能可以通过 __ future __ 这个包来导入。

### Python 标识符
在 Python 里，标识符由字母、数字、下划线组成。

在 Python 中，所有标识符可以包括英文、数字以及下划线( _ )，但不能以数字开头。

Python 中的标识符是区分大小写的。

以下划线开头的标识符是有特殊意义的。以单下划线开头 _foo 的代表不能直接访问的类属性，需通过类提供的接口进行访问，不能用 from xxx import * 而导入。

以双下划线开头的 __ foo 代表类的私有成员，以双下划线开头和结尾的 __ foo__ 代表 Python 里特殊方法专用的标识，如 __ init __() 代表类的构造函数。

Python 可以同一行显示多条语句，方法是用分号 ; 分开，如：
```
>>> print ('hello');print ('runoob');
hello
runoob
```

### Python 保留字符

下面的列表显示了在Python中的保留字。这些保留字不能用作常数或变数，或任何其他标识符名称。

所有 Python 的关键字只包含小写字母。下面的列表显示了在Python中的保留字。这些保留字不能用作常数或变数，或任何其他标识符名称。

所有 Python 的关键字只包含小写字母。
```
and	exec	not
assert	finally	or
break	for	pass
class	from	print
continue	global	raise
def	if	return
del	import	try
elif	in	while
else	is	with
except	lambda	yield
```
### 行和缩进

学习 Python 与其他语言最大的区别就是，Python 的代码块不使用大括号 { } 来控制类，函数以及其他逻辑判断。python 最具特色的就是用缩进来写模块。

缩进的空白数量是可变的，但是所有代码块语句必须包含相同的缩进空白数量，这个必须严格执行。

以下实例缩进为四个空格:
```
if True:
    print ("True")
else:
    print ("False")
```
以下代码将会执行错误：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
# 文件名：test.py

if True:
    print ("Answer")
    print ("True")
else:
    print ("Answer")
    # 没有严格缩进，在执行时会报错
  print ("False")
```
执行以上代码，会出现如下错误提醒：
```
File "test.py", line 11
    print ("False")
                  ^
IndentationError: unindent does not match any outer indentation level
```
IndentationError: unindent does not match any outer indentation level错误表明，你使用的缩进方式不一致，有的是 tab 键缩进，有的是空格缩进，改为一致即可。

如果是 IndentationError: unexpected indent 错误, 则 python 编译器是在告诉你"Hi，老兄，你的文件里格式不对了，可能是tab和空格没对齐的问题"，所有 python 对格式要求非常严格。

因此，在 Python 的代码块中必须使用相同数目的行首缩进空格数。

建议你在每个缩进层次使用 单个制表符 或 两个空格 或 四个空格 , 切记不能混用

### 多行语句
Python语句中一般以新行作为语句的结束符。

但是我们可以使用斜杠（ \ ）将一行的语句分为多行显示，如下所示：
```
total = item_one + \
        item_two + \
        item_three
```
语句中包含 [ ], { } 或 ( ) 括号就不需要使用多行连接符。如下实例：
```
days = ['Monday', 'Tuesday', 'Wednesday',
        'Thursday', 'Friday']
```

### Python 引号
Python 可以使用引号( ' )、双引号( " )、三引号( ''' 或 """ ) 来表示字符串，引号的开始与结束必须是相同类型的。

其中三引号可以由多行组成，编写多行文本的快捷语法，常用于文档字符串，在文件的特定地点，被当做注释。
```
word = 'word'
sentence = "这是一个句子。"
paragraph = """这是一个段落。
包含了多个语句"""
```

### Python 注释
python中单行注释采用 # 开头。
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
# 文件名：test.py

# 第一个注释
print ("Hello, Python!")  # 第二个注释
```
输出结果：
```
Hello, Python!
```
注释可以在语句或表达式行末：
```
name = "Madisetti" # 这是一个注释
```
python 中多行注释使用三个单引号(''')或三个双引号(""")。
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
# 文件名：test.py


'''
这是多行注释，使用单引号。
这是多行注释，使用单引号。
这是多行注释，使用单引号。
'''

"""
这是多行注释，使用双引号。
这是多行注释，使用双引号。
这是多行注释，使用双引号。
"""
```

### Python 空行
函数之间或类的方法之间用空行分隔，表示一段新的代码的开始。类和函数入口之间也用一行空行分隔，以突出函数入口的开始。

空行与代码缩进不同，空行并不是Python语法的一部分。书写时不插入空行，Python解释器运行也不会出错。但是空行的作用在于分隔两段不同功能或含义的代码，便于日后代码的维护或重构。

记住：空行也是程序代码的一部分。

### 等待用户输入
下面的程序执行后就会等待用户输入，按回车键后就会退出：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-

raw_input("按下 enter 键退出，其他任意键显示...\n")
```
以上代码中 ，\n 实现换行。一旦用户按下 enter(回车) 键退出，其它键显示。

### 同一行显示多条语句
Python可以在同一行中使用多条语句，语句之间使用分号(;)分割，以下是一个简单的实例：
```
#!/usr/bin/python

import sys; x = 'runoob'; sys.stdout.write(x + '\n')
```
执行以上代码，输入结果为：
```
$ python test.py
runoob
```

### print 输出
print 默认输出是换行的，如果要实现不换行需要在变量末尾加上逗号 ,。
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-

x="a"
y="b"
# 换行输出
print x
print y

print '---------'
# 不换行输出
print x,
print y,

# 不换行输出
print x,y
```
以上实例执行结果为：
```
a
b
---------
a b a b
```

### 多个语句构成代码组
缩进相同的一组语句构成一个代码块，我们称之代码组。

像if、while、def和class这样的复合语句，首行以关键字开始，以冒号( : )结束，该行之后的一行或多行代码构成代码组。

我们将首行及后面的代码组称为一个子句(clause)。

如下实例：
```
if expression : 
   suite 
elif expression :  
   suite  
else :  
   suite 
```

### 命令行参数
很多程序可以执行一些操作来查看一些基本信息，Python 可以使用 -h 参数查看各参数帮助信息：
```
$ python -h 
usage: python [option] ... [-c cmd | -m mod | file | -] [arg] ... 
Options and arguments (and corresponding environment variables): 
-c cmd : program passed in as string (terminates option list) 
-d     : debug output from parser (also PYTHONDEBUG=x) 
-E     : ignore environment variables (such as PYTHONPATH) 
-h     : print this help message and exit 
 
[ etc. ] 
```
我们在使用脚本形式执行 Python 时，可以接收命令行输入的参数，具体使用可以参照 Python 命令行参数。

### Python 命令行参数
Python 提供了 getopt 模块来获取命令行参数。
```
$ python test.py arg1 arg2 arg3
```
Python 中也可以使用 sys 的 sys.argv 来获取命令行参数：

1)sys.argv 是命令行参数列表。

2)len(sys.argv) 是命令行参数个数。

注：sys.argv[0] 表示脚本名。

test.py 文件代码如下：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-

import sys

print '参数个数为:', len(sys.argv), '个参数。'
print '参数列表:', str(sys.argv)
```
执行以上代码，输出结果为：
```
$ python test.py arg1 arg2 arg3
参数个数为: 4 个参数。
参数列表: ['test.py', 'arg1', 'arg2', 'arg3']
```

### getopt模块
getopt模块是专门处理命令行参数的模块，用于获取命令行选项和参数，也就是sys.argv。命令行选项使得程序的参数更加灵活。支持短选项模式（-）和长选项模式（--）。

该模块提供了两个方法及一个异常处理来解析命令行参数。

getopt.getopt 方法

getopt.getopt 方法用于解析命令行参数列表，语法格式如下：
```
getopt.getopt(args, options[, long_options])
```

方法参数说明：

1)args: 要解析的命令行参数列表。

2)options : 以字符串的格式定义，options 后的冒号 : 表示如果设置该选项，必须有附加的参数，否则就不附加参数。

3)long_options : 以列表的格式定义，long_options 后的等号 = 表示该选项必须有附加的参数，不带冒号表示该选项不附加参数。

4)该方法返回值由两个元素组成: 第一个是 (option, value) 元组的列表。 第二个是参数列表，包含那些没有 - 或 -- 的参数。

另外一个方法是 getopt.gnu_getopt，这里不多做介绍。

### Exception getopt.GetoptError
在没有找到参数列表，或选项的需要的参数为空时会触发该异常。

异常的参数是一个字符串，表示错误的原因。属性 msg 和 opt 为相关选项的错误信息。

## 六、Python 变量类型
变量存储在内存中的值，这就意味着在创建变量时会在内存中开辟一个空间。

基于变量的数据类型，解释器会分配指定内存，并决定什么数据可以被存储在内存中。

因此，变量可以指定不同的数据类型，这些变量可以存储整数，小数或字符。

### 变量赋值

Python 中的变量赋值不需要类型声明。

每个变量在内存中创建，都包括变量的标识，名称和数据这些信息。

每个变量在使用前都必须赋值，变量赋值以后该变量才会被创建。

等号 = 用来给变量赋值。

等号 = 运算符左边是一个变量名，等号 = 运算符右边是存储在变量中的值。例如：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
counter = 100 # 赋值整型变量
miles = 1000.0 # 浮点型
name = "John" # 字符串
 
print counter
print miles
print name
```
以上实例中，100，1000.0和"John"分别赋值给counter，miles，name变量。

执行以上程序会输出如下结果：
```
100
1000.0
John
```

### 多个变量赋值
Python允许你同时为多个变量赋值。例如：
```
a = b = c = 1
```
以上实例，创建一个整型对象，值为1，三个变量被分配到相同的内存空间上。

您也可以为多个对象指定多个变量。例如：
```
a, b, c = 1, 2, "john"
```
以上实例，两个整型对象 1 和 2 分别分配给变量 a 和 b，字符串对象 "john" 分配给变量 c。

### 标准数据类型
在内存中存储的数据可以有多种类型。

例如，一个人的年龄可以用数字来存储，他的名字可以用字符来存储。

Python 定义了一些标准类型，用于存储各种类型的数据。

Python有五个标准的数据类型：

1)Numbers（数字）
2)String（字符串）
3)List（列表）4)Tuple（元组）
5)Dictionary（字典）

### Python数字
数字数据类型用于存储数值。

他们是不可改变的数据类型，这意味着改变数字数据类型会分配一个新的对象。

当你指定一个值时，Number 对象就会被创建：
```
var1 = 1
var2 = 10
```
您也可以使用del语句删除一些对象的引用。

del语句的语法是：
```
del var1[,var2[,var3[....,varN]]]
```
您可以通过使用del语句删除单个或多个对象的引用。例如：
```
del var
del var_a, var_b
```
Python支持四种不同的数字类型：

1)int（有符号整型）
2)long（长整型[也可以代表八进制和十六进制]）
3)float（浮点型）
4)complex（复数）
```
int   	 long                 	float	         complex
10	     51924361L	            0.0	           3.14j
100	     -0x19323L	            15.20	         45.j
-786	   0122L	                -21.9	         9.322e-36j
080	     0xDEFABCECBDAECBFBAEl	32.3e+18	     .876j
-0490	   535633629843L	        -90.	         -.6545+0J
-0x260	 -052318172735L	        -32.54e100	   3e+26J
0x69	   -4721885298529L	      70.2E-12	     4.53e-7j
```
1)长整型也可以使用小写 l，但是还是建议您使用大写 L，避免与数字 1 混淆。Python使用 L 来显示长整型。
2)Python 还支持复数，复数由实数部分和虚数部分构成，可以用 a + bj,或者 complex(a,b) 表示， 复数的实部 a 和虚部 b 都是浮点型。

注意：long 类型只存在于 Python2.X 版本中，在 2.2 以后的版本中，int 类型数据溢出后会自动转为long类型。在 Python3.X 版本中 long 类型被移除，使用 int 替代。

### Python字符串
字符串或串(String)是由数字、字母、下划线组成的一串字符。

一般记为 :
```
s = "a1a2···an"   # n>=0
```
它是编程语言中表示文本的数据类型。

python的字串列表有2种取值顺序:

1)从左到右索引默认0开始的，最大范围是字符串长度少1

2)从右到左索引默认-1开始的，最大范围是字符串开头

如果你要实现从字符串中获取一段子字符串的话，可以使用 [头下标:尾下标] 来截取相应的字符串，其中下标是从 0 开始算起，可以是正数或负数，下标可以为空表示取到头或尾。

[头下标:尾下标] 获取的子字符串包含头下标的字符，但不包含尾下标的字符。

比如:
```
>>> s = 'abcdef'
>>> s[1:5]
'bcde'
```
当使用以冒号分隔的字符串，python 返回一个新的对象，结果包含了以这对偏移标识的连续的内容，左边的开始是包含了下边界。

上面的结果包含了 s[1] 的值 b，而取到的最大范围不包括尾下标，就是 s[5] 的值 f。
```
从后面索引： -6 -5 -4 -3 -2 -1
从前面索引：  0  1  2  3  4  5 
             a  b  c  d  e  f
从前面截取： ： 1  2  3  4  5  ：
从后面截取： ：-5 -4 -3 -2 -1  ：
```
加号（+）是字符串连接运算符，星号（*）是重复操作。如下实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
str = 'Hello World!'
 
print str           # 输出完整字符串
print str[0]        # 输出字符串中的第一个字符
print str[2:5]      # 输出字符串中第三个至第六个之间的字符串
print str[2:]       # 输出从第三个字符开始的字符串
print str * 2       # 输出字符串两次
print str + "TEST"  # 输出连接的字符串
```
以上实例输出结果：
```
Hello World!
H
llo
llo World!
Hello World!Hello World!
Hello World!TEST
```
Python 列表截取可以接收第三个参数，参数作用是截取的步长，以下实例在索引 1 到索引 4 的位置并设置为步长为 2（间隔一个位置）来截取字符串：
```
>>> j=['a','b','c','d','e','f','g','h']
>>> j
['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h']
>>> j[::2] #第三个参数（步长）可以理解为间隔的意思。
['a', 'c', 'e', 'g']
>>> j[::3]
['a', 'd', 'g']
>>> j[1:6:3]
['b', 'e']
```

### Python列表
List（列表） 是 Python 中使用最频繁的数据类型。

列表可以完成大多数集合类的数据结构实现。它支持字符，数字，字符串甚至可以包含列表（即嵌套）。

列表用 [ ] 标识，是 python 最通用的复合数据类型。

列表中值的切割也可以用到变量 [头下标:尾下标] ，就可以截取相应的列表，从左到右索引默认 0 开始，从右到左索引默认 -1 开始，下标可以为空表示取到头或尾。
```
同字符串
```
加号 + 是列表连接运算符，星号 * 是重复操作。如下实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
list = [ 'runoob', 786 , 2.23, 'john', 70.2 ]
tinylist = [123, 'john']
 
print list               # 输出完整列表
print list[0]            # 输出列表的第一个元素
print list[1:3]          # 输出第二个至第三个元素 
print list[2:]           # 输出从第三个开始至列表末尾的所有元素
print tinylist * 2       # 输出列表两次
print list + tinylist    # 打印组合的列表
```
以上实例输出结果：
```
['runoob', 786, 2.23, 'john', 70.2]
runoob
[786, 2.23]
[2.23, 'john', 70.2]
[123, 'john', 123, 'john']
['runoob', 786, 2.23, 'john', 70.2, 123, 'john']
```

### Python元组
元组是另一个数据类型，类似于 List（列表）。

元组用 () 标识。内部元素用逗号隔开。但是元组不能二次赋值，相当于只读列表。
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
tuple = ( 'runoob', 786 , 2.23, 'john', 70.2 )
tinytuple = (123, 'john')
 
print tuple               # 输出完整元组
print tuple[0]            # 输出元组的第一个元素
print tuple[1:3]          # 输出第二个至第四个（不包含）的元素 
print tuple[2:]           # 输出从第三个开始至列表末尾的所有元素
print tinytuple * 2       # 输出元组两次
print tuple + tinytuple   # 打印组合的元组
```
以上实例输出结果：
```
('runoob', 786, 2.23, 'john', 70.2)
runoob
(786, 2.23)
(2.23, 'john', 70.2)
(123, 'john', 123, 'john')
('runoob', 786, 2.23, 'john', 70.2, 123, 'john')
```
以下是元组无效的，因为元组是不允许更新的。而列表是允许更新的：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
tuple = ( 'runoob', 786 , 2.23, 'john', 70.2 )
list = [ 'runoob', 786 , 2.23, 'john', 70.2 ]
tuple[2] = 1000    # 元组中是非法应用
list[2] = 1000     # 列表中是合法应用
```

### Python字典
字典(dictionary)是除列表以外python之中最灵活的内置数据结构类型。列表是有序的对象集合，字典是无序的对象集合。

两者之间的区别在于：字典当中的元素是通过键来存取的，而不是通过偏移存取。

字典用"{ }"标识。字典由索引(key)和它对应的值value组成。
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
dict = {}
dict['one'] = "This is one"
dict[2] = "This is two"
 
tinydict = {'name': 'runoob','code':6734, 'dept': 'sales'}
 
 
print dict['one']          # 输出键为'one' 的值
print dict[2]              # 输出键为 2 的值
print tinydict             # 输出完整的字典
print tinydict.keys()      # 输出所有键
print tinydict.values()    # 输出所有值
```
输出结果为：
```
This is one
This is two
{'dept': 'sales', 'code': 6734, 'name': 'runoob'}
['dept', 'code', 'name']
['sales', 6734, 'runoob']
```

### Python数据类型转换
有时候，我们需要对数据内置的类型进行转换，数据类型的转换，你只需要将数据类型作为函数名即可。

以下几个内置的函数可以执行数据类型之间的转换。这些函数返回一个新的对象，表示转换的值。
```
函数	描述
int(x [,base])  将x转换为一个整数

long(x [,base] )  将x转换为一个长整数

float(x)  将x转换到一个浮点数

complex(real [,imag])  创建一个复数

str(x)  将对象 x 转换为字符串

repr(x)  将对象 x 转换为表达式字符串

eval(str)  用来计算在字符串中的有效Python表达式,并返回一个对象

tuple(s)  将序列 s 转换为一个元组

list(s)  将序列 s 转换为一个列表

set(s)  转换为可变集合

dict(d)  创建一个字典。d 必须是一个序列 (key,value)元组。

frozenset(s)  转换为不可变集合

chr(x)  将一个整数转换为一个字符

unichr(x)  将一个整数转换为Unicode字符

ord(x)  将一个字符转换为它的整数值

hex(x)  将一个整数转换为一个十六进制字符串

oct(x)  将一个整数转换为一个八进制字符串
```

## 七、Pythoon 运算符

### 什么是运算符？
本章节主要说明Python的运算符。举个简单的例子 4 +5 = 9 。 例子中，4 和 5 被称为操作数，"+" 称为运算符。

Python语言支持以下类型的运算符:
```
算术运算符
比较（关系）运算符
赋值运算符
逻辑运算符
位运算符
成员运算符
身份运算符
运算符优先级
```
接下来让我们一个个来学习Python的运算符。

### Python算术运算符
以下假设变量： a=10，b=20：
```
运算符	    描述	                                            实例
+	      加 - 两个对象相加	                                a + b 输出结果 30
-	      减 - 得到负数或是一个数减去另一个数	                a - b 输出结果 -10
*	      乘 - 两个数相乘或是返回一个被重复若干次的字符串	     a * b 输出结果 200
/	      除 - x除以y	                                      b / a 输出结果 2
%	      取模 - 返回除法的余数	                             b % a 输出结果 0
**	    幂 - 返回x的y次幂	                                 a**b 为10的20次方， 输出结果 100000000000000000000
//	    取整除 - 返回商的整数部分（向下取整）	               >>> 9//2  4  >>> -9//2  -5
```
以下实例演示了Python所有算术运算符的操作：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 21
b = 10
c = 0
 
c = a + b
print "1 - c 的值为：", c
 
c = a - b
print "2 - c 的值为：", c 
 
c = a * b
print "3 - c 的值为：", c 
 
c = a / b
print "4 - c 的值为：", c 
 
c = a % b
print "5 - c 的值为：", c
 
# 修改变量 a 、b 、c
a = 2
b = 3
c = a**b 
print "6 - c 的值为：", c
 
a = 10
b = 5
c = a//b 
print "7 - c 的值为：", c
```
以上实例输出结果：
```
1 - c 的值为： 31
2 - c 的值为： 11
3 - c 的值为： 210
4 - c 的值为： 2
5 - c 的值为： 1
6 - c 的值为： 8
7 - c 的值为： 2
```
注意：Python2.x 里，整数除整数，只能得出整数。如果要得到小数部分，把其中一个数改成浮点数即可。
```
>>> 1/2
0
>>> 1.0/2
0.5
>>> 1/float(2)
0.5
```

### Python比较运算符
以下假设变量a为10，变量b为20：
```
运算符	            描述	                              实例
==	   等于 - 比较对象是否相等	                  (a == b) 返回 False。
!=	   不等于 - 比较两个对象是否不相等 	           (a != b) 返回 true.
<>	   不等于 - 比较两个对象是否不相等。python3 已废弃。	(a <> b) 返回 true。这个运算符类似 != 。
>	     大于 - 返回x是否大于y	                    (a > b) 返回 False。
<	     小于 - 返回x是否小于y。所有比较运算符返回1表示真，返回0表示假。这分别与特殊的变量True和False等价。	(a < b) 返回 true。
>=	   大于等于 - 返回x是否大于等于y。 	           (a >= b) 返回 False。
<=	   小于等于 - 返回x是否小于等于y。	           (a <= b) 返回 true。
```
以下实例演示了Python所有比较运算符的操作：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 21
b = 10
c = 0
 
if  a == b :
   print "1 - a 等于 b"
else:
   print "1 - a 不等于 b"
 
if  a != b :
   print "2 - a 不等于 b"
else:
   print "2 - a 等于 b"
 
if  a <> b :
   print "3 - a 不等于 b"
else:
   print "3 - a 等于 b"
 
if  a < b :
   print "4 - a 小于 b" 
else:
   print "4 - a 大于等于 b"
 
if  a > b :
   print "5 - a 大于 b"
else:
   print "5 - a 小于等于 b"
 
# 修改变量 a 和 b 的值
a = 5
b = 20
if  a <= b :
   print "6 - a 小于等于 b"
else:
   print "6 - a 大于  b"
 
if  b >= a :
   print "7 - b 大于等于 a"
else:
   print "7 - b 小于 a"
```
以上实例输出结果：
```
1 - a 不等于 b
2 - a 不等于 b
3 - a 不等于 b
4 - a 大于等于 b
5 - a 大于 b
6 - a 小于等于 b
7 - b 大于等于 a
```

### Python赋值运算符
以下假设变量a为10，变量b为20：
```
运算符	         描述	                       实例
=	         简单的赋值运算符	        c = a + b 将 a + b 的运算结果赋值为 c
+=	       加法赋值运算符	          c += a 等效于 c = c + a
-=	       减法赋值运算符	          c -= a 等效于 c = c - a
*=	       乘法赋值运算符	          c *= a 等效于 c = c * a
/=	       除法赋值运算符	          c /= a 等效于 c = c / a
%=	       取模赋值运算符	          c %= a 等效于 c = c % a
**=	       幂赋值运算符             c **= a 等效于 c = c ** a
//=	       取整除赋值运算符	        c //= a 等效于 c = c // a
```
以下实例演示了Python所有赋值运算符的操作：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 21
b = 10
c = 0
 
c = a + b
print "1 - c 的值为：", c
 
c += a
print "2 - c 的值为：", c 
 
c *= a
print "3 - c 的值为：", c 
 
c /= a 
print "4 - c 的值为：", c 
 
c = 2
c %= a
print "5 - c 的值为：", c
 
c **= a
print "6 - c 的值为：", c
 
c //= a
print "7 - c 的值为：", c
```
以上实例输出结果：
```
1 - c 的值为： 31
2 - c 的值为： 52
3 - c 的值为： 1092
4 - c 的值为： 52
5 - c 的值为： 2
6 - c 的值为： 2097152
7 - c 的值为： 99864
```

### Python位运算符
按位运算符是把数字看作二进制来进行计算的。Python中的按位运算法则如下：

下表中变量 a 为 60，b 为 13，二进制格式如下：
```
a = 0011 1100

b = 0000 1101

-----------------

a&b = 0000 1100

a|b = 0011 1101

a^b = 0011 0001

~a  = 1100 0011
```
```
运算符        	                  描述                           	                                    实例
&	      按位与运算符：参与运算的两个值,如果两个相应位都为1,则该位的结果为1,否则为0	                 (a & b) 输出结果 12 ，二进制解释： 0000 1100
|	按位或运算符：只要对应的二个二进位有一个为1时，结果位就为1。                    	                (a | b) 输出结果 61 ，二进制解释： 0011 1101
^	按位异或运算符：当两对应的二进位相异时，结果为1	                                                 (a ^ b) 输出结果 49 ，二进制解释： 0011 0001
~	按位取反运算符：对数据的每个二进制位取反,即把1变为0,把0变为1 。~x 类似于 -x-1	                     (~a ) 输出结果 -61 ，二进制解释： 1100 0011，在一个有符号二进制数的补码形式。
<<	左移动运算符：运算数的各二进位全部左移若干位，由 << 右边的数字指定了移动的位数，高位丢弃，低位补0。	a << 2 输出结果 240 ，二进制解释： 1111 0000
>>	右移动运算符：把">>"左边的运算数的各二进位全部右移若干位，>> 右边的数字指定了移动的位数	           a >> 2 输出结果 15 ，二进制解释： 0000 1111
```
以下实例演示了Python所有位运算符的操作：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 60            # 60 = 0011 1100 
b = 13            # 13 = 0000 1101 
c = 0
 
c = a & b;        # 12 = 0000 1100
print "1 - c 的值为：", c
 
c = a | b;        # 61 = 0011 1101 
print "2 - c 的值为：", c
 
c = a ^ b;        # 49 = 0011 0001
print "3 - c 的值为：", c
 
c = ~a;           # -61 = 1100 0011
print "4 - c 的值为：", c
 
c = a << 2;       # 240 = 1111 0000
print "5 - c 的值为：", c
 
c = a >> 2;       # 15 = 0000 1111
print "6 - c 的值为：", c
```
以上实例输出结果：
```
1 - c 的值为： 12
2 - c 的值为： 61
3 - c 的值为： 49
4 - c 的值为： -61
5 - c 的值为： 240
6 - c 的值为： 15
```

### Python逻辑运算符
Python语言支持逻辑运算符，以下假设变量 a 为 10, b为 20:
```
运算符   逻辑表达式	                          描述	                                                   实例
and	   x and y	  布尔"与" - 如果 x 为 False，x and y 返回 False，否则它返回 y 的计算值。	    (a and b) 返回 20。
or	      x or y	  布尔"或" - 如果 x 是非 0，它返回 x 的值，否则它返回 y 的计算值。	           (a or b) 返回 10。
not	   not x	     布尔"非" - 如果 x 为 True，返回 False 。如果 x 为 False，它返回 True。	    not(a and b) 返回 False
```
以上实例输出结果：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 10
b = 20
 
if  a and b :
   print "1 - 变量 a 和 b 都为 true"
else:
   print "1 - 变量 a 和 b 有一个不为 true"
 
if  a or b :
   print "2 - 变量 a 和 b 都为 true，或其中一个变量为 true"
else:
   print "2 - 变量 a 和 b 都不为 true"
 
# 修改变量 a 的值
a = 0
if  a and b :
   print "3 - 变量 a 和 b 都为 true"
else:
   print "3 - 变量 a 和 b 有一个不为 true"
 
if  a or b :
   print "4 - 变量 a 和 b 都为 true，或其中一个变量为 true"
else:
   print "4 - 变量 a 和 b 都不为 true"
 
if not( a and b ):
   print "5 - 变量 a 和 b 都为 false，或其中一个变量为 false"
else:
   print "5 - 变量 a 和 b 都为 true"
```

### Python成员运算符
除了以上的一些运算符之外，Python还支持成员运算符，测试实例中包含了一系列的成员，包括字符串，列表或元组。
```
运算符	               描述	                                                        实例
in	       如果在指定的序列中找到值返回 True，否则返回 False。	         x 在 y 序列中 , 如果 x 在 y 序列中返回 True。
not in	 如果在指定的序列中没有找到值返回 True，否则返回 False。	       x 不在 y 序列中 , 如果 x 不在 y 序列中返回 True。
```
以下实例演示了Python所有成员运算符的操作：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 10
b = 20
list = [1, 2, 3, 4, 5 ];
 
if ( a in list ):
   print "1 - 变量 a 在给定的列表中 list 中"
else:
   print "1 - 变量 a 不在给定的列表中 list 中"
 
if ( b not in list ):
   print "2 - 变量 b 不在给定的列表中 list 中"
else:
   print "2 - 变量 b 在给定的列表中 list 中"
 
# 修改变量 a 的值
a = 2
if ( a in list ):
   print "3 - 变量 a 在给定的列表中 list 中"
else:
   print "3 - 变量 a 不在给定的列表中 list 中"
```
以上实例输出结果：
```
1 - 变量 a 不在给定的列表中 list 中
2 - 变量 b 不在给定的列表中 list 中
3 - 变量 a 在给定的列表中 list 中
```

### Python身份运算符
身份运算符用于比较两个对象的存储单元
```
运算符	                      描述	                                              实例
is	        is 是判断两个标识符是不是引用自一个对象	              x is y, 类似 id(x) == id(y) , 如果引用的是同一个对象则返回 True，否则返回 False
is not	  is not 是判断两个标识符是不是引用自不同对象	           x is not y ， 类似 id(a) != id(b)。如果引用的不是同一个对象则返回结果 True，否则返回 False。
```
注： id() 函数用于获取对象内存地址。

以下实例演示了Python所有身份运算符的操作：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 20
b = 20
 
if ( a is b ):
   print "1 - a 和 b 有相同的标识"
else:
   print "1 - a 和 b 没有相同的标识"
 
if ( a is not b ):
   print "2 - a 和 b 没有相同的标识"
else:
   print "2 - a 和 b 有相同的标识"
 
# 修改变量 b 的值
b = 30
if ( a is b ):
   print "3 - a 和 b 有相同的标识"
else:
   print "3 - a 和 b 没有相同的标识"
 
if ( a is not b ):
   print "4 - a 和 b 没有相同的标识"
else:
   print "4 - a 和 b 有相同的标识"
```
以上实例输出结果：
```
1 - a 和 b 有相同的标识
2 - a 和 b 有相同的标识
3 - a 和 b 没有相同的标识
4 - a 和 b 没有相同的标识
```
is 与 == 区别：

is 用于判断两个变量引用对象是否为同一个(同一块内存空间)， == 用于判断引用变量的值是否相等。
```
>>> a = [1, 2, 3]
>>> b = a
>>> b is a 
True
>>> b == a
True
>>> b = a[:]
>>> b is a
False
>>> b == a
True
```

### Python运算符优先级
以下表格列出了从最高到最低优先级的所有运算符：
```
运算符	                        描述
**	                        指数 (最高优先级)
~ + -	                     按位翻转, 一元加号和减号 (最后两个的方法名为 +@ 和 -@)
* / % //	                  乘，除，取模和取整除
+ -	                     加法减法
>> <<	                     右移，左移运算符
&	                        位 'AND'
^ |	                     位运算符
<= < > >=	               比较运算符
<> == !=	                  等于运算符
= %= /= //= -= += *= **=	赋值运算符
is is not	               身份运算符
in not in	               成员运算符
not and or	               逻辑运算符
```
以下实例演示了Python所有运算符优先级的操作：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = 20
b = 10
c = 15
d = 5
e = 0
 
e = (a + b) * c / d       #( 30 * 15 ) / 5
print "(a + b) * c / d 运算结果为：",  e
 
e = ((a + b) * c) / d     # (30 * 15 ) / 5
print "((a + b) * c) / d 运算结果为：",  e
 
e = (a + b) * (c / d);    # (30) * (15/5)
print "(a + b) * (c / d) 运算结果为：",  e
 
e = a + (b * c) / d;      #  20 + (150/5)
print "a + (b * c) / d 运算结果为：",  e
```
以上实例输出结果：
```
(a + b) * c / d 运算结果为： 90
((a + b) * c) / d 运算结果为： 90
(a + b) * (c / d) 运算结果为： 90
a + (b * c) / d 运算结果为： 50
```

## 八、Python 条件语句

### Python条件语句
Python条件语句是通过一条或多条语句的执行结果（True或者False）来决定执行的代码块。

可以通过下图来简单了解条件语句的执行过程:

Python程序语言指定任何非0和非空（null）值为true，0 或者 null为false。

Python 编程中 if 语句用于控制程序的执行，基本形式为：
```
if 判断条件：
    执行语句……
else：
    执行语句……
```
其中"判断条件"成立时（非零），则执行后面的语句，而执行内容可以多行，以缩进来区分表示同一范围。

else 为可选语句，当需要在条件不成立时执行内容则可以执行相关语句。

具体例子如下：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
# 例1：if 基本用法
 
flag = False
name = 'luren'
if name == 'python':         # 判断变量是否为 python 
    flag = True              # 条件成立时设置标志为真
    print 'welcome boss'     # 并输出欢迎信息
else:
    print name               # 条件不成立时输出变量名称
```
输出结果为：
```
luren            # 输出结果
```
if 语句的判断条件可以用>（大于）、<(小于)、==（等于）、>=（大于等于）、<=（小于等于）来表示其关系。

当判断条件为多个值时，可以使用以下形式：
```
if 判断条件1:
    执行语句1……
elif 判断条件2:
    执行语句2……
elif 判断条件3:
    执行语句3……
else:
    执行语句4……
```
实例如下：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
# 例2：elif用法
 
num = 5     
if num == 3:            # 判断num的值
    print 'boss'        
elif num == 2:
    print 'user'
elif num == 1:
    print 'worker'
elif num < 0:           # 值小于零时输出
    print 'error'
else:
    print 'roadman'     # 条件均不成立时输出
```
输出结果为：
```
roadman        # 输出结果
```
由于 python 并不支持 switch 语句，所以多个条件判断，只能用 elif 来实现，如果判断需要多个条件需同时判断时，可以使用 or （或），表示两个条件有一个成立时判断条件成功；使用 and （与）时，表示只有两个条件同时成立的情况下，判断条件才成功。
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
# 例3：if语句多个条件
 
num = 9
if num >= 0 and num <= 10:    # 判断值是否在0~10之间
    print 'hello'
# 输出结果: hello
 
num = 10
if num < 0 or num > 10:    # 判断值是否在小于0或大于10
    print 'hello'
else:
    print 'undefine'
# 输出结果: undefine
 
num = 8
# 判断值是否在0~5或者10~15之间
if (num >= 0 and num <= 5) or (num >= 10 and num <= 15):    
    print 'hello'
else:
    print 'undefine'
# 输出结果: undefine
```
当if有多个条件时可使用括号来区分判断的先后顺序，括号中的判断优先执行，此外 and 和 or 的优先级低于>（大于）、<（小于）等判断符号，即大于和小于在没有括号的情况下会比与或要优先判断。

### 简单的语句组
你也可以在同一行的位置上使用if条件判断语句，如下实例：
```
#!/usr/bin/python 
# -*- coding: UTF-8 -*-
 
var = 100 
 
if ( var  == 100 ) : print "变量 var 的值为100" 
 
print "Good bye!"
```
以上代码执行输出结果如下：
```
变量 var 的值为100
Good bye!
```

## 九、Python 循环语句

本章节将向大家介绍Python的循环语句，程序在一般情况下是按顺序执行的。

编程语言提供了各种控制结构，允许更复杂的执行路径。

循环语句允许我们执行一个语句或语句组多次，下面是在大多数编程语言中的循环语句的一般形式：

Python 提供了 for 循环和 while 循环（在 Python 中没有 do..while 循环）:
```
循环类型             	          描述
while 循环          在给定的判断条件为 true 时执行循环体，否则退出循环体。
for 循环            重复执行语句
嵌套循环            你可以在while循环体中嵌套for循环
```

### 循环控制语句
循环控制语句可以更改语句执行的顺序。Python支持以下循环控制语句：
```
控制语句                           描述
break 语句         在语句块执行过程中终止循环，并且跳出整个循环
continue 语句      在语句块执行过程中终止当前循环，跳出该次循环，执行下一次循环。
pass 语句          pass是空语句，是为了保持程序结构的完整性。
```

## 十、Python While 循环语句
Python 编程中 while 语句用于循环执行程序，即在某条件下，循环执行某段程序，以处理需要重复处理的相同任务。其基本形式为：
```
while 判断条件(condition)：
    执行语句(statements)……
```
执行语句可以是单个语句或语句块。判断条件可以是任何表达式，任何非零、或非空（null）的值均为true。

当判断条件假 false 时，循环结束。

执行流程图如下：

实例：
```
#!/usr/bin/python
 
count = 0
while (count < 9):
   print 'The count is:', count
   count = count + 1
 
print "Good bye!"
```
以上代码执行输出结果:
```
The count is: 0
The count is: 1
The count is: 2
The count is: 3
The count is: 4
The count is: 5
The count is: 6
The count is: 7
The count is: 8
Good bye!
```
while 语句时还有另外两个重要的命令 continue，break 来跳过循环，continue 用于跳过该次循环，break 则是用于退出循环，此外"判断条件"还可以是个常值，表示循环必定成立，具体用法如下：
```
# continue 和 break 用法
 
i = 1
while i < 10:   
    i += 1
    if i%2 > 0:     # 非双数时跳过输出
        continue
    print i         # 输出双数2、4、6、8、10
 
i = 1
while 1:            # 循环条件为1必定成立
    print i         # 输出1~10
    i += 1
    if i > 10:     # 当i大于10时跳出循环
        break
```

### 无限循环
如果条件判断语句永远为 true，循环将会无限的执行下去，如下实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
var = 1
while var == 1 :  # 该条件永远为true，循环将无限执行下去
   num = raw_input("Enter a number  :")
   print "You entered: ", num
 
print "Good bye!"
```
以上实例输出结果：
```
Enter a number  :20
You entered:  20
Enter a number  :29
You entered:  29
Enter a number  :3
You entered:  3
Enter a number between :Traceback (most recent call last):
  File "test.py", line 5, in <module>
    num = raw_input("Enter a number :")
KeyboardInterrupt
```
注意：以上的无限循环你可以使用 CTRL+C 来中断循环。

### 循环使用else语句
在 python 中，while … else 在循环条件为 false 时执行 else 语句块：
```
#!/usr/bin/python
 
count = 0
while count < 5:
   print count, " is  less than 5"
   count = count + 1
else:
   print count, " is not less than 5"
```
以上实例输出结果为：
0 is less than 5
1 is less than 5
2 is less than 5
3 is less than 5
4 is less than 5
5 is not less than 5

### 简单语句组
类似 if 语句的语法，如果你的 while 循环体中只有一条语句，你可以将该语句与while写在同一行中， 如下所示：
```
#!/usr/bin/python
 
flag = 1
 
while (flag): print 'Given flag is really true!'
 
print "Good bye!"
```
注意：以上的无限循环你可以使用 CTRL+C 来中断循环。

## 十一、Python for 循环语句

Python for循环可以遍历任何序列的项目，如一个列表或者一个字符串。

语法：

for循环的语法格式如下：
```
for iterating_var in sequence:
   statements(s)
```
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
for letter in 'Python':     # 第一个实例
   print '当前字母 :', letter
 
fruits = ['banana', 'apple',  'mango']
for fruit in fruits:        # 第二个实例
   print '当前水果 :', fruit
 
print "Good bye!"
```
以上实例输出结果:
```
当前字母 : P
当前字母 : y
当前字母 : t
当前字母 : h
当前字母 : o
当前字母 : n
当前水果 : banana
当前水果 : apple
当前水果 : mango
Good bye!
```

### 通过序列索引迭代
另外一种执行循环的遍历方式是通过索引，如下实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
fruits = ['banana', 'apple',  'mango']
for index in range(len(fruits)):
   print '当前水果 :', fruits[index]
 
print "Good bye!"
```
以上实例输出结果：
```
当前水果 : banana
当前水果 : apple
当前水果 : mango
Good bye!
```
以上实例我们使用了内置函数 len() 和 range(),函数 len() 返回列表的长度，即元素的个数。 range返回一个序列的数。

### 循环使用else语句
在 python 中，for … else 表示这样的意思，for 中的语句和普通的没有区别，else 中的语句会在循环正常执行完（即 for 不是通过 break 跳出而中断的）的情况下执行，while … else 也是一样。
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
for num in range(10,20):  # 迭代 10 到 20 之间的数字
   for i in range(2,num): # 根据因子迭代
      if num%i == 0:      # 确定第一个因子
         j=num/i          # 计算第二个因子
         print '%d 等于 %d * %d' % (num,i,j)
         break            # 跳出当前循环
   else:                  # 循环的 else 部分
      print num, '是一个质数'
```
以上实例输出结果：
```
10 等于 2 * 5
11 是一个质数
12 等于 2 * 6
13 是一个质数
14 等于 2 * 7
15 等于 3 * 5
16 等于 2 * 8
17 是一个质数
18 等于 2 * 9
19 是一个质数
```

## 十二、Python 循环嵌套
Python 语言允许在一个循环体里面嵌入另一个循环。
Python for 循环嵌套语法：
```
for iterating_var in sequence:
   for iterating_var in sequence:
      statements(s)
   statements(s)
```
Python while 循环嵌套语法：
```
while expression:
   while expression:
      statement(s)
   statement(s)
```
你可以在循环体内嵌入其他的循环体，如在while循环中可以嵌入for循环， 反之，你可以在for循环中嵌入while循环。

以下实例使用了嵌套循环输出2~100之间的素数：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
i = 2
while(i < 100):
   j = 2
   while(j <= (i/j)):
      if not(i%j): break
      j = j + 1
   if (j > i/j) : print i, " 是素数"
   i = i + 1
 
print "Good bye!"
```
以上实例输出结果:
```
2 是素数
3 是素数
5 是素数
7 是素数
11 是素数
13 是素数
17 是素数
19 是素数
23 是素数
29 是素数
31 是素数
37 是素数
41 是素数
43 是素数
47 是素数
53 是素数
59 是素数
61 是素数
67 是素数
71 是素数
73 是素数
79 是素数
83 是素数
89 是素数
97 是素数
Good bye!
```

## 十三、Python break 语句
Python break语句，就像在C语言中，打破了最小封闭for或while循环。

break语句用来终止循环语句，即循环条件没有False条件或者序列还没被完全递归完，也会停止执行循环语句。

break语句用在while和for循环中。

如果您使用嵌套循环，break语句将停止执行最深层的循环，并开始执行下一行代码。

Python语言 break 语句语法：
```
break
```
流程图：
实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
for letter in 'Python':     # 第一个实例
   if letter == 'h':
      break
   print '当前字母 :', letter
  
var = 10                    # 第二个实例
while var > 0:              
   print '当前变量值 :', var
   var = var -1
   if var == 5:   # 当变量 var 等于 5 时退出循环
      break
 
print "Good bye!"
```
以上实例执行结果：
```
当前字母 : P
当前字母 : y
当前字母 : t
当前变量值 : 10
当前变量值 : 9
当前变量值 : 8
当前变量值 : 7
当前变量值 : 6
Good bye!
```

## 十四、Python continue 语句

Python continue 语句跳出本次循环，而break跳出整个循环。

continue 语句用来告诉Python跳过当前循环的剩余语句，然后继续进行下一轮循环。

continue语句用在while和for循环中。

Python 语言 continue 语句语法格式如下：
```
continue
```
流程图：
实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
for letter in 'Python':     # 第一个实例
   if letter == 'h':
      continue
   print '当前字母 :', letter
 
var = 10                    # 第二个实例
while var > 0:              
   var = var -1
   if var == 5:
      continue
   print '当前变量值 :', var
print "Good bye!"
```
以上实例执行结果：
```
当前字母 : P
当前字母 : y
当前字母 : t
当前字母 : o
当前字母 : n
当前变量值 : 9
当前变量值 : 8
当前变量值 : 7
当前变量值 : 6
当前变量值 : 4
当前变量值 : 3
当前变量值 : 2
当前变量值 : 1
当前变量值 : 0
Good bye!
```

## 十五、Python pass 语句

Python pass 是空语句，是为了保持程序结构的完整性。

pass 不做任何事情，一般用做占位语句。

Python 语言 pass 语句语法格式如下：
```
pass
```
测试实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*- 
 
# 输出 Python 的每个字母
for letter in 'Python':
   if letter == 'h':
      pass
      print '这是 pass 块'
   print '当前字母 :', letter
 
print "Good bye!"
```

以上实例执行结果：
```
当前字母 : P
当前字母 : y
当前字母 : t
这是 pass 块
当前字母 : h
当前字母 : o
当前字母 : n
Good bye!
```

## 十六、Python Number(数字)

Python Number 数据类型用于存储数值。

数据类型是不允许改变的,这就意味着如果改变 Number 数据类型的值，将重新分配内存空间。

以下实例在变量赋值时 Number 对象将被创建：
```
var1 = 1
var2 = 10
```
您也可以使用del语句删除一些 Number 对象引用。

del语句的语法是：
```
del var1[,var2[,var3[....,varN]]]]
```
您可以通过使用del语句删除单个或多个对象，例如：
```
del var
del var_a, var_b
``
Python 支持四种不同的数值类型：
```
```
1)整型(Int) - 通常被称为是整型或整数，是正或负整数，不带小数点。

2)长整型(long integers) - 无限大小的整数，整数最后是一个大写或小写的L。

3)浮点型(floating point real values) - 浮点型由整数部分与小数部分组成，浮点型也可以使用科学计数法表示（2.5e2 = 2.5 x 102 = 250）

4)复数(complex numbers) - 复数由实数部分和虚数部分构成，可以用a + bj,或者complex(a,b)表示， 复数的实部a和虚部b都是浮点型。
```
```
int         long                   float         complex
10        51924361L                0.0            3.14j
100       -0x19323L                15.20          45.j
-786      0122L                    -21.9          9.322e-36j
080       0xDEFABCECBDAECBFBAEl    32.3+e18       .876j
-0490     535633629843L            -90.           -.6545+0J
-0x260    -052318172735L           -32.54e100     3e+26J
0x69      -4721885298529L          70.2-E12       4.53e-7j
```
```
1)长整型也可以使用小写"L"，但是还是建议您使用大写"L"，避免与数字"1"混淆。Python使用"L"来显示长整型。

2)Python还支持复数，复数由实数部分和虚数部分构成，可以用a + bj,或者complex(a,b)表示， 复数的实部a和虚部b都是浮点型
```

### Python Number 类型转换
```
int(x [,base ])         将x转换为一个整数  
long(x [,base ])        将x转换为一个长整数  
float(x )               将x转换到一个浮点数  
complex(real [,imag ])  创建一个复数  
str(x )                 将对象 x 转换为字符串  
repr(x )                将对象 x 转换为表达式字符串  
eval(str )              用来计算在字符串中的有效Python表达式,并返回一个对象  
tuple(s )               将序列 s 转换为一个元组  
list(s )                将序列 s 转换为一个列表  
chr(x )                 将一个整数转换为一个字符  
unichr(x )              将一个整数转换为Unicode字符  
ord(x )                 将一个字符转换为它的整数值  
hex(x )                 将一个整数转换为一个十六进制字符串  
oct(x )                 将一个整数转换为一个八进制字符串  
```
### Python math 模块、cmath 模块
Python 中数学运算常用的函数基本都在 math 模块、cmath 模块中。

Python math 模块提供了许多对浮点数的数学运算函数。

Python cmath 模块包含了一些用于复数运算的函数。

cmath 模块的函数跟 math 模块函数基本一致，区别是 cmath 模块运算的是复数，math 模块运算的是数学运算。

要使用 math 或 cmath 函数必须先导入：
```
import math
```
查看 math 查看包中的内容:
```
>>> import math
>>> dir(math)
['__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'acos', 'acosh', 'asin', 'asinh', 'atan', 'atan2', 'atanh', 'ceil', 'copysign', 'cos', 'cosh', 'degrees', 'e', 'erf', 'erfc', 'exp', 'expm1', 'fabs', 'factorial', 'floor', 'fmod', 'frexp', 'fsum', 'gamma', 'gcd', 'hypot', 'inf', 'isclose', 'isfinite', 'isinf', 'isnan', 'ldexp', 'lgamma', 'log', 'log10', 'log1p', 'log2', 'modf', 'nan', 'pi', 'pow', 'radians', 'sin', 'sinh', 'sqrt', 'tan', 'tanh', 'tau', 'trunc']
>>>
```
下文会介绍各个函数的具体应用。

查看 cmath 查看包中的内容
```
>>> import cmath
>>> dir(cmath)
['__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'acos', 'acosh', 'asin', 'asinh', 'atan', 'atanh', 'cos', 'cosh', 'e', 'exp', 'inf', 'infj', 'isclose', 'isfinite', 'isinf', 'isnan', 'log', 'log10', 'nan', 'nanj', 'phase', 'pi', 'polar', 'rect', 'sin', 'sinh', 'sqrt', 'tan', 'tanh', 'tau']
>>>
```
实例
```
>>> import cmath
>>> cmath.sqrt(-1)
1j
>>> cmath.sqrt(9)
(3+0j)
>>> cmath.sin(1)
(0.8414709848078965+0j)
>>> cmath.log10(100)
(2+0j)
>>>
```
### Python数学函数
```
函数               返回值 ( 描述 )
abs(x)            返回数字的绝对值，如abs(-10) 返回 10
ceil(x)           返回数字的上入整数，如math.ceil(4.1) 返回 5
cmp(x, y)         如果 x < y 返回 -1, 如果 x == y 返回 0, 如果 x > y 返回 1
exp(x)            返回e的x次幂(ex),如math.exp(1) 返回2.718281828459045
fabs(x)           返回数字的绝对值，如math.fabs(-10) 返回10.0
floor(x)          返回数字的下舍整数，如math.floor(4.9)返回 4
log(x)            如math.log(math.e)返回1.0,math.log(100,10)返回2.0
log10(x)          返回以10为基数的x的对数，如math.log10(100)返回 2.0
max(x1, x2,...)   返回给定参数的最大值，参数可以为序列。
min(x1, x2,...)   返回给定参数的最小值，参数可以为序列。
modf(x)           返回x的整数部分与小数部分，两部分的数值符号与x相同，整数部分以浮点型表示。
pow(x, y)         x**y 运算后的值。
round(x [,n])     返回浮点数x的四舍五入值，如给出n值，则代表舍入到小数点后的位数。
sqrt(x)           返回数字x的平方根
```

### Python随机数函数

随机数可以用于数学，游戏，安全等领域中，还经常被嵌入到算法中，用以提高算法效率，并提高程序的安全性。

Python包含以下常用随机数函数：
```
函数                                                            描述
choice(seq)                            从序列的元素中随机挑选一个元素，比如random.choice(range(10))，从0到9中随机挑选一个整数。
randrange ([start,] stop [,step])      从指定范围内，按指定基数递增的集合中获取一个随机数，基数默认值为 1
random()                               随机生成下一个实数，它在[0,1)范围内。
seed([x])                              改变随机数生成器的种子seed。如果你不了解其原理，你不必特别去设定seed，Python会帮你选择seed。
shuffle(lst)                           将序列的所有元素随机排序
uniform(x, y)                          随机生成下一个实数，它在[x,y]范围内。
```

### Python三角函数

Python包括以下三角函数：
```
函数                 描述
acos(x)       返回x的反余弦弧度值。
asin(x)       返回x的反正弦弧度值。
atan(x)       返回x的反正切弧度值。
atan2(y, x)   返回给定的 X 及 Y 坐标值的反正切值。
cos(x)        返回x的弧度的余弦值。
hypot(x, y)   返回欧几里德范数 sqrt(x*x + y*y)。
sin(x)        返回的x弧度的正弦值。
tan(x)        返回x弧度的正切值。
degrees(x)    将弧度转换为角度,如degrees(math.pi/2) ， 返回90.0
radians(x)    将角度转换为弧度
```

### Python数学常量
```
常量                   描述
pi         数学常量 pi（圆周率，一般以π来表示）
e          数学常量 e，e即自然常数（自然常数）。
```

## 十七、Python 字符串
字符串是 Python 中最常用的数据类型。我们可以使用引号('或")来创建字符串。

创建字符串很简单，只要为变量分配一个值即可。例如：
```
var1 = 'Hello World!'
var2 = "Python Runoob"
```

### Python 访问字符串中的值
Python 不支持单字符类型，单字符在 Python 中也是作为一个字符串使用。

Python 访问子字符串，可以使用方括号来截取字符串，如下实例：
```
#!/usr/bin/python
 
var1 = 'Hello World!'
var2 = "Python Runoob"
 
print "var1[0]: ", var1[0]
print "var2[1:5]: ", var2[1:5]
```
以上实例执行结果：
```
var1[0]:  H
var2[1:5]:  ytho
```

### Python 字符串连接
我们可以对字符串进行截取并与其他字符串进行连接，如下实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
var1 = 'Hello World!'
 
print "输出 :- ", var1[:6] + 'Runoob!'
```
以上实例执行结果：
```
输出 :-  Hello Runoob!
```

### Python 转义字符
在需要在字符中使用特殊字符时，python 用反斜杠 \ 转义字符。如下表：
```
转义字符         描述
\(在行尾时)      续行符
\\              反斜杠符号
\'              单引号
\"              双引号
\a              响铃
\b              退格(Backspace)
\e              转义
\000            空
\n              换行
\v              纵向制表符
\t              横向制表符
\r              回车
\f              换页
\oyy            八进制数，y 代表 0~7 的字符，例如：\012            代表换行。
\xyy            十六进制数，以 \x 开头，yy代表的字符，例如：\x0a代表换行
\other          其它的字符以普通格式输出
```

### Python字符串运算符
下表实例变量 a 值为字符串 "Hello"，b 变量值为 "Python"：
```
操作符       描述                                                                     实例
+         字符串连接                                                               >>>a + b   'HelloPython'
*         重复输出字符串                                                           >>>a * 2   'HelloHello'
[]        通过索引获取字符串中字符                                                  >>>a[1]    'e'
[ : ]     截取字符串中的一部分                                                      >>>a[1:4]  'ell'
in        成员运算符 - 如果字符串中包含给定的字符返回 True                            >>>"H" in a True
not in    成员运算符 - 如果字符串中不包含给定的字符返回 True                           >>>"M" not in a True
r/R       原始字符串 - 原始字符串：所有的字符串都是直接按照字面的意思来使用，没有转义特殊或不能打印的字符。 原始字符串除在字符串的第一个引号前加上字母"r"（可以大小写）以外，与普通字符串有着几乎完全相同的语法。	  >>>print r'\n'  \n  >>> print R'\n' \n
%         格式字符串                                                                请看下一章节
```
实例：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
a = "Hello"
b = "Python"
 
print "a + b 输出结果：", a + b 
print "a * 2 输出结果：", a * 2 
print "a[1] 输出结果：", a[1] 
print "a[1:4] 输出结果：", a[1:4] 
 
if( "H" in a) :
    print "H 在变量 a 中" 
else :
    print "H 不在变量 a 中" 
 
if( "M" not in a) :
    print "M 不在变量 a 中" 
else :
    print "M 在变量 a 中"
 
print r'\n'
print R'\n'
```
以上程序执行结果为：
```
a + b 输出结果： HelloPython
a * 2 输出结果： HelloHello
a[1] 输出结果： e
a[1:4] 输出结果： ell
H 在变量 a 中
M 不在变量 a 中
\n
\n
```

### Python 字符串格式化
Python 支持格式化字符串的输出 。尽管这样可能会用到非常复杂的表达式，但最基本的用法是将一个值插入到一个有字符串格式符 %s 的字符串中。

在 Python 中，字符串格式化使用与 C 中 sprintf 函数一样的语法。

如下实例：
```
#!/usr/bin/python

print "My name is %s and weight is %d kg!" % ('Zara', 21) 
```
以上实例输出结果：
```
My name is Zara and weight is 21 kg!
```
python 字符串格式化符号:
```
   符   号    描述
      %c    格式化字符及其ASCII码
      %s    格式化字符串
      %d    格式化整数
      %u    格式化无符号整型
      %o    格式化无符号八进制数
      %x    格式化无符号十六进制数
      %X    格式化无符号十六进制数（大写）
      %f    格式化浮点数字，可指定小数点后的精度
      %e    用科学计数法格式化浮点数
      %E    作用同%e，用科学计数法格式化浮点数
      %g    %f和%e的简写
      %G    %F 和 %E 的简写
      %p    用十六进制数格式化变量的地址
```
格式化操作符辅助指令:
```
符号        功能
*         定义宽度或者小数点精度
-         用做左对齐
+         在正数前面显示加号( + )
<sp>      在正数前面显示空格
#         在八进制数前面显示零('0')，在十六进制前面显示'0x'或者'0X'(取决于用的是'x'还是'X')
0         显示的数字前面填充'0'而不是默认的空格
%         '%%'输出一个单一的'%'
(var)     映射变量(字典参数)
m.n.      m 是显示的最小总宽度,n 是小数点后的位数(如果可用的话)

Python2.6 开始，新增了一种格式化字符串的函数 str.format()，它增强了字符串格式化的功能。
```

### Python 三引号
Python 中三引号可以将复杂的字符串进行赋值。

Python 三引号允许一个字符串跨多行，字符串中可以包含换行符、制表符以及其他特殊字符。

三引号的语法是一对连续的单引号或者双引号（通常都是成对的用）。
```
>>> hi = '''hi 
there'''
>>> hi   # repr()
'hi\nthere'
>>> print hi  # str()
hi 
there  
```
三引号让程序员从引号和特殊字符串的泥潭里面解脱出来，自始至终保持一小块字符串的格式是所谓的WYSIWYG（所见即所得）格式的。

一个典型的用例是，当你需要一块HTML或者SQL时，这时当用三引号标记，使用传统的转义字符体系将十分费神。
```
errHTML = '''
<HTML><HEAD><TITLE>
Friends CGI Demo</TITLE></HEAD>
<BODY><H3>ERROR</H3>
<B>%s</B><P>
<FORM><INPUT TYPE=button VALUE=Back
ONCLICK="window.history.back()"></FORM>
</BODY></HTML>
'''
cursor.execute('''
CREATE TABLE users (  
login VARCHAR(8), 
uid INTEGER,
prid INTEGER)
''')
```
### Unicode 字符串
Python 中定义一个 Unicode 字符串和定义一个普通字符串一样简单：
```
>>> u'Hello World !'
u'Hello World !'
```
引号前小写的"u"表示这里创建的是一个 Unicode 字符串。如果你想加入一个特殊字符，可以使用 Python 的 Unicode-Escape 编码。如下例所示：
```
>>> u'Hello\u0020World !'
u'Hello World !'
```
被替换的 \u0020 标识表示在给定位置插入编码值为 0x0020 的 Unicode 字符（空格符）。

### python的字符串内建函数
字符串方法是从python1.6到2.0慢慢加进来的——它们也被加到了Jython中。

这些方法实现了string模块的大部分方法，如下表所示列出了目前字符串内建支持的方法，所有的方法都包含了对Unicode的支持，有一些甚至是专门用于Unicode的。

## 十八、Python 列表(List)
序列是Python中最基本的数据结构。序列中的每个元素都分配一个数字 - 它的位置，或索引，第一个索引是0，第二个索引是1，依此类推。

Python有6个序列的内置类型，但最常见的是列表和元组。

序列都可以进行的操作包括索引，切片，加，乘，检查成员。

此外，Python已经内置确定序列的长度以及确定最大和最小的元素的方法。

列表是最常用的Python数据类型，它可以作为一个方括号内的逗号分隔值出现。

列表的数据项不需要具有相同的类型

创建一个列表，只要把逗号分隔的不同的数据项使用方括号括起来即可。如下所示：
```
list1 = ['physics', 'chemistry', 1997, 2000]
list2 = [1, 2, 3, 4, 5 ]
list3 = ["a", "b", "c", "d"]
```
与字符串的索引一样，列表索引从0开始。列表可以进行截取、组合等。

### 访问列表中的值
使用下标索引来访问列表中的值，同样你也可以使用方括号的形式截取字符，如下所示：
```
#!/usr/bin/python
 
list1 = ['physics', 'chemistry', 1997, 2000]
list2 = [1, 2, 3, 4, 5, 6, 7 ]
 
print "list1[0]: ", list1[0]
print "list2[1:5]: ", list2[1:5]
```
以上实例输出结果：
```
list1[0]:  physics
list2[1:5]:  [2, 3, 4, 5]
```

### 更新列表
你可以对列表的数据项进行修改或更新，你也可以使用append()方法来添加列表项，如下所示：
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
list = []          ## 空列表
list.append('Google')   ## 使用 append() 添加元素
list.append('Runoob')
print list
```
注意：我们会在接下来的章节讨论append()方法的使用

以上实例输出结果：
```
['Google', 'Runoob']
```

### 删除列表元素
可以使用 del 语句来删除列表的元素，如下实例：
```
#!/usr/bin/python
 
list1 = ['physics', 'chemistry', 1997, 2000]
 
print list1
del list1[2]
print "After deleting value at index 2 : "
print list1
```
以上实例输出结果：
```
['physics', 'chemistry', 1997, 2000]
After deleting value at index 2 :
['physics', 'chemistry', 2000]
```
注意：我们会在接下来的章节讨论remove()方法的使用

### Python列表脚本操作符
列表对 + 和 * 的操作符与字符串相似。+ 号用于组合列表，* 号用于重复列表。

如下所示：
```
Python 表达式                   结果                              描述
len([1, 2, 3])                  3                                长度
[1, 2, 3] + [4, 5, 6]           [1, 2, 3, 4, 5, 6]               组合
['Hi!'] * 4                     ['Hi!', 'Hi!', 'Hi!', 'Hi!']     重复
3 in [1, 2, 3]                  True                             元素是否存在于列表中
for x in [1, 2, 3]: print x,    1 2 3                            迭代
```

### Python列表截取
Python 的列表截取实例如下：
```
>>>L = ['Google', 'Runoob', 'Taobao']
>>> L[2]
'Taobao'
>>> L[-2]
'Runoob'
>>> L[1:]
['Runoob', 'Taobao']
>>>
```
描述：
```
Python 表达式     结果                     描述
L[2]             'Taobao'                 读取列表中第三个元素
L[-2]            'Runoob'                 读取列表中倒数第二个元素
L[1:]            ['Runoob', 'Taobao']     从第二个元素开始截取列表
```

### Python列表函数&方法
Python包含以下函数:
```
序号              函数
1           cmp(list1, list2)
            比较两个列表的元素
2           len(list)
            列表元素个数
3           max(list)
            返回列表元素最大值
4           min(list)
            返回列表元素最小值
5           list(seq)
            将元组转换为列表
```
Python包含以下方法:
```
序号            方法
1               list.append(obj)
                在列表末尾添加新的对象
2               list.count(obj)
                统计某个元素在列表中出现的次数
3               list.extend(seq)
                在列表末尾一次性追加另一个序列中的多个值（用新列表扩展原来的列表）
4               list.index(obj)
                从列表中找出某个值第一个匹配项的索引位置
5               list.insert(index, obj)
                将对象插入列表
6               list.pop([index=-1])
                移除列表中的一个元素（默认最后一个元素），并且返回该元素的值
7               list.remove(obj)
                移除列表中某个值的第一个匹配项
8               list.reverse()
                反向列表中元素
9               list.sort(cmp=None, key=None, reverse=False)
                对原列表进行排序
```

## 十九、Python 元组
Python的元组与列表类似，不同之处在于元组的元素不能修改。

元组使用小括号，列表使用方括号。

元组创建很简单，只需要在括号中添加元素，并使用逗号隔开即可。

如下实例：
```
tup1 = ('physics', 'chemistry', 1997, 2000)
tup2 = (1, 2, 3, 4, 5 )
tup3 = "a", "b", "c", "d"
```
创建空元组
```
tup1 = ()
```
元组中只包含一个元素时，需要在元素后面添加逗号
```
tup1 = (50,)
```
元组与字符串类似，下标索引从0开始，可以进行截取，组合等。

### 访问元组
元组可以使用下标索引来访问元组中的值，如下实例:
```
#!/usr/bin/python
 
tup1 = ('physics', 'chemistry', 1997, 2000)
tup2 = (1, 2, 3, 4, 5, 6, 7 )
 
print "tup1[0]: ", tup1[0]
print "tup2[1:5]: ", tup2[1:5]
```
以上实例输出结果：
```
tup1[0]:  physics
tup2[1:5]:  (2, 3, 4, 5)
```

### 修改元组
元组中的元素值是不允许修改的，但我们可以对元组进行连接组合，如下实例:
```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
tup1 = (12, 34.56)
tup2 = ('abc', 'xyz')
 
# 以下修改元组元素操作是非法的。
# tup1[0] = 100
 
# 创建一个新的元组
tup3 = tup1 + tup2
print tup3
```
以上实例输出结果：
```
(12, 34.56, 'abc', 'xyz')
```

### 删除元组
元组中的元素值是不允许删除的，但我们可以使用del语句来删除整个元组，如下实例:
```
#!/usr/bin/python
 
tup = ('physics', 'chemistry', 1997, 2000)
 
print tup
del tup
print "After deleting tup : "
print tup
```
以上实例元组被删除后，输出变量会有异常信息，输出如下所示：
```
('physics', 'chemistry', 1997, 2000)
After deleting tup :
Traceback (most recent call last):
  File "test.py", line 9, in <module>
    print tup
NameError: name 'tup' is not defined
```

### 元组运算符
与字符串一样，元组之间可以使用 + 号和 * 号进行运算。这就意味着他们可以组合和复制，运算后会生成一个新的元组。
```
Python 表达式                      结果                            描述
len((1, 2, 3))                     3                              计算元素个数
(1, 2, 3) + (4, 5, 6)              (1, 2, 3, 4, 5, 6)             连接
('Hi!',) * 4                       ('Hi!', 'Hi!', 'Hi!', 'Hi!')   复制
3 in (1, 2, 3)                     True                           元素是否存在
for x in (1, 2, 3): print x,       1 2 3                          迭代
```

### 元组索引，截取
 























































<br>
<hr>

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
