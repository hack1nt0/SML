# SML(Scalable Machine Learning)

This is a collections of assignments and thinking of course
https://courses.edx.org/courses/BerkeleyX/CS190.1x/1T2015/info

### Overview
1，机器学习的流水线（pipeline)，2, 探索性数据分析（exploratory data analysis,
主要包括可视化等），3，相关算法的分布式实现（spark、矩阵分解计算和迭代算法等），4，领域知识和技术知识的浅显却不失动机和感性的解释。

### lab3
1，线性回归用于回归问题的流程（LabeledPoint、LinearRegressionModel、Grid Search、RMSE等配合）；

2，画表格图专用的Heap Map（plt.imshow），以及为图中元素着色的抽象色板参数cmap（matplotlib.cm？）；

### lab4
1，词袋编码（one-hot-encoding，OHE），可以消除一个feature不同category基数编码后产生的依赖性；

2，分布式构建OHE词典(利用特征哈希，前者的另一个作用是减少特征数量）；

3，ROC曲线（x轴：假阳率，y轴：真阳率， 作用是在选取合适的分类阈值）；

4，逻辑回归中的代价函数（log loss，有一种图形解释，也可以通过最大似然概率P(y|x)解释）；

### lab5
1，N维高斯分布，通过指定协变方差矩阵，可以方便的采样得到具备特定相关性的N维变量；

2，PCA的两种分布式实现（对应于大N、小d和大N、大d，其中后者适用Krylov subspace methods？）

3，进行PCA之前必要的数据预处理（均值归零等规范化, 以及规范化的必要性？），以及PCA可行的两个理论假设（新数据是旧数据的线性变换，旧数据的投影向量是相互正交的，这两者不一定总是合适，故而有其他的PCA变种，比如manifold learning？）

4，可视化中对二维向量所用的颜色映射方法是极坐标转化和HSV？

5，基于特征不同分类的特征聚合（feature-based aggregation)，作为PCA之前的步骤，可以用来混入先验知识，与PCA配合可以得到某些更抽象的相似性（以文中领域的例子，有时间动态（temporal dynamics）和刺激选择性两方面的相似性）

6，Top 2 主成份（principal component)所构成的超平面，也是原数据的欧几里德距离最小的平面？


Happy Reading and Communicating.
