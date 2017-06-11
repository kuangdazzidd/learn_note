安装ReText软件
###############


**1.安装**
    直接通过apt安装(过程中会安装python3和其他依赖包)

   >>> sudo apt-get install retext

**2.扩展**    
    ReText支持rst的扩展语法，例如mathjax和codehilite

a. 安装数学库
    >>> sudo apt-get install libjs-mathjax
b. 打开ReText的设置界面，在Markdown extensions框里添加字段：mathjax
c. 重启ReText之后，输入公式，在预览中不显示。此时，通过 编辑(Edit) –> 使用WebKit渲染



-----------------------------------------

**参考网址**

1. http://www.th7.cn/system/lin/201610/182748.shtml
