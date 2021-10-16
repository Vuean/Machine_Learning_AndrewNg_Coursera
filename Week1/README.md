# 第一周

Welcome to Machine Learning! In this module, we introduce the core idea of teaching a computer to learn concepts using data—without being explicitly programmed. 

We are going to start by covering linear regression with one variable. Linear regression predicts a real-valued output based on an input value. We discuss the application of linear regression to housing price prediction, present the notion of a cost function, and introduce the gradient descent method for learning.

We’ll also have optional lessons that provide a refresher on linear algebra concepts. Basic understanding of linear algebra is necessary for the rest of the course, especially as we begin to cover models with multiple variables. If you feel confident in your understanding of linear algebra, feel free to take a break or help other students out in the forums.

## Introduction

### 1.1 欢迎参加《机器学习》课程

第一个视频主要讲了什么是机器学习，机器学习能做些什么事情。

机器学习是目前信息技术中最激动人心的方向之一。在这门课中，你将学习到这门技术的前沿，并可以自己实现学习机器学习的算法。

### 1.2 什么是机器学习？

Arthur Samuel：定义机器学习为，在进行特定编程的情况下，使计算机**具有学习能力**的领域。

Tom Mitchell：计算机程序从经验E中学习，解决任务T，达到性能度量值P，通过P测定在处理任务T时的性能因经验E而提高。

主要的学习算法可分为：**监督学习（Supervised Learning）**和**无监督学习（Unsupervised Learning）**。

### 1.3 监督学习

监督学习：给学习算法一个由“正确答案”组成的数据集，然后运用学习算法，算出更多的正确答案。用术语来讲，这叫做**回归问题**（regression problem）。我们试着推测出一个**连续值**的结果。还有**分类问题**（classfication problem），试着推出**离散的**输出值。

在处理分类问题过程中，为了让算法可以利用大量的特征或线索来推测，那么如何来存储这些特征？可通过**支持向量机**，能让计算机处理无限多个特征。

监督学习的基本思想是，我们数据集中的每个样本都有相应的“正确答案”。再根据这些样本作出预测。其中包括有回归问题，即通过回归来推出一个连续的输出；和分类问题，其目标是推出一组离散的结果。

### 1.4 无监督学习

无监督学习中的数据可能没有任何标签、或者是相同的标签。针对数据集，无监督学习能将数据分为不同的簇，这也称为**聚类算法**（clustering algorithm）。

## Liner Regression with One Variable

### 2.1 模型描述


## Linear Algebra Review

线性代数回顾

