# 机器学习
### 1.机器学习起源
1. 人工智能是一个非常模糊的宽泛的概念，指的是利用机器来实现人类的智能，或者说是超越人类的智能。<br>
2. 具体实现人工智能的过程需要一些算法，这些算法就可以被统称为机器学习算法。<br>
3. 神经网络就是其中一个特别的机器学习算法，其模拟的就是人类的大脑的神经元的处理过程。<br>
4. 深度学习本质上就是神经网络，其最大的区别就是网络层数非常的深，这样可以提取出图片的特征更抽象，更容易给机器去判断。<br>
### 2.回归
##### 1.回归介绍
1. 回归这个词的意思是子代会趋向于平均数，即父代的差异值会在子代中回归。<br>
2. 我们使用回归的目标就是预测未来的平均值。<br>
##### 2.代价函数
1. 代价函数又叫损失函数，就是预测值和实际值之间的差值。就可以得到一个关于参数的代价函数，并可以求得代价函数的最小值。<br>
##### 3.相关系数
1. 自变量和因变量之间的相关关系。<br>
##### 决定系数
1. 也是自变量和因变量之间的相关关系。<br>
##### 4.梯度下降法
1. 随机选择一点，然后求解这个点附近所有的倒数，得到最大变化的方向之后，之后再换 一个点。反复操作之后就可以到达最低点了。如果形象的比喻的话，可以说是丢一个球，球会自动向下走。<br>
##### 5.多元线性回归
1. 这里指的多元线性回归主要是指的一阶线性回归。<br>
##### 6.多项式回归
1. 关于一个或多个变量的多次函数。<br>
2. 可以使用标准方程法求解出最小值，此时的矩阵是可逆的。<br>
##### 7.标准方法
1. 对于多项式回归有的时候可以使用标准方法来求解，前提是其矩阵是可逆的。<br>
##### 5.HDFS分布式文件系统简介
1. 分布式文件系统是一种允许文件通过网络在多台主机上进行分享的文件系统，可让多台机器上的多用户分享文件和存储空间。
2. 一类是 NameNode，又叫“名称结点”；另一类是 DataNode，又叫“数据结点”。这两类结点分别承担 Master 和 Worker 具体任务的执行。·
### 4.数据挖掘(数据分析)
##### 1.数据挖掘是什么
###### 1.什么是数据挖掘
1. 数据挖掘可简单地理解为通过对大量数据的操作，发现有用的知识的过程。它是一门涉及面很广的交叉学科，包括机器学习、数理统计、神经网络、数据库、模式识别、粗糙集、模糊数学等相关技术。
###### 2.数据挖掘的价值类型
1. 相关性，相关性分析是指对两个或多个具备相关性的变量元素进行分析，从而衡量两个变量因素的相关密切程度。<br>
2. 趋势，趋势分析是指将实际达到的结果，与不同时期财务报表中同类指标的历史数据进行比较，从而确定财务状况、经营成果和现金流量的变化趋势和变化规律的一种分析方法。<br>
3. 特征，特征分析是指根据具体分析的内容寻找主要对象的特征。<br>
###### 3.数据挖掘算法的类型
1. 有监督的学习是基于归纳的学习，是通过对大量已知分类或输出结果的数据进行训练，建立分类或预测模型，用来分类未知实例或预测输出结果的未来值。<br>
2. 无监督学习方法是在学习训练之前，对没有预定义好分类的实例按照某种相似性度量方法，计算实例之间的相似程度，并将最为相似的实例聚类在一组，解释每组的含义，从中发现聚类的意义。<br>
##### 2.分类和预测
1. 分类的基本概念，分类算法反映的是如何找出同类事物的共同性质的特征型知识和不同事物之间的差异性特征知识。分类是通过有指导的学习训练建立分类模型，并使用模型对未知分类的实例进行分类。分类输出属性是离散的、无序的。<br>
2. 预测的基本概念，预测模型与分类模型类似，可以看作一个映射或者函数 y=f(x)，其中，x 是输入元组，输出 y 是连续的或有序的值。与分类算法不同的是，预测算法所需要预测的属性值是连续的、有序的，分类所需要预测的属性值是离散的、无序的。<br>
##### 3.决策树和朴素贝叶斯算法
1. 决策树算法，决策树（Decision Tree，DT）分类法是一个简单且广泛使用的分类技术。决策树是一个树状预测模型，它是由结点和有向边组成的层次结构。<br>
2. 朴素贝叶斯算法，朴素贝叶斯（Nawe Bayes）算法是一种十分简单的分类算法。它的基础思想是，对于给出的待分类项，求解在此项出现的条件下各个类别出现的概率，哪个最大，就认为此待分类项属 于哪个类别。<br>
##### 4.回归分析预测技术
1. 回归分析的基本概念是用一群变量预测另一个变量的方法。通俗点来讲，就是根据几件事情的相关程度来预测另一件事情发生的概率。回归分析的目的是找到一个联系输入变量和输出变量的最优模型。<br>
##### 5.聚类分析方法
1. 基本概念，聚类（Clustering）就是一种寻找数据之间内在结构的技术。聚类把全体数据实例组织成一些相似组，而这些相似组被称作簇。处于相同簇中的数据实例彼此相同，处于不同簇中的实例彼此不同。<br>
2. 聚类分析方法的类别，目前存在大量的聚类算法，算法的选择取决于数据的类型、聚类的目的和具体应用。聚类算法主要分为 5 大类：基于划分的聚类方法、基于层次的聚类方法、基于密度的聚类方法、基于网格的聚类方法和基于模型的聚类方法。<br>
### 5.大数据预测与应用
