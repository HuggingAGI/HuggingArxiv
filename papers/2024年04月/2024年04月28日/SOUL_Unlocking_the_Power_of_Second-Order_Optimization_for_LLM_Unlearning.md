# SOUL：释放二阶优化在大型语言模型“忘却”过程中的潜力。

发布时间：2024年04月28日

`LLM理论` `数据法规` `人工智能伦理`

> SOUL: Unlocking the Power of Second-Order Optimization for LLM Unlearning

# 摘要

> 大型语言模型（LLMs）凸显了为了遵守数据法规和遵循道德的AI实践，必须具备有效的遗忘机制。LLM的遗忘目的是消除不需要的数据影响及其对模型能力的影响，同时保持模型在遗忘范围之外的实用性。尽管对LLM遗忘的研究兴趣日益增长，但选择优化器对LLM遗忘的影响尚未得到充分研究。本研究首次揭示了优化器选择在LLM遗忘中的重要性，并明确了二阶优化与影响遗忘之间的联系，后者是一种利用影响函数更新模型以去除数据影响的经典方法。基于此，我们提出了一个名为SOUL的二阶遗忘框架，该框架基于二阶裁剪随机优化（Sophia）的LLM训练方法构建。SOUL将传统的静态一次性模型更新方法转变为动态迭代的遗忘过程。我们的广泛实验表明，SOUL在多种遗忘任务、模型和评价指标上均优于常规的一阶方法，这预示着二阶优化在为LLM遗忘提供可扩展且易于实施的解决方案方面具有巨大潜力。

> Large Language Models (LLMs) have highlighted the necessity of effective unlearning mechanisms to comply with data regulations and ethical AI practices. LLM unlearning aims at removing undesired data influences and associated model capabilities without compromising utility out of the scope of unlearning. While interest in studying LLM unlearning is growing,the impact of the optimizer choice for LLM unlearning remains under-explored. In this work, we shed light on the significance of optimizer selection in LLM unlearning for the first time, establishing a clear connection between {second-order optimization} and influence unlearning (a classical approach using influence functions to update the model for data influence removal). This insight propels us to develop a second-order unlearning framework, termed SOUL, built upon the second-order clipped stochastic optimization (Sophia)-based LLM training method. SOUL extends the static, one-shot model update using influence unlearning to a dynamic, iterative unlearning process. Our extensive experiments show that SOUL consistently outperforms conventional first-order methods across various unlearning tasks, models, and metrics, suggesting the promise of second-order optimization in providing a scalable and easily implementable solution for LLM unlearning.

[Arxiv](https://arxiv.org/abs/2404.18239)