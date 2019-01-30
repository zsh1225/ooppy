# “面向对象程序设计基础与Python语言”讲义

## 内容
diagrams含插图。
examples含Python程序例子。

## 免责声明

如果发现文字或代码侵权，请及时联系。
作者会删除侵权内容。

# 课程目标、教学措施
## 课程目标
Python是一种工具，课程目标是让学生学会使用工具、会自学、会制造新工具三个方面展开。
## 教学措施
### 使用工具
教授PYTHON基本知识，让学生掌握编程的基本手段。涵盖：基础数据类型。程序控制结构。高级数据类型，由于PYTHON重试依赖列表和字典，因此，这两个数据类型应归程序设计课讲授，而不归数据结构讲授。函数。模块。面向对象基础技术，面向对象只讲封装、继承、多态三种技术，不枝蔓。异常。学习上述基础技术，学生基本可以撰写程序了。PYTHON面向对象还有更丰富内容，如封装对应的资产、继承对应的多继承、多态对应的装相和虚基类，乃至装饰器、迭代器、生成器、多线程。这些归为一章，名为高级面向对象技术。它们是PYTHON特有的技术，而非面向对象语言标准技术，因此，单独立章。可讲，可自学。

数据抽象主要思想是鼓励程序定义自己的数据类型。

### 自学
内容多，不可能面面俱到，都学。因此，要都会学生自学。
1. 定位自学材料，Python Llibrary，自带的doc。要求自学，logging，argparse，doctest，PYTEST，SPHINX。
2. 搜索，stackoverflow。
3. file定位源代码。

### 制造工具
用python开发软件。
模块化编程最重要部分，就是记录库方法的用法，撰写供他人参考的文档。
1. 定义一位api，api要旨即调用、实现分离。举例，比如Counter，累加器，日期，howdoi，auth，记事本？设计软件sphinx
2. 编程，实现api定义
3. 测试，doctest，pytest
4. 打包，发布pypi或github。安装包。
学习时的案例，也有意按开发思路讲。

### 实验
针对python的擅场，设计三个实验：脚本、网页、数据分析
脚本：howdoi
网页：flask
数据分析：决策树、k-means自主实现，及scikit-learn。这部分不只是开发软件，相当于做科研，因此两个目的。一是遵循科学式的做法：先提出假设、再建立数学模型、再次用多种实验验证它们。必要时，重复这个过程。二是做出可复用的研究，虚拟环境和jupyter notebook。

# 算法
算法只能前两步，学习算法，分析算法，没有第三步创造算法，即设计算法。
性能是算法研究的核心问题。
学习是了解现有算法，它们解决哪些问题，性能如何。
分析是复杂度分析。
设计应当是数学任务，而非计算机任务。因此不讲，但可以提提设计算法思想。