数据导出为excel
data.to_excel("wenjianming")




看完这章之后对这个 from…import * 语句与 import 区别很是疑惑从别处看完解释理解如下。

首先你要了解 import 与 from…import 的区别。

import 模块：导入一个模块；注：相当于导入的是一个文件夹，是个相对路径。
from…import：导入了一个模块中的一个函数；注：相当于导入的是一个文件夹中的文件，是个绝对路径。
所以使用上的的区别是当引用文件时是:

import   //模块.函数

from…import  // 直接使用函数名使用就可以了
所以

from…import *：是把一个模块中所有函数都导入进来; 注：相当于：相当于导入的是一个文件夹中所有文件，所有函数都是绝对路径。

结论：

from…import *语句与import区别在于：

import 导入模块，每次使用模块中的函数都要是定是哪个模块。

from…import * 导入模块，每次使用模块中的函数，直接使用函数就可以了；注因为已经知道该函数是那个模块中的了。


args={'a':1,'b':2}

func(**args)

等价于函数调用 func(a=1,b=2)
