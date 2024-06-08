# 大型语言模型赋能推荐系统，使其在样本利用上更为高效。

发布时间：2024年06月04日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在推荐系统（RSs）中的应用，特别是在提高样本效率方面的潜力。论文提出了一种名为Laser的框架，该框架利用LLMs来提升推荐系统的性能，即使在有限的训练数据下也能实现高性能。这与LLM应用分类相符，因为它关注的是LLMs在实际应用中的效果和改进，而不是LLMs的理论研究或Agent的设计与实现。` `推荐系统`

> Large Language Models Make Sample-Efficient Recommender Systems

# 摘要

> 大型语言模型（LLMs）在NLP领域取得了显著进展，其生成的文本在多种任务中与人类语言极为相似，为推荐系统（RSs）的应用带来了新机遇。本文聚焦于LLM增强推荐系统的样本效率，即在有限训练数据下实现高性能的能力。传统推荐模型（CRMs）因特征和交互的稀疏性，常需大量数据。我们提出并验证了核心观点：大型语言模型能提升推荐系统的样本效率。为此，我们设计了Laser框架，从两方面证明：（1）LLMs自身就是高效的样本推荐器；（2）作为特征和编码的生成者，LLMs使CRMs更高效。实验结果显示，Laser在两个公开数据集上，仅需少量样本即可与全量训练的CRMs媲美甚至超越，彰显了其样本效率的优越性。

> Large language models (LLMs) have achieved remarkable progress in the field of natural language processing (NLP), demonstrating remarkable abilities in producing text that resembles human language for various tasks. This opens up new opportunities for employing them in recommender systems (RSs). In this paper, we specifically examine the sample efficiency of LLM-enhanced recommender systems, which pertains to the model's capacity to attain superior performance with a limited quantity of training data. Conventional recommendation models (CRMs) often need a large amount of training data because of the sparsity of features and interactions. Hence, we propose and verify our core viewpoint: Large Language Models Make Sample-Efficient Recommender Systems. We propose a simple yet effective framework (i.e., Laser) to validate the viewpoint from two aspects: (1) LLMs themselves are sample-efficient recommenders; and (2) LLMs, as feature generators and encoders, make CRMs more sample-efficient. Extensive experiments on two public datasets show that Laser requires only a small fraction of training samples to match or even surpass CRMs that are trained on the entire training set, demonstrating superior sample efficiency.

![大型语言模型赋能推荐系统，使其在样本利用上更为高效。](../../../paper_images/2406.02368/x1.png)

[Arxiv](https://arxiv.org/abs/2406.02368)