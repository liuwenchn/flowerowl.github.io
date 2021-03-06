---
title: The meaning of some terms in DM
author: Flowerowl
layout: post
permalink: /4007.html
views:
  - 667
categories:
  - DM
tags:
  - DM
---
### Basis(基础)：

MSE(Mean Square Error 均方误差)，

LMS(LeastMean Square 最小均方)，

LSM(Least Square Methods 最小二乘法)，

MLE(MaximumLikelihood Estimation最大似然估计)，

QP(Quadratic Programming 二次规划)，

CP(Conditional Probability条件概率)，

JP(Joint Probability 联合概率)，

MP(Marginal Probability边缘概率)，

Bayesian Formula(贝叶斯公式)，

L1 /L2Regularization(L1/L2正则，以及更多的，现在比较火的L2.5正则等)，

GD(GradientDescent 梯度下降)，

SGD(Stochastic Gradient Descent 随机梯度下降)，

Eigenvalue(特征值)，

Eigenvector(特征向量)，

QR-decomposition(QR分解)，

Quantile (分位数)，

Covariance(协方差矩阵)。

### Common Distribution(常见分布)：

Discrete Distribution(离散型分布)：

BernoulliDistribution/Binomial(贝努利分布/二项分布)，

Negative BinomialDistribution(负二项分布)，

MultinomialDistribution(多项式分布)，

Geometric Distribution(几何分布)，

HypergeometricDistribution(超几何分布)，

Poisson Distribution (泊松分布)。

### Continuous Distribution (连续型分布)：

UniformDistribution(均匀分布)，

Normal Distribution /Guassian Distribution(正态分布/高斯分布)，

ExponentialDistribution(指数分布)，

Lognormal Distribution(对数正态分布)，

GammaDistribution(Gamma分布)，

Beta Distribution(Beta分布)，

Dirichlet Distribution(狄利克雷分布)，

Rayleigh Distribution(瑞利分布)，

Cauchy Distribution(柯西分布)，

Weibull Distribution (韦伯分布)。

### Three Sampling Distribution(三大抽样分布)：

Chi-squareDistribution(卡方分布)，

t-distribution(t-distribution)，

F-distribution(F-分布)。

### Data Pre-processing(数据预处理)：

Missing Value Imputation(缺失值填充)，

Discretization(离散化)，Mapping(映射)，

Normalization(归一化/标准化)。

### Sampling(采样)：

Simple Random Sampling(简单随机采样)，

OfflineSampling(离线等可能K采样)，

Online Sampling(在线等可能K采样)，

Ratio-based Sampling(等比例随机采样)，

Acceptance-RejectionSampling(接受-拒绝采样)，

Importance Sampling(重要性采样)，

MCMC(MarkovChain Monte Carlo 马尔科夫蒙特卡罗采样算法：Metropolis-Hasting& Gibbs)。

### Clustering(聚类)：

K-Means，

K-Mediods，

二分K-Means，

FK-Means，

Canopy，

Spectral-KMeans(谱聚类)，

GMM-EM(混合高斯模型-期望最大化算法解决)，

K-Pototypes，CLARANS(基于划分)，

BIRCH(基于层次)，

CURE(基于层次)，

DBSCAN(基于密度)，

CLIQUE(基于密度和基于网格)。

### Classification&Regression(分类&回归)：

LR(Linear Regression 线性回归)，

LR(LogisticRegression逻辑回归)，

SR(Softmax Regression 多分类逻辑回归)，

GLM(GeneralizedLinear Model 广义线性模型)，

RR(Ridge Regression 岭回归/L2正则最小二乘回归)，

LASSO(Least Absolute Shrinkage andSelectionator Operator L1正则最小二乘回归)，

RF(随机森林)，

DT(DecisionTree决策树)，

GBDT(Gradient BoostingDecision Tree 梯度下降决策树)，

CART(ClassificationAnd Regression Tree 分类回归树)，

KNN(K-Nearest Neighbor K近邻)，

SVM(Support VectorMachine)，

KF(KernelFunction 核函数PolynomialKernel Function 多项式核函、

Guassian KernelFunction 高斯核函数/Radial BasisFunction RBF径向基函数、

String KernelFunction 字符串核函数)、

NB(Naive Bayes 朴素贝叶斯)，

BN(Bayesian Network/Bayesian Belief Network/ Belief Network 贝叶斯网络/贝叶斯信度网络/信念网络)，

LDA(Linear Discriminant Analysis/FisherLinear Discriminant 线性判别分析/Fisher线性判别)，

EL(Ensemble Learning集成学习Boosting，Bagging，Stacking)，

AdaBoost(Adaptive Boosting 自适应增强)，

MEM(MaximumEntropy Model最大熵模型)。

### Effectiveness Evaluation(分类效果评估)：

Confusion Matrix(混淆矩阵)，

Precision(精确度)，

Recall(召回率)，

Accuracy(准确率)，

F-score(F得分)，

ROC Curve(ROC曲线)，

AUC(AUC面积)，

LiftCurve(Lift曲线) ，

KS Curve(KS曲线)。

### PGM(Probabilistic Graphical Models概率图模型)：

BN(Bayesian Network/Bayesian Belief Network/ BeliefNetwork 贝叶斯网络/贝叶斯信度网络/信念网络)，

MC(Markov Chain 马尔科夫链)，

HMM(HiddenMarkov Model 马尔科夫模型)，

MEMM(Maximum Entropy Markov Model 最大熵马尔科夫模型)，

CRF(ConditionalRandom Field 条件随机场)，

MRF(MarkovRandom Field 马尔科夫随机场)。

### NN(Neural Network神经网络)：

ANN(Artificial Neural Network 人工神经网络)，

BP(Error BackPropagation 误差反向传播)。

### Deep Learning(深度学习)：

Auto-encoder(自动编码器)，

SAE(Stacked Auto-encoders堆叠自动编码器，

Sparse Auto-encoders稀疏自动编码器、

Denoising Auto-encoders去噪自动编码器、

Contractive Auto-encoders 收缩自动编码器)，

RBM(RestrictedBoltzmann Machine 受限玻尔兹曼机)，

DBN(Deep Belief Network 深度信念网络)，

CNN(ConvolutionalNeural Network 卷积神经网络)，

Word2Vec(词向量学习模型)。

### DimensionalityReduction(降维)：

LDA LinearDiscriminant Analysis/Fisher Linear Discriminant 线性判别分析/Fisher线性判别，

PCA(Principal Component Analysis 主成分分析)，

ICA(IndependentComponent Analysis 独立成分分析)，

SVD(Singular Value Decomposition 奇异值分解)，

FA(FactorAnalysis 因子分析法)。

### Text Mining(文本挖掘)：

VSM(Vector Space Model向量空间模型)，

Word2Vec(词向量学习模型)，

TF(Term Frequency词频)，

TF-IDF(Term Frequency-Inverse DocumentFrequency 词频-逆向文档频率)，

MI(MutualInformation 互信息)，

ECE(Expected Cross Entropy 期望交叉熵)，

QEMI(二次信息熵)，

IG(InformationGain 信息增益)，

IGR(Information Gain Ratio 信息增益率)，

Gini(基尼系数)，

x2 Statistic(x2统计量)，

TEW(TextEvidence Weight文本证据权)，

OR(Odds Ratio 优势率)，

N-Gram Model，

LSA(Latent Semantic Analysis 潜在语义分析)，

PLSA(ProbabilisticLatent Semantic Analysis 基于概率的潜在语义分析)，

LDA(Latent DirichletAllocation 潜在狄利克雷模型)。

### Association Mining(关联挖掘)：

Apriori，

FP-growth(Frequency Pattern Tree Growth 频繁模式树生长算法)，

AprioriAll，

Spade。

### Recommendation Engine(推荐引擎)：

DBR(Demographic-based Recommendation 基于人口统计学的推荐)，

CBR(Context-basedRecommendation 基于内容的推荐)，

CF(Collaborative Filtering协同过滤)，

UCF(User-basedCollaborative Filtering Recommendation 基于用户的协同过滤推荐)，

ICF(Item-basedCollaborative Filtering Recommendation 基于项目的协同过滤推荐)。

### Similarity Measure&Distance Measure(相似性与距离度量)：

Euclidean Distance(欧式距离)，

ManhattanDistance(曼哈顿距离)，

Chebyshev Distance(切比雪夫距离)，

MinkowskiDistance(闵可夫斯基距离)，

Standardized Euclidean Distance(标准化欧氏距离)，

MahalanobisDistance(马氏距离)，

Cos(Cosine 余弦)，

HammingDistance/Edit Distance(汉明距离/编辑距离)，

JaccardDistance(杰卡德距离)，

Correlation Coefficient Distance(相关系数距离)，

InformationEntropy(信息熵)，

KL(Kullback-Leibler Divergence KL散度/Relative Entropy 相对熵)。

### Optimization(最优化)：

Non-constrainedOptimization(无约束优化)：

Cyclic VariableMethods(变量轮换法)，

Pattern Search Methods(模式搜索法)，

VariableSimplex Methods(可变单纯形法)，

Gradient Descent Methods(梯度下降法)，

Newton Methods(牛顿法)，

Quasi-NewtonMethods(拟牛顿法)，

Conjugate Gradient Methods(共轭梯度法)。

### ConstrainedOptimization(有约束优化)：

Approximation Programming Methods(近似规划法)，

FeasibleDirection Methods(可行方向法)，

Penalty Function Methods(罚函数法)，

Multiplier Methods(乘子法)。

Heuristic Algorithm(启发式算法)，

SA(SimulatedAnnealing，模拟退火算法)，

GA(genetic algorithm遗传算法)。

### Feature Selection(特征选择算法)：

Mutual Information(互信息)，

DocumentFrequence(文档频率)，

Information Gain(信息增益)，

Chi-squared Test(卡方检验)，

Gini(基尼系数)。

### Outlier Detection(异常点检测算法)：

Statistic-based(基于统计)，

Distance-based(基于距离)，

Density-based(基于密度)，

Clustering-based(基于聚类)。

### Learning to Rank(基于学习的排序)：

Pointwise：McRank；

Pairwise：RankingSVM，RankNet，Frank，RankBoost；

Listwise：AdaRank，SoftRank，LamdaMART。


source: http://blog.csdn.net/heyongluoyao8/article/details/39299913
