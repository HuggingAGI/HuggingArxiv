# Missci：揭秘科学误解中的谬论

发布时间：2024年06月05日

`LLM应用

这篇论文主要关注的是如何利用大型语言模型（LLMs）来自动反驳社交媒体上的健康谣言，特别是通过解释谣言如何错误地从科学文献中推导出来。论文介绍了名为Missci的新论证理论模型，并提供了一个新的数据集，用于检测错误引用生物医学文献的现实世界谣言。研究的重点是评估LLMs在零-shot设置下的关键推理能力，并探讨了不同谬误类别细节提示的影响。因此，这篇论文属于LLM应用类别，因为它展示了LLMs在特定应用场景（即自动事实核查和谬误检测）中的实际应用和效果评估。` `健康谣言检测` `生物医学`

> Missci: Reconstructing Fallacies in Misrepresented Science

# 摘要

> 社交媒体上的健康谣言可能导致决策失误和现实风险。这些谣言常错误引用科学文献以增加可信度。为了自动反驳这些谣言，系统需解释谣言如何错误地从文献中推导。现有的自动事实核查或谬误检测方法未评估谣言与引用文献之间的证据误用，这是检测不匹配的关键。为此，我们推出了Missci，一种新的论证理论模型，专用于谬误推理，并附带一个新数据集，用于检测错误引用生物医学文献的现实世界谣言。与以往数据集不同，Missci关注文献内容与谣言间的隐含谬误，并要求模型不仅识别谬误，还要解释其推理。我们用Missci测试大型语言模型（LLMs）在零-shot设置下的关键推理能力，评估了两个代表性LLMs及不同谬误类别细节提示的影响。实验和人类评估显示GPT 4表现良好，但也揭示了任务的挑战性。

> Health-related misinformation on social networks can lead to poor decision-making and real-world dangers. Such misinformation often misrepresents scientific publications and cites them as "proof" to gain perceived credibility. To effectively counter such claims automatically, a system must explain how the claim was falsely derived from the cited publication. Current methods for automated fact-checking or fallacy detection neglect to assess the (mis)used evidence in relation to misinformation claims, which is required to detect the mismatch between them. To address this gap, we introduce Missci, a novel argumentation theoretical model for fallacious reasoning together with a new dataset for real-world misinformation detection that misrepresents biomedical publications. Unlike previous fallacy detection datasets, Missci (i) focuses on implicit fallacies between the relevant content of the cited publication and the inaccurate claim, and (ii) requires models to verbalize the fallacious reasoning in addition to classifying it. We present Missci as a dataset to test the critical reasoning abilities of large language models (LLMs), that are required to reconstruct real-world fallacious arguments, in a zero-shot setting. We evaluate two representative LLMs and the impact of different levels of detail about the fallacy classes provided to the LLM via prompts. Our experiments and human evaluation show promising results for GPT 4, while also demonstrating the difficulty of this task.

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x1.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x2.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x3.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x4.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x5.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/t1-highlight.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/annotation-claim.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/annotation-fallacies.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/annotation-study-credibilitypng.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x6.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x7.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x8.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x9.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x10.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x11.png)

![Missci：揭秘科学误解中的谬论](../../../paper_images/2406.03181/x12.png)

[Arxiv](https://arxiv.org/abs/2406.03181)