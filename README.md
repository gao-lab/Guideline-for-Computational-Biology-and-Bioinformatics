# 完善中......

# Guideline-for-Computational-Biology-and-Bioinformatics


**目的**: 在原来的 [GCCS2019](https://github.com/gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/190317-guideline_for_common_computational_skills.pdf) 基础上对组内培养方案更具体的完善，大概会包括如何达到 GCCS2019 中的要求中的basic，advanced skills。

Ps. 对于一开始进组开始 intern 的同学建议全部掌握 Basic skills 且最好掌握部分 Advanced skills，basic skills 是能开始工作的基础，Advanced skills 是能做出原创性工作的前提。

## Basic Skills

这部分是能够开展工作的基础，至少需要了解的部分。
  
### Linux Foundation
对于 Linux 需要掌握一些最基础的基本操作，以及关于服务器的一些基本的常识。
* [Linux basic](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/Linux_Basics_2019.pdf) 和 [linux shortenned](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/linux_shortened.pdf) 
      都是基本的 Linux 知识，建议快速的看一遍，然后上手试一试，北大未名有免费的学生账号，可以[申请](http://hpc.pku.edu.cn/guide.html)
      
### Python

Basic 的 Python ，只需要掌握基本的语法，以及常见的 package 比如 numpy, pandas 的基础用法即可。
* [Basic Python](https://www.learnpython.org) 中文版本 [[link]](http://www.runoob.com/python/python-tutorial.html)
* [Python 100 days](https://github.com/jackfrued/Python-100-Days) 已经是很完整的 Python 的资料了，包括的内容非常多，basic 的话不需要全部掌握。

### R
* [R for beginners]((https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/R-for-beginners.pdf))
  适合初学者入门。
### Writing

* Markdown/Rmarkdown
Markdown 感觉是轻量级 LaTeX，最主要的就是也能支持数学公式。推荐 typora！来写 Markdown 
* LaTeX
LaTeX 基础的话推荐 [Basic latex](https://github.com/gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/LaTeX_basic.pdf)
看完这个，LaTeX 的基本的使用不成问题！如果想要尝试的话可以推荐使用 [Overleaf](https://www.overleaf.com)，上面有很多的 template 可以直接用。

## Math
* 高等数学
* 线性代数
* 概率论与数理统计



## Advanced Skills
Advanced Math 是在 Basic Math 的基础上的进阶，包括机器学习，统计学习，深度学习，贝叶斯理论，概率图模型，同学们按照自己的兴趣挑选学习即可。

*ps. 如何做出有价值的，其他人没想到的工作呢 1.你比人家聪明，2.你比人家知道的多。相比第一条，第二条是更容易实现的*

这边的分类可能存在点问题(待修改)
### Machine Learning
使用机器学习/统计学习方法挖掘组学数据其实就是生物信息做的事情，所以machine learning某种程度上也是 basic skill! 这部分资料其实非常多，Google 
随便搜索一下就能找到很多，下面简单的罗列一下我知道的，或者我看过觉得不错的的资料。

* Mooc
    * Coursera 上 Andrew Ng 的 Machine learning，深入浅出相当不错，建议快速刷完。[machine learning](https://www.coursera.org/learn/machine-learning)
，另外国内网易云上，bilibili上都有搬运的资料。
    * [**machine-learning-notes**](https://github.com/roboticcam/machine-learning-notes) 只要是里面有视频的部分讲的都非常清楚(Variational 
Inference, MC等)！而且中文格外亲切。
* Book
    * Pattern recognition and machine learning[(PRML)](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/PRML.pdf)

### Statistical Learning 
统计学习和机器学习其实没什么区别吧，因为毕竟有"统计"两个字,所以看起来更加令人信服！

* Mooc 
    * 李航的[统计学习](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/统计学习方法_李航.pdf)，短小精悍！建议专心读几天，一口气读完。
    * [Statistical Rethinking: A Bayesian Course Using R and Stan](https://github.com/rmcelreath/statrethinking_winter2019)这其中包括 slides, videos, homework(solution)。
* Book
    * [Introduction to Statistical Learning with R](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf) 这本比较简单，也有中文翻译版本，也是某种意义上李程老师的基因组数据分析所用的教材。
    * [The Element of Statistical Learning](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/ESL.pdf) 这本书比 ISL 更难，有更多的数学，而且中文版感觉翻译的不是很好，另外也是林伟老师的统计学习的教材.


### Deep Learning

* Coursera 上面的 [Deep Learning](https://www.coursera.org/specializations/deep-learning), Andrew Ng 讲的还是非常好的，另外 
[bilibili](https://www.bilibili.com/video/av49445369?from=search&seid=853459819773787018) 上也有搬运的。另外网易云上应该也有。
* 李沐的[动手学深度学习](https://zh.gluon.ai),框架使用的是MXNET，所以可能这部分借鉴意义不大，但是本身来说写的还是不错的，比那本非常有名的 deep learning 更适合学习。
* [Solution of Deep-Learning-Coursera](https://github.com/DeepakSridhar/Deep-Learning-Coursera)
* [Awesome - Most Cited Deep Learning Papers](https://github.com/terryum/awesome-deep-learning-papers) Deep learning 
中经典的论文


### Bayes
贝叶斯学派和频率学派的本质区别就是认为 parameter 没有确定的值，有的是分布。

* Book
    * [Bayesian Data Analysis](https://github.com/Gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/BDA.pdf)
        这本书内容比较多，是席瑞斌老师的贝叶斯的参考书。
    * [Awesome Bayes](https://github.com/dimenwarper/awesome-bayes) 里面包括非常多的关于贝叶斯的资源
    * [Think 系列](https://greenteapress.com/wp/) 中的
    [Think Bayes](https://github.com/gao-lab/Guideline-for-Computational-Biology-and-Bioinformatics/blob/master/pdf/Think-python.pdf) 
      
### Reinforce Learning


## Bioinformatics Analyze 

* Single Cell Analyze 
    * [Single cell RNA-seq course by sanger institute](https://scrnaseq-course.cog.sanger.ac.uk/website/index.html)


## Some Courses 

* Computational Biology Courses
    * [MIT Foundations of computational and systems biology](https://ocw.mit.edu/courses/biology/7-91j-foundations-of-computational-and-systems-biology-spring-2014/)
    * [stanford Computational Biology in Four Dimensions](https://cs371.stanford.edu/index.html) computational biology 的一些topic。
* Course in Peking university
    * 

## Related links
* [selection of books/urls for bioinformatics/data science curriculum](https://divingintogeneticsandgenomics.rbind.io/post/my-opinionated-selection-of-books-for-bioinformatics-data-science-curriculum/) Provided by Ming Tang
* [A New Online Computational Biology Curriculum](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003662) 

### People
* [屠鑫明](https://xinmingtu.cn)
* 陈子玉 
* 曹智杰
* 丁阳

