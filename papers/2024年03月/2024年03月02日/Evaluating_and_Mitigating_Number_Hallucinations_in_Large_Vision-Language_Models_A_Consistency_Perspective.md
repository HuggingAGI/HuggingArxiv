# 本研究从一致性视角出发，探讨并解决大型视觉-语言模型在处理过程中出现的数字幻觉现象。

发布时间：2024年03月02日

`Agent`

> Evaluating and Mitigating Number Hallucinations in Large Vision-Language Models: A Consistency Perspective

# 摘要

> 大型视觉语言模型在处理图文难题上表现出色，但同时也易受多种类型的幻觉错误影响。本文聚焦于其中一种新颖的类型——数字幻觉，即模型在识别图像中物体数量时出现偏差的现象。为此，我们创建了一个专门的数据集并运用评估标准来检测主流大型视觉语言模型（LVLMs）中存在的数字幻觉问题，结果显示这一问题相当普遍。我们进一步深度剖析数字幻觉，从内外两个关联角度审视其一致性缺失的问题，并断定这种不一致性正是引发数字幻觉的原因之一。据此，我们提议采用一致性训练策略来缓解这类幻觉问题，实验表明这种方法相比直接微调平均提升了8\%的表现效果。

> Large vision language models have demonstrated remarkable efficacy in addressing challenges related to both textual and visual content. Nevertheless, these models are susceptible to various hallucinations. In this paper, we focus on a new form of hallucination, specifically termed as number hallucination, which denotes instances where models fail to accurately identify the quantity of objects in an image. We establish a dataset and employ evaluation metrics to assess number hallucination, revealing a pronounced prevalence of this issue across mainstream large vision language models (LVLMs). Additionally, we delve into a thorough analysis of number hallucination, examining inner and outer inconsistency problem from two related perspectives. We assert that this inconsistency is one cause of number hallucination and propose a consistency training method as a means to alleviate such hallucination, which achieves an average improvement of 8\% compared with direct finetuning method.

[Arxiv](https://arxiv.org/abs/2403.01373)