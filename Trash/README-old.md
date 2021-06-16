# Paper Weekly


### 3/25-3/11

|Area|Title|Idea|Disscussion|
|:---|:----|:---|:---|
|Data Augmentation|**Neural Data Augmentation via Example Extrapolation.** *arXiv 2021.* [[PDF]](https://arxiv.org/pdf/2102.01335.pdf)|在Many-shot类上训练一个可以根据K个样本生成新样本的生成器，然后作用于Few-shot类上，在几个任务的dataset上overall提升虽然不大，但是few-shot class上的提升还是比较显著的，相当于固定label生成新样本|【Pos】文中对related work有一个比较好的回顾，可以帮助我更好的review【Neg】我没看出来idea的新颖之处，而且对paper中related work的"these heuristics may not scale well and are poor approximation of the complexity of real examples"描述存疑
|Data Augmentation|**A Closer Look At Feature Space Data Augmentation For Few-Shot Intent Classification.** *ACL 2019.* [[PDF]](https://www.aclweb.org/anthology/D19-6101.pdf)|针对Few-shot conversation topics的问题，研究了6种feature space data augmentation methods|【Pos】对不同方法阐述与分析都比较清楚，提到了active learning, metric learning以及feature-based data augmentation的相关工作都是我比较感兴趣的|
||
|Active Learning|**Active Learning.** [[PPT]](http://www.cs.cmu.edu/~epxing/Class/10701-12f/Lecture/settles.active-nov14.pdf)|Burr Settles 2010年的总结|
|Active Leanring|**Active Learning Literature Survey.** [[PDF]](https://minds.wisconsin.edu/bitstream/handle/1793/60660/TR1648.pdf?sequence=1)|
|Active Leanring|**Active Learning for Ranking through Expected Loss Optimization.** [[PDF]](http://www.yichang-cs.com/yahoo/TKDE2015_activelearning.pdf)|
|Active Leanring|**Active learning by querying informative and representative examples.** [[PDF]](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.231.220&rep=rep1&type=pdf)|
|Active Learning|**An Active Learning Algorithm for Ranking from Pairwise Preferences with an Almost Optimal Query Complexity.** [[PDF]](https://www.jmlr.org/papers/volume13/ailon12a/ailon12a.pdf)|
|Active Learning|**An Analysis of Active Learning Strategies for Sequence Labeling Tasks.** *EMNLP 2008.* [[PDF]](https://www.aclweb.org/anthology/D08-1112.pdf)|
||
|Active Learning|**Active Learning for New Domains in Natural Language Understanding.** ** *NAACL 2019.*  [[PDF]](https://www.aclweb.org/anthology/N19-2012.pdf)|
|

- Few-shot Learning

Prototypical networks for few-shot learning.

- Metric Learning
Diverse few-shot text classification with multiple metrics

Attentive task-agnostic meta-learning for few-shot text classification

- other data augmentation
Sequence-to-sequence data augmentation for dialogue language understanding

Data augmentation with atomic templates for spoken language understanding.

Generating sentences by editing prototypes

Data augmentation for spoken language understanding via joint variational generation


 Efficient semisupervised learning for natural language understanding by optimizing diversity
--------

Good-Enough Compositional Data Augmentation
https://www.aclweb.org/anthology/2020.acl-main.676.pdf

Do Not Have Enough Data? Deep Learning to the Rescue!

* Feature-based data augmentation
  - Low-shot Visual Recognition by Shrinking and Hallucinating Features https://arxiv.org/abs/1606.02819
  - Dataset augmentation in feature space https://arxiv.org/pdf/1702.05538.pdf

  - Augmenting data with mixup for sentence clas- sification: An empirical study https://arxiv.org/pdf/1905.08941.pdf

* 变分自编码器

  - Tutorial on Variational Autoencoders https://arxiv.org/pdf/1606.05908.pdf


Learning to Recombine and Resample Data for Compositional Generalization
https://openreview.net/pdf?id=PS3IMnScugk


Hierarchical Attention Prototypical Networks for Few-Shot Text Classification
https://www.aclweb.org/anthology/D19-1045.pdf


Simple and Effective Few-Shot Named Entity Recognition with Structured Nearest Neighbor Learning
https://www.aclweb.org/anthology/2020.emnlp-main.516.pdf


Exploiting Cloze Questions for Few Shot Text Classification and Natural Language Inference
https://arxiv.org/pdf/2001.07676.pdf

Evaluation of Output Embeddings for Fine-Grained Image Classification
https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Akata_Evaluation_of_Output_2015_CVPR_paper.pdf


The Effectiveness of Data Augmentation in Image Classification using Deep
Learning
https://arxiv.org/pdf/1712.04621.pdf
