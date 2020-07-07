# Daily Reading

Important Paper Source

- ACL
- EMNLP
- NIPS
- ICLR
- ICML

### >> 0707

- Critically Examining the "Neural Hype": Weak Baselines and the Additivity of Effectiveness Gains from Neural Ranking Models [~Paper](https://cs.uwaterloo.ca/~jimmylin/publications/Yang_etal_SIGIR2019.pdf)

  这篇paper很有意思，质疑了现有了几种neural ir model并没有超越很多年前的strong baselines，并且很多neural model的增益不可以累加

  Reinfoselect 提到了without large scale relevance labels, Neural model的effectivenss. without the luxury of large amounts of relevance-specific supervision signals

- Neural Ranking Models with Weak Supervision [~Paper](https://arxiv.org/pdf/1704.08803.pdf)

  这篇也有意思，需要多少training data，才能超越week supervision

  其中关于"How useful is learning with weak supervision for supervised ranking? "的讨论对我很有帮助

  (1) Weakly supervised: only trained on weakly supervised data

  (2) Fully supervised: only trained on supervised data

  (3) Weakly supervised + Fully supervised: pre-trained using the weakly supervised data and then ne tuned using relevance judgments

  

- [Optimizing data usage via differentiable rewards](https://arxiv.org/pdf/1911.10088.pdf)

- [Balancing Training for Multilingual Neural Machine Translation](https://arxiv.org/pdf/2004.06748.pdf)
  Multilingual machie translation (MT) model that can translate to/from multiple languages(one-many, many-to-one), but faced with imbalanched training sets. This paper propose a data scorer that learns to weight training data to maximize the performance on all test languages. This papers follow [Optimizing data usage via differentiable rewards] (https://arxiv.org/pdf/1911.10088.pdf)

- [Meta-Learning for Low-Resource Neural Machine Translation](https://www.aclweb.org/anthology/D18-1398.pdf) * 
  This paper extend MAML for low resource neural translaition based on  multilingual high-resource language tasks. The proposed approach significantly outperforms transfer learning based approach.
  - Spotlights: 
    - (1) MAML could be applied to low-resource machine translation by viewing language pairs as separate tasks.
    - (2) vanilla MAML cannot handle tasks with mismached input and output, thus this paper incorporates the universal lexical representation (Gu et al., 2018) for meta-learning scenario.

- [TF-Ranking: Scalable TensorFlow Library for Learning-to-Rank](https://arxiv.org/pdf/1812.00073.pdf)

  A ranking problem is different from classification or regression tasks, the latters aim to predict a label or a value for each individual item as accurately as possible; the goal of the former is to sort the entire item list, with items of higher relevance being prioritized. In a ranking problem, we are more concerned with the relative order of the relevance of items than their absolute magnitudes.

  learning-to-rank methods: fall into one of pointwise, pairwise, or listwise classes, pairwise and listwise methods are more closely aligned with the ranking task.

- [Learning Data Manipulation for Augmentation and Weighting](https://arxiv.org/pdf/1910.12795.pdf)

  This paper mention a new item (I haven't heard before) —— Manipulating data, including weighting data examples, augmenting new instances.

  Previous works design different learning algorithms for different data manipulation schemas. (either augmentation or weighting)

  This paper proposes the same gradient-based algorithms for different manipulation schemas.

  Important to me: have BERT code

<!-- [An Alternative Cross Entropy Loss for Learning-to-Rank]() -->
