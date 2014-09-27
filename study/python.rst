Python入门
---------------------

在前章稍微介绍了一下Python的相关知识，为了使读者在组里尽快上手，这里稍微介绍一下Python的安装方式和一些常见的问题。

简介
````````````````````
在介绍如何安装Python之前，这里对Python涉及的一些概念做一个最简单的介绍。

Python
	Python除了指代一门编程语言之外，也常指Python解释器本身。Python解释器是一个可交互式的界面，即时输入Python指令即时看见结果

Module
	Python的模块可以理解为实现编译好的一系列函数。比如Python本身的解释器并不提供圆周率，而Numpy模块提供了此包，如果在解释器中输入下面的指令就可以调用出圆周率
	
	.. code-block:: python
	
		import numpy
		print numpy.pi

Library
	一般来说，Python模块的合集称为Library。比如Matplotlib就是一个著名的用于绘图的库。Library和Module之前的界限并不总是很清晰的，所以在这两个词有时候也被不加区分地使用
	
环境变量(Environment variables)
	环境变量指Python运行中系统的相关设定，比较主要PYTHONPATH，这个环境变量指定了Python运行的时候默认搜索的模块。也就是说如果一个模块没有被安装到此文件夹下，默认情况下Python是无法调用的
	
IDE
	集成化开发环境（Integrated Development Environment）一般集成大量编程所需功能于一身，提供诸如源代码编辑，自动编译和代码调试等功能，为编程提供便利。Python自带名为IDLE（Integrated DeveLopment Environment）的IDE，在初学的时候可以一用。而我们组主要使用的为商业软件\ WingIDE_\。博士生以及在PRG做毕设的硕士生可以找\ `Wim Bogaerts`_\要注册码。

.. _WingIDE: https://wingware.com/
.. _Wim Bogaerts: Wim.Bogaerts@intec.UGent.be

安装
````````````````````
推荐大家通过Enthought Canopy安装。

首先进入Canopy官网，在右上角点击Sign up注册账号，推荐注册的时候选用UGent邮箱。注册成功之后在依次点击Product -> Get Canopy -> For Academics -> Request your license。通过验证之后就可以下载了。安装过程中会有各类窗口弹出，建议对Python不太熟悉的人直接选择默认值。

安装成功之后打开Canopy进入Package Manager即可安装相关的模块和库，包括本文的写作工具Sphinx。

常见问题
``````````````````````