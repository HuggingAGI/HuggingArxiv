# LAMPO：将大型语言模型视为少样本序数分类的偏好机器

发布时间：2024年08月06日

`LLM应用` `电影评论` `社交媒体`

> LAMPO: Large Language Models as Preference Machines for Few-shot Ordinal Classification

# 摘要

> 我们推出了 LAMPO，一种新颖的方法，利用大型语言模型 (LLM) 来高效解决少样本多类别序数分类任务。不同于传统方法，LAMPO 将 LLM 视为偏好机器，通过相对比较测试实例与每个演示示例来做出决策，并采用自监督方法将这些比较结果整合为最终序数决策。这一创新有效克服了先前方法中的上下文长度限制、排序偏差及绝对点估计难题。在七个公共数据集上的实验显示，LAMPO 在电影评论分析、仇恨言论检测等多种应用中表现卓越，某些情况下性能提升超过 20%。此外，LAMPO 作为 LLM 上的非参数应用，无需访问模型内部状态，如嵌入，展现了其对黑盒 LLM 的支持能力，为该领域增添了新的研究视角。

> We introduce LAMPO, a novel paradigm that leverages Large Language Models (LLMs) for solving few-shot multi-class ordinal classification tasks. Unlike conventional methods, which concatenate all demonstration examples with the test instance and prompt LLMs to produce the pointwise prediction, our framework uses the LLM as a preference machine that makes a relative comparative decision between the test instance and each demonstration. A self-supervised method is then introduced to aggregate these binary comparisons into the final ordinal decision. LAMPO addresses several limitations inherent in previous methods, including context length constraints, ordering biases, and challenges associated with absolute point-wise estimation. Extensive experiments on seven public datasets demonstrate LAMPO's remarkably competitive performance across a diverse spectrum of applications (e.g., movie review analysis and hate speech detection). Notably, in certain applications, the improvement can be substantial, exceeding 20% in an absolute term. Moreover, we believe LAMPO represents an interesting addition to the non-parametric application layered on top of LLMs, as it supports black-box LLMs without necessitating the outputting of LLM's internal states (e.g., embeddings), as seen in previous approaches.

[Arxiv](https://arxiv.org/abs/2408.03359)