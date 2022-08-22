# Python 基础

## 什么是 Python

- Python 是一门编程语言。
- Python 是一个很简单的编程语言。
- Python 可以处理除了 c/c++语言之外的几乎所有问题

## 环境配置（重要！）

对于编程新手，你需要一个编辑器和适当的环境，推荐 vscode 这个软件。这可能要耗费你半天的时间，但这是值得的。

首先去[官网下载](https://code.visualstudio.com/)vscode，点击蓝色的大按钮下载。

然后去[官网下载](https://www.python.org/downloads/)Python，（Windows）点击黄色的大图标。

之后的配置大家参考[这篇文章](https://zhuanlan.zhihu.com/p/31417084)

## 起步

起步 Python，建议阅读[“菜鸟教程”网站](https://www.runoob.com/python3/python3-tutorial.html)。

在阅读菜鸟教程时，不需要全懂，只需要阅读个概念，然后上手跟着操作一下即可。建议阅读的篇目如下：

- 基础语法
- 基本数据类型
- 注释
- 运算符（加减乘除，优先级）
- 字符串
- 列表、字典、元组、集合
- 条件控制（重要）
- 循环语句（重要）
- 函数（重要）
- 模块（看个语法）

## 一定要会的

这里列举一些一定要会的概念，然后就可以开始应用了：

- 设变量 `a=1`
- 写加减乘除 `a+b`
- 输出内容 `print(a)`
- 设字符串 `str="hello-world"`
- 设列表 `list=[1,2,3,4,5]`
- 列表里增加一项 `list.append(6)`
- `if` `for` 语句
- 函数 `def func() :`
- 引入库 `import numpy`

## 认识库

库是指别人写好的东西，我们用 Python 大多数是把别人写好的东西拿来用。那么重要的就是要获得别人写的代码，并且按照别人规定的用法使用。这一切的来源在于**读文档**！

## 阅读 numpy,pandas 文档

numpy 是 Python 数据处理中一个重要的库，大家阅读[numpy 文档](https://www.numpy.org.cn/user/quickstart.html)。还是一样，不需要全懂。

pandas 是一个数据表格相关的库，大家阅读[pandas 文档]。读不懂不要紧，留个概念。

## 实践：从 excel 里导入一些文件并作一些操作

大家新建一个 excel 工作表，随便打一些*数字*，如下（随意）：

| 数字 1 | 数字 2 |
| ------ | ------ |
| 1      | 5      |
| 3      | 5      |
| 2      | 5      |
| 67     | 3      |

然后在网上搜索**“Python 读取 excel”**，自己找寻相关内容，读取这张表格里的数字，然后分别求一个方差或者平均数（用 numpy 库的函数）。

这里给[一篇文章](https://zhuanlan.zhihu.com/p/137750174)参考。

至此，你就可以说，你掌握了 Python 基础！
