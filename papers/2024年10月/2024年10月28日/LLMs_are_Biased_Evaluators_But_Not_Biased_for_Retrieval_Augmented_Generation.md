# LLMs 作为评估者存在偏差，但在检索增强生成方面不存在偏差。

发布时间：2024年10月28日

`RAG` `语言模型` `检索增强生成`

> LLMs are Biased Evaluators But Not Biased for Retrieval Augmented Generation

# 摘要

> 近期研究显示，大型语言模型（LLMs）在评估任务中存在明显偏差，尤其偏爱自身生成的内容。但这种偏差在面向事实的任务中，特别是在检索增强生成（RAG）框架下（该框架中关键词提取和事实准确性比文体要素更重要）的具体表现程度尚不明确。我们的研究通过模拟 RAG 框架的两个关键阶段来填补这一知识空缺。第一阶段，我们考察人类创作的段落与模型生成的段落的适用性，模拟逐点重排序过程。第二阶段进行成对的阅读理解测试来模拟生成过程。与之前在评级任务中发现的自我偏好结果不同，我们的研究表明在 RAG 框架中不存在显著的自我偏好效应。相反，我们发现即便没有先验知识，事实准确性也对 LLMs 的输出有显著影响。我们的研究为正在进行的关于 LLMs 偏差及其对基于 RAG 系统的影响的讨论做出了贡献，所提供的见解或许能为更强大且无偏差的 LLMs 系统的开发提供参考。

> Recent studies have demonstrated that large language models (LLMs) exhibit significant biases in evaluation tasks, particularly in preferentially rating and favoring self-generated content. However, the extent to which this bias manifests in fact-oriented tasks, especially within retrieval-augmented generation (RAG) frameworks-where keyword extraction and factual accuracy take precedence over stylistic elements-remains unclear. Our study addresses this knowledge gap by simulating two critical phases of the RAG framework. In the first phase, we access the suitability of human-authored versus model-generated passages, emulating the pointwise reranking process. The second phase involves conducting pairwise reading comprehension tests to simulate the generation process. Contrary to previous findings indicating a self-preference in rating tasks, our results reveal no significant self-preference effect in RAG frameworks. Instead, we observe that factual accuracy significantly influences LLMs' output, even in the absence of prior knowledge. Our research contributes to the ongoing discourse on LLM biases and their implications for RAG-based system, offering insights that may inform the development of more robust and unbiased LLM systems.

[Arxiv](https://arxiv.org/abs/2410.20833)