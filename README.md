# Daily Reading

Important Paper Source

- ACL
- EMNLP
- NIPS
- ICLR
- ICML

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
