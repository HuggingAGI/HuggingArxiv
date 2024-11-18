# 借助幻觉目标直接偏好优化来缓解多模态大型语言模型中的幻觉现象

发布时间：2024年11月15日

`LLM应用` `语言模型` `多模态`

> Mitigating Hallucination in Multimodal Large Language Model via Hallucination-targeted Direct Preference Optimization

# 摘要

> 多模态大型语言模型（MLLMs）常出现幻觉，这制约了其实际应用。近来，有研究尝试运用直接偏好优化（DPO）提升 MLLMs 的性能，然而在缓解幻觉方面的成效并不稳定。为更有效地处理这一问题，我们推出了针对幻觉的直接偏好优化（HDPO），以减少 MLLMs 中的幻觉。和以往方法不同，我们的方法从多种形式和成因入手解决幻觉问题。具体而言，针对 MLLM 产生幻觉的以下原因，我们开发了三类偏好对数据：（1）视觉能力欠佳；（2）长上下文生成；（3）多模态冲突。实验结果显示，我们的方法在多个幻觉评估数据集上表现出色，超越了多数最先进（SOTA）的方法，彰显了我们方法的潜力。消融研究和深入分析进一步验证了我们方法的有效性，并表明通过扩大规模有望实现进一步的优化。

> Multimodal Large Language Models (MLLMs) are known to hallucinate, which limits their practical applications. Recent works have attempted to apply Direct Preference Optimization (DPO) to enhance the performance of MLLMs, but have shown inconsistent improvements in mitigating hallucinations. To address this issue more effectively, we introduce Hallucination-targeted Direct Preference Optimization (HDPO) to reduce hallucinations in MLLMs. Unlike previous approaches, our method tackles hallucinations from their diverse forms and causes. Specifically, we develop three types of preference pair data targeting the following causes of MLLM hallucinations: (1) insufficient visual capabilities, (2) long context generation, and (3) multimodal conflicts. Experimental results demonstrate that our method achieves superior performance across multiple hallucination evaluation datasets, surpassing most state-of-the-art (SOTA) methods and highlighting the potential of our approach. Ablation studies and in-depth analyses further confirm the effectiveness of our method and suggest the potential for further improvements through scaling up.

[Arxiv](https://arxiv.org/abs/2411.10436)