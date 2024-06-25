# 大型语言模型展现诊断推理能力

发布时间：2023年07月17日

`LLM应用

理由：这篇论文探讨了如何将思维链提示法（DR-CoT）应用于医学推理，以提高大型语言模型在自动诊断中的准确率。这种方法通过模拟医生的推理过程，展示了大型语言模型在特定应用场景下的能力提升。因此，这篇论文属于LLM应用类别，因为它关注的是LLM在特定领域（医学诊断）的应用和优化。` `人工智能`

> Large Language Models Perform Diagnostic Reasoning

# 摘要

> 我们研究了如何将思维链提示法应用于医学推理，以实现自动诊断。借鉴医生的推理过程，我们开发了诊断推理思维链（DR-CoT）。实验结果显示，只需向大型语言模型（这些模型仅在通用文本上训练）展示两个DR-CoT示例，诊断准确率就能提升15%，相较于传统提示方法。在域外场景下，这一提升更是高达18%。这表明，通过恰当的提示，大型语言模型能够展现出专家级的推理能力。

> We explore the extension of chain-of-thought (CoT) prompting to medical reasoning for the task of automatic diagnosis. Motivated by doctors' underlying reasoning process, we present Diagnostic-Reasoning CoT (DR-CoT). Empirical results demonstrate that by simply prompting large language models trained only on general text corpus with two DR-CoT exemplars, the diagnostic accuracy improves by 15% comparing to standard prompting. Moreover, the gap reaches a pronounced 18% in out-domain settings. Our findings suggest expert-knowledge reasoning in large language models can be elicited through proper promptings.

[Arxiv](https://arxiv.org/abs/2307.08922)