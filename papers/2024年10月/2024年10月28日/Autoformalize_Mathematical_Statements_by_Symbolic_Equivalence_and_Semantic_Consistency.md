# 借助符号等价和语义一致性来对数学陈述进行自动形式化

发布时间：2024年10月28日

`LLM应用`

> Autoformalize Mathematical Statements by Symbolic Equivalence and Semantic Consistency

# 摘要

> 自动形式化，也就是把自然语言描述自动转化为形式语言的任务，在众多领域，尤其是数学领域，是个重大挑战。大型语言模型（LLMs）的最新进展展现出它们能将竞赛级别的数学问题形式化的出色能力。不过，我们发现 LLM 生成的形式化中，pass@1 和 pass@k 的准确率有较大差距。为缩小这一差距，我们推出一个全新框架，基于符号等价和语义一致性这两种互补的自一致性方法，对 k 个自动形式化候选结果进行打分并选出最佳结果。具体而言，符号等价借助自动定理证明器来辨别自动形式化候选结果间的逻辑同质性，语义一致性通过将候选结果非正式化，并计算原始文本与非正式化文本嵌入的相似度，来评估原始含义的保留情况。我们在 MATH 和 miniF2F 数据集上开展的大量实验表明，我们的方法大幅提升了自动形式化的准确率，在各类 LLMs 和基线方法中实现了高达 0.22 - 1.35 倍的相对提升。

> Autoformalization, the task of automatically translating natural language descriptions into a formal language, poses a significant challenge across various domains, especially in mathematics. Recent advancements in large language models (LLMs) have unveiled their promising capabilities to formalize even competition-level math problems. However, we observe a considerable discrepancy between pass@1 and pass@k accuracies in LLM-generated formalizations. To address this gap, we introduce a novel framework that scores and selects the best result from k autoformalization candidates based on two complementary self-consistency methods: symbolic equivalence and semantic consistency. Elaborately, symbolic equivalence identifies the logical homogeneity among autoformalization candidates using automated theorem provers, and semantic consistency evaluates the preservation of the original meaning by informalizing the candidates and computing the similarity between the embeddings of the original and informalized texts. Our extensive experiments on the MATH and miniF2F datasets demonstrate that our approach significantly enhances autoformalization accuracy, achieving up to 0.22-1.35x relative improvements across various LLMs and baseline methods.

[Arxiv](https://arxiv.org/abs/2410.20936)