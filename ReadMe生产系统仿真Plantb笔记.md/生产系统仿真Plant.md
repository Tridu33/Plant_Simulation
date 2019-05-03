# 正确的学习方法是跑正确的例程
```

Plant13软件安装根目录:.
├─3D # 模型库
│  ├─jt-graphics
│  └─s3d-graphics
│      ├─BuffersAndSorters
│      ├─EOM
│      ├─Transporters
│      └─Workers
├─BasicObjects# 模型库
├─C-Interface  #C语言接口使用教程样例
├─Clipart #图标库
│  ├─Chart
│  ├─Misc
│  ├─Movable
│  ├─Schulung
│  └─Training
├─Examples # 各种使用教程样例，超级有用!
│  ├─3D
│  └─Demo#用到什么学什么，看会直接用，模仿做一个
│      └─German
├─Help
│  └─Videos# 视频有点用，就是chm文字版很垃圾，
├─Languages
│  ├─CHS
│  ├─DEU
│  ├─HUN
│  ├─JPN
│  └─RUS
├─Libraries#类库，可以加载管理工程类库
│  ├─Standard
│  │  ├─Free
│  │  └─Licensed
│  │      ├─Assembly
│  │      ├─Process Designer Interface
│  │      ├─Shop
│  │      └─Value Stream Mapping
│  └─Tools
├─License Server Binaries
├─OPC Core Components
├─Teamcenter
│  └─Saxon MPL notices
├─Templates    # Method代码模板------用到相应的代码，复制进去Method改吧改吧就完事儿了
│  ├─English
│  │  ├─Broker
│  │  ├─Code Snippets
│  │  ├─Dialog
│  │  ├─Entrance Control
│  │  ├─Exit Control
│  │  ├─Exporter
│  │  ├─Importer
│  │  ├─Interaction
│  │  ├─Processing Time
│  │  └─Sensor Control
│  └─German#不看
│      ├─Ausgangssteuerungen
│      ├─Bearbeitungszeiten
│      ├─Broker
│      ├─Code-Schnipsel
│      ├─Dialog
│      ├─Eingangssteuerungen
│      ├─Exporter
│      ├─Importer
│      ├─Interaktion
│      └─Sensorsteuerungen
├─Tutorial#  入门必看，先看视频！
├─WIBU Driver
├─wrltojt
└─xt2jt
    └─Schema

```


*.jt,*.s3d
## Examples学习笔记！！！！！！
![英文版HTML用Chrome打开](_v_images/英文版html用ch_1556851626_23537.png)
翻译之后的结果：

![help中文版用法](_v_images/help中文版用法_1556851571_29147.png)
闲着有空，你还可以把它翻译成中文chm发布。







# 技巧

扩展启动选项 E:/chm_files/Plant/CHM/id74918.html

F1：打开帮助文档

  

F2：重命名

  

F3：搜索。可搜索根目录下所有对象名、源代码、变量等

  

F4：重命名当前Frame

  

F5：继续运行由于debug或断点中断的程序

  

F6：查看统计信息

  

F8：查看属性

  

F9：添加类断点

  

F10：调试时逐句运行

  

F11：查看当前对象自定义属性

  

F12：查看当前对象控制方法

  

Shift + F9：仅对当前方法添加断点

  

Ctrl + Space：代码自动补全

  

Alt + C：自动缩进

  

Ctrl + Shift+ Q：注释当前语句

  

Ctrl + T：旋转图标

  

  

  

多按下列按钮看着学习：

F8 属性 F4重命名 shift F1对象属性

  

reset Init Endsim

  

# **匿名表达式**

  

•@--表示触发物流对象control的MU

  

• basis--表示 class library

  

• current--表示method所在的frame

  

• ?---表示调用method的实体（物流对象或method)

  

  

Self 执行Method本身

  

Current 执行Method所在Frame

  

Location 正执行的Method所在 Frame，指代正在处理他的物流对象，<Object， >.Location表示正在处理他的物流对象，@.Location返回MU所在物流对象绝对路径

  

~是Location缩写

  

Root 模型顶级Frame，第四章

  

!\[语句是错的\](\_v\_images/语句是错的\_1555672447\_25759.png)

# Simtalk 20

  

/*

param action: string

  

switch action

case "Open"

\-\- TODO: add code for the "Open" action here

\-\- E.g. ?.setCaption("TextBox", "Test")

\-\- E.g. ?.setCheckBox("CheckBox", true)

case "Apply"

\-\- TODO: add code for the "Apply" action here

\-\- E.g. print ?.getValue("TextBox")

\-\- E.g. print ?.GetCheckBox("CheckBox")

case "Close"

\-\- TODO: add code for the "Close" action here

end

(action : string)

*/

  

  

  

www.plantsim.top/simtalk-编程技巧和建议/

### 善用debug

  

在程序运行中，有时会出现意外的情况，但是并不会打断程序执行，如move语句执行失败，程序会继续运行。当出现错误时，问题的根源已难以追溯。debug语句就可以在问题发生时，及时中断程序。下面列举一些debug的适用范围。

  

\- move：move失败错误比较隐蔽，经常会在很长时间之后发生错误。建议使用以下方法：

  

if not move()

  

debug

  

end

  

\- find：如果在一个表中使用find查找一个值，而这个值应该出现在表中。那么如果出现错误，并没有这个值，那么find语句并不会报错，而是返回初始游标位置，找到错误的值。建议使用以下方法：

  

if TableFile.find({*,*}..{*,*},aValue)

else

  

debug

  

end

  

\- if：可以在if语句未涵盖到的部分添加debug，以检验当前程序逻辑。例如：

  

if condition1

  

elseif condition2

  

else

  

debug

  

end



[5] 周金平 
SimTalk 2.0的变化：

Ø  抛弃is……do……end的结构；

Ø  定义变量的方法不同于以前的在is后面添加类似于m：integer，改为var m：integer；

Ø  引用method的语句修改为param n1,n2:real->real（示例为传递两个实数型变量），在低版本中为（n1,n2:real）:real;

Ø  每行结尾不再需要分号。

其他的变化在日后的使用过程，再继续与大家分享。

Tips：

Ø  一些常见的控制结构可以直接在菜单栏“编辑-控制结构”中选择，修改相应条件即可；

Ø  修改某些object的属性，可以选中object，按“F8”键，查看object具有哪些属性；


Ø Tablefile[column，row]，第一个数为列，第二个数为行。

SimTalk 2.0 encompasses:

A line-controlled syntax: You no longer need to type a semicolon (Smiley Wink at the end of each statement. Instead, you can simply enter a single statement into a line. As you still might want to be able to split a statement and distribute it over several lines, the interpreter needs to automatically determine if the statement is incomplete and is being continued in the next line. In addition, you can enter a semicolon to add another statement in the same line.

 

A simplified body syntax: In SimTalk 1.0 the source code requires the keywords is do end. SimTalk 2.0 does not need these keywords. In SimTalk 2.0 you will declare parameters using the keyword param, local variables using the keyword var, and the return value using the keyword -> (hyphen plus right angle bracket).

 

Improved referencing of methods and global variables: In SimTalk 1.0 Methods and Variables are referenced with the reference operator. In SimTalk 2.0 you reference Methods and Variables with a leading & operator, for example: var oSmiley Surprisedbject := &Method.

 

New div/mod operator: In SimTalk 1.0 the // operator represents an integer division and the \\ operator represents an integer modulo operation. In SimTalk 2.0 the keyword div represents an integer division and the keyword mod represents an integer modulo operation.

 

Simplified control flow statements: The control structures which you can insert with the command Insert Control Structure into your source code, reflect this. You can now enter control flow statements using the simplified syntax:

if-else-end instead of if-then-else-end
for-next instead of for-to-loop-next
switch-case-end instead of inspect-when-then-end
while-end instead of while-loop-end
The keyword then in if-statements is optionally allowed.
The keyword loop in loops is optionally allowed.
A changed about equal operator. You now have to use:

~= instead of ==, compare Tolerance for about equal (~=) comparison.
<~= instead of <==
>~= instead of >==
New operators for adding, subtracting, or multiplying a value:

x += y is short for x := x + y
x -= y is short for x := x - y
x *= y is short for x := x * y
An improved list and table syntax: You now only enter list ranges using curly brackets {}. The optional 1.0 syntax using a grave accent `[] is no longer available. (The bracket operator of an empty cell, compare [,] (read the contents of a cell), now returns VOID. In SimTalk 1.0 an empty cell returned the default value of the cell, which usually was 0.)

 

You can read out an element of a one-dimensional list with the bracket operator []. This works for Stacks and Queues as well. You can read and remove an element from a CardFile with the new built-in method remove.

*  When reading the contents of a cell of a CardFile with the bracket operator in SimTalk 1.0, the contents of the designated cell was read and removed. The remaining cells moved up by one position.
When assigning a value to the designated cell with the bracket operator to a CardFile in SimTalk 1.0, this value was inserted into the cell and the existing cells moved down by one position. 

*  When reading the contents of a cell with the bracket operator in SimTalk 2.0, the contents of the designated cell will be read, but will remain in the StackFile, QueueFile, and the CardFile.
When assigning a value to the designated cell with the bracket operator to a CardFile in SimTalk 2.0, this value will just overwrite the contents of the existing cell. This way a CardFile will behave the same way as a TableFile with one column.

________________________________________
--------------------- 


作者：Ronnie666 


来源：CSDN 

# 全局变量
you can access an object **Variable**, which is located in an arbitrary network (object Frame).

For instance:
```

 root.Frame.variable := 10;  
 local n := root.Frame.variable;  
 print n;

```

Note that **root** is your simulation frame, which containes the **Eventcontroller**.

Regards,

Peter







原文：

https://blog.csdn.net/luolandeygy/article/details/70464186 


版权声明：本文为博主原创文章，转载请附上博文链接！


博客

https://blog.csdn.net/cqzhaodaxio/article/details/84854854

微信

学习之路

网站
www.plantsim.top/page/2/
论坛

知乎
https://zhuanlan.zhihu.com/p/30516262

周金平书本

新版本simtalk

遗传算法

Plant Simulation 是面向对象的三维离散事件仿真软件，使您能够快速、直观地构建逼真的物流模型。 您还可以使用高级统计工具执行复杂的生产分析。以下介绍该软件的一些常用命令。

1\. clearConsole: 清空控制台内容。

2.表操作：

is orderlist : table\[string,real\]; do orderlist.create;
   orderlist\[1,1\] := "cans";
   orderlist\[2,1\] := 3000.0;
   orderlist.forget; -- 删除表
   orderlist.create(4); \-\- 重现创建一个4行的表end; 

 3.  When-Then-Else

例1:  is
do @.color := when ?.entranceLocked then "red" else "green"; end;  
例2:  (n : integer) : integer \-\- computes the faculty of n is
do
   return when n > 1 then n * self.execute(n - 1) else 1; end;  
例3:  Method(x, y \+ (when dy > 0 then y+dy else 100));











































JT文件格式是Siemens（[西门子](https://www.baidu.com/s?wd=%E8%A5%BF%E9%97%A8%E5%AD%90&tn=SE_PcZhidaonwhc_ngpagmjz&rsv_dl=gh_pc_zhidao)） PLM Software开发的轻型3D模型文件格式，可以使用JT2Go软件打开。  
　　Siemens（[西门子](https://www.baidu.com/s?wd=%E8%A5%BF%E9%97%A8%E5%AD%90&tn=SE_PcZhidaonwhc_ngpagmjz&rsv_dl=gh_pc_zhidao)） PLM Software是全球领先的产品生命周期管理（PLM）软件与服务提供商。JT文件格式设计为一个开放、高效率的、紧凑，持久性存储的产品数据格式；用于产品可视化、协作和CAD数据共享。JT文件格式包括多方面的数据，以及对曲面边界的精准表示，产品和制造业的相关信息，元数据信息，这些信息都可以CAD文件系统导出并可以被产品数据管理(PDM) 系统导入到软件里。


# SimTalk

　　[http://www.itpub.net/viewthread.php?tid=1287272&hinghlight=SinTalk](http://www.itpub.net/viewthread.php?tid=1287272&hinghlight=SinTalk)
　　

http://www.itpub.net/viewthread.php?tid=1452011&extra=page%3D1&frombbs=1

# NP-Complete
Nondeterministic Polynomial Complete Problem


[http://www.itpub.net/thread-1287272-1-1.html](http://www.itpub.net/thread-1287272-1-1.html)





# 备忘

D:\Program Files\Siemens\Tecnomatix Plant Simulation 13

### 利用高效语句

正常的仿真运行对程序效率要求不高，但是当仿真时间较长，需要进行大规模实验的时候，运行效率的问题变得尤为重要。这里列举一些高效的语句供参考。

-   使用switch…case…end (inspect…when…end) 代替 if…elseif…end （条件较多时）
-   使用copyRangeTo / writeRow 等代替循环语句写表，减少表格读取次数。
-   尽量使用局部变量代替全局变量，包括表格。

### 循环语句的终止条件

for循环不涉及该问题，但是while循环和repeat循环极有可能因为终止条件不完善陷入死循环。所以在使用这两种循环时，要注意设置循环次数的限制，添加计数器。例如：

repeat

«loop_statements»  
i+=1

until «exit_condition» or i>1000







www.plantsim.top/simtalk常用函数介绍（四）：数学运算相关函数/


www.plantsim.top/simtalk常用函数介绍（三）：表格操作相关函数/

www.plantsim.top/simtalk常用函数介绍（一）：字符串操作相关函数/


www.plantsim.top/simtalk常用函数介绍（二）：数组操作相关函数/


www.plantsim.top/非整型数值变量使用时需要注意的问题/

# 数据库交互和COM,ActiveX。。。

















# Method 
208
InheritSources Scource Code

**![](_v_images/1553782779_3277.png)**









一般蓝色method不能直接运行，绿色可以。



红 故障
蓝色 暂停
绿色 正常工作
黄色 阻塞
棕色 正常工作准备
灰色 缺乏必要资源而等待
淡蓝 恢复状态

![](_v_images/1553781239_9434.png)




# 
![](_v_images/1553781308_19466.png)











# 开发限制
当您使用C接口链接自己编程的DLL时，此DLL必须编译为64位DLL。

对于ActiveX对象，您需要64位ActiveX控件。

对于ODBC接口，还需要用于ODBC的 64位驱动程序。从Microsoft Office 2010开始，Microsoft为Access，Excel等提供64位ODBC驱动程序。

该OPC接口只能解决OPC服务器的64位版本。


FlowControl VS Exit Strategy属性
133

InterFace层次


### GA

  

  

### Experiments

















































