# 自适应查询重写：通过对话答案的边际概率协调重写策略

发布时间：2024年06月16日

`RAG

理由：这篇论文主要关注的是查询重写技术，特别是在开放领域对话式问答（CQA）中的应用。提出的AdaQR框架通过使用少量标注数据和大型语言模型进行微调，以及通过直接偏好优化（DPO）来优化查询重写器，这些都是检索增强生成（RAG）技术的典型应用。RAG技术通常涉及使用大型语言模型来增强检索过程，这与论文中描述的方法相符。因此，这篇论文更适合归类于RAG。` `对话式问答` `信息检索`

> Adaptive Query Rewriting: Aligning Rewriters through Marginal Probability of Conversational Answers

# 摘要

> 查询重写技术在开放领域对话式问答（CQA）的段落检索中扮演着关键角色，它将对话查询转化为独立问题，以便现成检索器使用。尽管现有方法尝试在训练重写模型时考虑检索器的偏好，但它们往往依赖大量标注，如特定领域的重写和相关段落标签，这限制了模型的泛化与适应性。本文提出的AdaQR（自适应查询重写）框架，利用种子数据集中的少量重写标注，无需任何段落标签，训练查询重写模型。首先，我们使用种子数据集中约10%的重写标注对大型语言模型进行微调，生成每个查询的重写候选。随后，通过计算答案在前K个段落中的条件概率，评估检索器对这些候选的偏好，以此作为奖励，通过直接偏好优化（DPO）进一步优化重写器，整个过程无需依赖重写和检索的标注。实验证明，AdaQR不仅在有限标注下提升了重写器的领域内性能，还能有效适应跨领域数据集。

> Query rewriting is a crucial technique for passage retrieval in open-domain conversational question answering (CQA). It decontexualizes conversational queries into self-contained questions suitable for off-the-shelf retrievers. Existing methods attempt to incorporate retriever's preference during the training of rewriting models. However, these approaches typically rely on extensive annotations such as in-domain rewrites and/or relevant passage labels, limiting the models' generalization and adaptation capabilities. In this paper, we introduce AdaQR ($\textbf{Ada}$ptive $\textbf{Q}$uery $\textbf{R}$ewriting), a framework for training query rewriting models with limited rewrite annotations from seed datasets and completely no passage label. Our approach begins by fine-tuning compact large language models using only ~$10\%$ of rewrite annotations from the seed dataset training split. The models are then utilized to generate rewrite candidates for each query instance. A novel approach is then proposed to assess retriever's preference for these candidates by the probability of answers conditioned on the conversational query by marginalizing the Top-$K$ passages. This serves as the reward for optimizing the rewriter further using Direct Preference Optimization (DPO), a process free of rewrite and retrieval annotations. Experimental results on four open-domain CQA datasets demonstrate that AdaQR not only enhances the in-domain capabilities of the rewriter with limited annotation requirement, but also adapts effectively to out-of-domain datasets.

![自适应查询重写：通过对话答案的边际概率协调重写策略](../../../paper_images/2406.10991/x1.png)

![自适应查询重写：通过对话答案的边际概率协调重写策略](../../../paper_images/2406.10991/x2.png)

![自适应查询重写：通过对话答案的边际概率协调重写策略](../../../paper_images/2406.10991/x3.png)

![自适应查询重写：通过对话答案的边际概率协调重写策略](../../../paper_images/2406.10991/x4.png)

![自适应查询重写：通过对话答案的边际概率协调重写策略](../../../paper_images/2406.10991/x5.png)

[Arxiv](https://arxiv.org/abs/2406.10991)