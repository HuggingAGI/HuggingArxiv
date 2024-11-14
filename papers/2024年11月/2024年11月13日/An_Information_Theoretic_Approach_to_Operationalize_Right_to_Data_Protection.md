# 一种将数据保护权付诸实践的信息理论方法

发布时间：2024年11月13日

`LLM应用` `数据保护`

> An Information Theoretic Approach to Operationalize Right to Data Protection

# 摘要

> 不加区分地进行数据抓取以微调语言模型（LMs）的广泛做法引发了重大的法律和伦理问题，特别是在遵守数据保护法（如《通用数据保护条例》（GDPR））方面。这种做法经常导致未经授权使用个人信息，在学术界和监管界引发了越来越多的争论。最近的研究引入了生成不可学习数据集的概念（通过向干净数据添加不易察觉的噪声），使得基础模型在训练期间损失较低，但无法推广到未见过的测试环境。尽管在一定程度上有效，但这些方法主要是为图像设计的，并受到一些实际限制，例如需要了解目标模型。为此，我们引入了 RegText，这是一个向自然语言数据集注入不易察觉的虚假关联的框架，在不影响语义内容的情况下有效地使其不可学习。我们通过对小型和大型 LMs 的严格实证分析证明了 RegText 的实用性。值得注意的是，RegText 可以限制像 GPT-4o 和 Llama 这样的新模型在我们生成的数据上学习，导致它们的测试准确率相对于零样本性能下降，为生成不可学习的文本以保护公共数据铺平了道路。

> The widespread practice of indiscriminate data scraping to fine-tune language models (LMs) raises significant legal and ethical concerns, particularly regarding compliance with data protection laws such as the General Data Protection Regulation (GDPR). This practice often results in the unauthorized use of personal information, prompting growing debate within the academic and regulatory communities. Recent works have introduced the concept of generating unlearnable datasets (by adding imperceptible noise to the clean data), such that the underlying model achieves lower loss during training but fails to generalize to the unseen test setting. Though somewhat effective, these approaches are predominantly designed for images and are limited by several practical constraints like requiring knowledge of the target model. To this end, we introduce RegText, a framework that injects imperceptible spurious correlations into natural language datasets, effectively rendering them unlearnable without affecting semantic content. We demonstrate RegText's utility through rigorous empirical analysis of small and large LMs. Notably, RegText can restrict newer models like GPT-4o and Llama from learning on our generated data, resulting in a drop in their test accuracy compared to their zero-shot performance and paving the way for generating unlearnable text to protect public data.

[Arxiv](https://arxiv.org/abs/2411.08506)