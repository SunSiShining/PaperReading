# English Collection

**Learning Deep Structured Semantic Models for Web Search using Clickthrough Data**

  - 有两段英文描述keyphrase-based matching与unsupervised IR的文字很好记录一下

  - These latent semantic models address the language discrepancy between Web documents and search queries by grouping different terms that occur in a similar context into the same semantic cluster. Thus, a query and a document, represented as two vectors in the lower-dimensional semantic space, can still have a high similarity score even if they do not share any term.

  - These semantic matching models are often trained in an unsupervised manner using an objective function that is only loosely coupled with the evaluation metric for the retrieval task. Thus the performance of these models on Web search tasks is not as good as originally expected.

**DeepRank: A New Deep Architecture for Relevance Ranking in Information Retrieval**

  - 对前人工作的总结很棒， A ranking list is produced by sorting in descending order of the relevance score.

**Don’t Stop Pretraining: Adapt Language Models to Domains and Tasks**

  - Our experiments show that continued pretraining on the domain (which we refer to as domain-adaptive pretraining or DAPT) consistently improves performance on tasks from the target domain, in both high- and low-resource settings.

## 描述发展很快



Recent progress in Natural Language Understanding (NLU) is **driving fast-paced advances** in Information Retrieval (IR), **largely owed to** fine-tuning deep language models (LMs) for document ranking.

While remarkably effective, the ranking models based on these LMs **increase computational cost by orders of magnitude over prior approaches**, particularly as they must feed each query–document pair through a massive neural network to compute a single relevance score.

Results show that ColBERT’s eectiveness is competitive
with existing BERT-based models (and outperforms every nonBERT baseline), while **executing two orders-of-magnitude faster** and *8requiring four orders-of-magnitude fewer** FLOPs per query.


However, the remarkable gains **delivered by** these LMs **come at a steep increase in** computational cost.
