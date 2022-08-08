# 机器学习
### 1.机器学习起源
1. 人工智能是一个非常模糊的宽泛的概念，指的是利用机器来实现人类的智能，或者说是超越人类的智能。<br>
2. 具体实现人工智能的过程需要一些算法，这些算法就可以被统称为机器学习算法。<br>
3. 神经网络就是其中一个特别的机器学习算法，其模拟的就是人类的大脑的神经元的处理过程。<br>
4. 深度学习本质上就是神经网络，其最大的区别就是网络层数非常的深，这样可以提取出图片的特征更抽象，更容易给机器去判断。<br>
##### 3.网络数据采集 
1. 网络爬虫原理<br>
   a. 选取一部分种子URL放入队列，抓取这部分网页，同时提取其中的URL放入队列中，如此一直下去.<br>
   b. 通过必要的算法控制能够更全面的抓取互联网上的所有网页。这里有现成的Scrapy架构<br>
##### 4.感知设备数据
### 2.大数据预处理技术
##### 1.数据清理(数据分析和人工智能)
###### 1.遗漏数据处理 
1. 忽略该条记录<br>
   a. 这个应该是最主要的处理方法，毕竟大数据不在乎这几条.<br>
2. 利用均值填补遗漏值。<br>
3. 手工填补遗漏值。<br>
4. 利用默认值填补遗漏值。<br>
5. 利用同类别均值填补遗漏值。<br>
6. 利用最可能的值填补遗漏值。<br>
###### 2.噪声数据处理
1. Bin 方法，也就是用平均值进行替换。<br>
2. 聚类分析方法，这样可以有效的消除异常值。<br>
3. 人机结合检查方法。<br>
4. 回归方法。<br>
##### 2.数据集成
1. 模式集成问题，当多个数据库的数据集合在一起就会遇到这个问题。<br>
2. 冗余问题，如果一个数据能够从其他数据推演出来，就是冗余问题。<br>
3. 数据值冲突检测与消除问题，不同来源的数据需要进行整理分析。<br>
##### 3.数据转换
1. 最大最小规格化方法，这个在机器学习中非常常见。<br>
2. 零均值规格化方法，该方法是指根据一个属性的均值和方差来对该属性的值进行规格化。<br>
3. 十基数变换规格化方法，不同来源的数据需要进行整理分析。<br>
##### 4.数据消减
1. 维数消减，数据集可能包含成百上千的属性，而这些属性中的许多属性是与挖掘任务无关的或冗余的。<br>
2. 数据压缩，数据压缩就是利用数据编码或数据转换将原来的数据集合压缩为一个较小规模的数据集合。<br>
3. 数据块消减，数据块消减方法主要包括参数与非参数两种基本方法。所谓参数方法就是利用一个模型来帮助获得原来的数据，因此只需要存储模型的参数即可（当然异常数据也需要存储）。<br>
### 3.大数据存储及管理技术
##### 1.数值概念层次树
1. 数值概念层次树，Bin 方法，直方图方法，聚类分析方法，自然划分分段方法。<br>
2. 类别概念层次树，类别数据是一种离散数据。类别属性可取有限个不同的值且这些值之间无大小和顺序。<br>
##### 2.大数据处理技术
1. 分布式计算，就是把一组计算机通过网络相互连接组成分散系统，然后将需要处理的大量数据分散成多个部分，交由分散系统内的计算机组同时计算，最后将这些计算结果合并，得到最终的结果。<br>
2. 服务器集群，服务器集群是一种提升服务器整体计算能力的解决方案。它是由互相连接在一起的服务器群组成的一个并行式或分布式系统。<br>
3. 大数据的技术基础，Google 发表了 MapReduce、GFS（Google File System）和 BigTable 3 篇技术论文，提出了一套全新的分布式计算理论。<br>
##### 3.Google的三种大数据处理系统
1. GFS，GFS 解决了 Google 海量数据的存储问题。<br>
2. MapReduce，MapReduce 则是为了解决如何从这些海量数据中快速计算并获取期望结果的问题。。<br>
3. BigTable，BigTable 是 Google 设计的分布式数据存储系统，是用来处理海量数据的一种非关系型数据库。BigTable 是一个稀疏的、分布式的、持久化存储的多维度排序的映射表。<br>
##### 4.Hadoop大数据处理框架简介
1. Hadoop 系统简介，Hadoop 和 Google 内部使用的分布式计算系统原理相同，其开源特性使其成为分布式计算系统的事实上的国际标准。<br>
2. Hadoop 生态圈，HDFS，MapReduce，HBase，Hive，Mahout，Pig，Zookeeper，Flume。<br>
3. Hadoop 版本演进。<br>
4. Hadoop 发行版本。<br>
##### 5.HDFS分布式文件系统简介
1. 分布式文件系统是一种允许文件通过网络在多台主机上进行分享的文件系统，可让多台机器上的多用户分享文件和存储空间。
2. 一类是 NameNode，又叫“名称结点”；另一类是 DataNode，又叫“数据结点”。这两类结点分别承担 Master 和 Worker 具体任务的执行。
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
