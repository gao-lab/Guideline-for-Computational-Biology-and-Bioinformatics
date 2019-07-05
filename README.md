
# Guideline-for-Computational-Biology-and-Bioinformatics


**目的**: 在原来的 [GCCS2019](https://githut.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/190317-guideline_for_common_computational_skills.pdf) 基础上对组内培养方案更具体的完善，大概会包括如何达到 GCCS2019 中的要求中的basic，advanced skills。

Ps. 对于一开始进组开始 intern 的同学建议全部掌握 Basic skills 且最好掌握部分 Advanced skills，basic skills 是能开始工作的基础，Advanced skills 是能做出原创性工作的前提。

# 完善中......

## Basic Skills

这部分是能够开展工作的基础，至少需要了解的部分。
### Linux Foundation
对于 Linux 需要掌握一些最基础的基本操作，以及关于服务器的一些基本的常识。

#### Book & Blog & Tutorial & Repo

[Linux basic](https://githut.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/Linux_Basics_2019.pdf) 和 [linux shortenned](https://githut.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/linux_shortened.pdf) 
都是基本的 Linux 知识，建议快速的看一遍，然后上手试一试，北大未名有免费的学生账号，可以[申请](http://hpc.pku.edu.cn/guide.html)

### Productivity Tools

**Pycharm**

**Tmux** 


### Python

Basic 的 Python ，只需要掌握基本的语法，以及常见的 package 比如 numpy, pandas 的基础用法即可。
* [Basic Python](https://www.learnpython.org) 中文版本 [[link]](http://www.runoob.com/python/python-tutorial.html)
* [Python 100 days](https://github.com/jackfrued/Python-100-Days) 已经是很完整的 Python 的资料了，包括的内容非常多，basic 的话不需要全部掌握。

### R

### Writing

#### Markdown/Rmarkdown
Markdown 感觉是轻量级 LaTeX，最主要的就是也能支持数学公式。

#### LaTeX
LaTeX 基础的话推荐 [Basic latex](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/LaTex_basic.pdf)
看完这个，LaTeX 的基本的使用不成问题！如果想要尝试的话可以推荐使用 [Overleaf](https://www.overleaf.com)，上面有很多的 template 可以直接用。配置中文的话可以看[XXX]()

## Basic Math

### Probability Theory and Statistics

### Stochastic Processes


## Advanced Skills
Advanced Math 是在 Basic Math 的基础上的进阶，包括机器学习，统计学习，深度学习，贝叶斯理论，概率图模型，同学们按照自己的兴趣挑选学习即可。

*ps. 如何做出有价值的，其他人没想到的工作呢 1.你比人家聪明，2.你比人家知道的多。相比第一条，第二条是更容易实现的*

这边的分类可能存在点问题(待修改)
### Machine Learning
使用机器学习/统计学习方法挖掘组学数据其实就是生物信息做的事情，所以machine learning某种程度上也是 basic skill! 这部分资料其实非常多，Google 
随便搜索一下就能找到很多，下面简单的罗列一下我知道的，或者我看过觉得不错的的资料。

#### Mooc

* Coursera 上 Andrew Ng 的机器学习，深入浅出相当不错，建议快速刷完。[machine learning](https://www.coursera.org/learn/machine-learning)
，另外国内网易云上，bilibili上都有搬运的资料。
* [**machine-learning-notes**](https://github.com/roboticcam/machine-learning-notes) 只要是里面有视频的部分讲的都非常清楚(Variational 
Inference, MC等)！而且中文格外亲切。


#### Book
* Pattern recognition and machine learning([(PRML)](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/PRML.pdf))

### Statistical Learning 
统计学习和机器学习其实没什么区别吧，所以为什么这是重要的和机器学习一样，但是相比之下可能说统计学习别人会觉得更可信，因为毕竟有"统计"两个字！

#### Mooc 

* 李航的[统计学习](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/统计学习方法_李航.pdf)，短小精悍！建议专心读几天，一口气读完。
* [Statistical Rethinking: A Bayesian Course Using R and Stan](https://github.com/rmcelreath/statrethinking_winter2019)这其中包括 slides, videos, homework(solution)。

#### Book
* [Introduction to Statistical Learning with R](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf) 这本比较简单，也有中文翻译版本，也是某种意义上李程老师的基因组数据分析所用的教材。
* [The Element of Statistical Learning](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/ESL.pdf) 这本书比 ISL 更难，有更多的数学，而且中文版感觉翻译的不是很好，另外也是林伟老师的统计学习的教材.

### Deep Learning

#### Mooc


* Coursera 上面的 [Deep Learning](https://www.coursera.org/specializations/deep-learning), Andrew Ng 讲的还是非常好的，另外 
[bilibili](https://www.bilibili.com/video/av49445369?from=search&seid=853459819773787018) 上也有搬运的。另外网易云上应该也有。
* 李沐的[动手学深度学习](https://zh.gluon.ai),没有看过但是应该不错。
* [Solution of Deep-Learning-Coursera](https://github.com/DeepakSridhar/Deep-Learning-Coursera)
* [Awesome - Most Cited Deep Learning Papers](https://github.com/terryum/awesome-deep-learning-papers) Deep learning 
中经典的论文

#### Book

### Bayes
贝叶斯学派和频率学派的本质区别就是认为 parameter 没有确定的值，有的是真实的分布。

#### Book
* [Bayesian Data Analysis](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/BDA.pdf)
* [Awesome Bayes](https://github.com/dimenwarper/awesome-bayes) 里面包括非常多的关于贝叶斯的资源


### Reinforce Learning


## Bioinformatics Analyze 

### Single Cell Analyze 


## Some Courses in Peking University

### Computational Biology Courses

* [stanford Computational Biology in Four Dimensions](https://cs371.stanford.edu/index.html) computational biology 
的一些topic。

### People
* 屠鑫明 xinmingtu@pku.edu.cn
* 陈子玉 
* 曹智杰
* 丁阳

