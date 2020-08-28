# Paper List

#### Understanding black-box predictions via influence functions [Paper](https://arxiv.org/pdf/1703.04730.pdf)

**>> Abstract**

如何解释 a black-box model的prediction？本文采用influence functions，追踪model prediction to training data, 最终确定到底哪个data对model preidiction至关重要。

为了对machine learning的setting运用influence functions, 本文提出一种方法仅需access to gradients and Hessian-vector products.

即使在non-convex and non-differentiable model上，influence functions仍提供了有价值的信息。

本文在Linear model and Convolution neural network上验证了influence functions可以用于：
- Understanding model behavior
- debugging model
- detecting model behavior
- create visually-indistinguishable training-set attacks

🤔 所以什么是influence functions? 它又是如何利用gradients来trac model predictions的？好奇作者怎么在model上验证提到的几种用途？

**>> Introduction**

在解释black-box model上已有的工作大多研究: 一个固定的model，如何做出特定的预测, 比如对test point进行扰动，看看prediction如何变化。本文通过model的learning algorithm追踪model prediction最终back to its training data.

为了判断a training point对a prediction的影响，我们可以问这么一个问题: 如果没有这个training point会怎么样? 但是如果为了测试a training data就重新训一遍model这代价也太大了，因此作者使用了influence functions (a classic technique from robust statistics, 1980)，它告诉了我们如果对a training point进行无穷小的upweight，model parameter如何变化。

但influence function的应用障碍是: expensive second derivative calculations and assume model differentiability and convexity.

我们可以利用second-order optimzation 技术对influence functions进行进行，即使在不可微或非凸问题上都具备accurate.

**>> Approach**
