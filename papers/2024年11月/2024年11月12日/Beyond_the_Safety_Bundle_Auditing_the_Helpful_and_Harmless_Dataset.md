# 超越安全捆绑：审计有用且无害的数据集

发布时间：2024年11月12日

`LLM应用` `语言模型` `安全技术`

> Beyond the Safety Bundle: Auditing the Helpful and Harmless Dataset

# 摘要

> 为了减轻大型语言模型（LLMs）的危害，从人类反馈中学习（LHF）已被用于引导 LLMs 生成既危害较小又更有帮助的输出。尽管 LHF 在实践中被广泛采用，但这种反馈的质量及其作为安全缓解技术的有效性仍不清楚。本研究通过审核 Anthropic 广泛使用的“有用且无害（HH）”数据集来解决这些问题。我们的工作包括：（1）通过手动和自动评估对数据集的内容进行彻底调查；（2）实验证明数据集对模型安全性的影响；（3）分析引用此数据集的 100 篇最具影响力的论文。通过我们的审核，我们展示了在 HH 数据集中发现的概念化失败和质量问题如何通过导致不同人口群体的不同安全行为而造成额外的危害。我们的研究结果强调了在 LLMs 中需要更细致、对上下文敏感的安全缓解方法。

> In an effort to mitigate the harms of large language models (LLMs), learning from human feedback (LHF) has been used to steer LLMs towards outputs that are intended to be both less harmful and more helpful. Despite the widespread adoption of LHF in practice, the quality of this feedback and its effectiveness as a safety mitigation technique remain unclear. This study addresses these issues by auditing the widely-used Helpful and Harmless (HH) dataset by Anthropic. Our work includes: (1) a thorough investigation of the dataset's content through both manual and automated evaluation; (2) experiments demonstrating the dataset's impact on models' safety; and (3) an analysis of the 100 most influential papers citing this dataset. Through our audit, we showcase how conceptualization failures and quality issues identified in the HH dataset can create additional harms by leading to disparate safety behaviors across demographic groups. Our findings highlight the need for more nuanced, context-sensitive approaches to safety mitigation in LLMs.

[Arxiv](https://arxiv.org/abs/2411.08243)