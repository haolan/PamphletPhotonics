开学前准备
-----------------

:Author: Haolan Zhao
:status: Finished
:revision: First Revision 9/5/2014

在这一章将主要介绍一些在实验室常用的软件，可能更多的针对于博士生，未必需要在国内花时间掌握，但是希望至少有个概念，等用到的时候可以再阅读更加有针对性的内容。

Python
~~~~~~~~~~~~~~~~~
Python是一种编程语言，作为基于解释器的脚本语言，Python语言相对来说非常简单，部署起来非常快，因此现在用处很广。

实验室基于Python的软件非常多，仿真软件包括了基于RCWA算法的CAMFR，基于FDTD算法的PyMEEP，对于系统仿真的Caphe，此外还有掩模设计软件Ipkiss和实验室自动测量接口PyMeasure。除了我们组自己开发的软件包之外，我们组也广泛使用Numpy做数值计算，用Matplotlib绘图或者PyQt开发图形化界面。

一般而言在博士或者硕士生活中难免会用到这些软件中的一两个，所以如果在国内有闲暇不妨抽一定的时间稍微了解一下Python相关内容，这里提供一本笔者认为比较好的英文\ python参考书_\。

.. _python参考书: http://www.amazon.com/Beginning-Python-Professional-Edition-Professionals/dp/1590599829

MATLAB 
~~~~~~~~~~~~~~~~~
大名鼎鼎的MATLAB想来我不用过多介绍。实验室里绝大部分的数值计算和数据处理都是用这个软件完成的。虽然我相信大部分人在国内都有使用MATLAB的经验，不过可能对MATLAB代码缺乏系统学习，所以在面对比较大型的仿真程序的时候不能游刃有余地处理。

笔者建议如果有时间的不放首先完成这个\ 网络简明MATLAB教程_\，再辅以此\ MATLAB参考书_\，使用MATLAB的时候肯定会非常有自信。

.. _网络简明MATLAB教程: http://www.matlab-cookbook.com/
.. _MATLAB参考书: http://www.amazon.com/MATLAB-Guide-Desmond-J-Higham/dp/0898715784

LaTeX
~~~~~~~~~~~~~~~~~
LaTeX是一个非所见即所得的文档编写系统，相比起Word，LaTeX有着下面的优点

- 对数学符号的支持很好，显示效果也很拔群
- 有着丰富的插件，如\ PSTricks_\下的\ pst-optexp_\能让你画出精美的\ 实验设计图_\
- 网络随处可见的LaTeX模版，值得一提的是硕士毕业论文基本只提供LaTeX模版而没有Word模版

不过不得不说LaTeX的易用性并不好，上手难度很大学习曲线也很陡，一个熟练的使用者经常也需要翻看参考书来实现某个功能。所以除了在理工科文档之外，LaTeX鲜少出现。

TUG提供了一个很好的\ LaTeX上手教材_\。掌握了之后对LaTeX基本语法基本就掌握了，下面只需要针对特定的扩展包学习即可。如果想对LaTeX有一个深入透彻的了解，包括它与TeX的关系，包括XeLaTeX，XeTeX，LuaTeX是怎么一回事，推荐从\ TeXbook_\开始阅读。

.. _PSTricks: http://tug.org/PSTricks/main.cgi/
.. _pst-optexp: http://www.ctan.org/pkg/pst-optexp
.. _实验设计图: http://ftp.snt.utwente.nl/pub/software/tex/graphics/pstricks/contrib/pst-optexp/pst-optexp.pdf
.. _LaTeX上手教材: https://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf
.. _TeXbook: http://web.mit.edu/jgross/www/LaTeX/texbook.pdf