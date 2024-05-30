# 利用内部一致性优化语言模型的推理校准

发布时间：2024年05月28日

`LLM理论

这篇论文主要关注大型语言模型（LLMs）在推理任务中的表现，特别是通过思维链（CoT）提示技术来激发语言化的推理过程。论文通过分析LLMs内部表示的动态，探讨了CoT推理的可靠性问题，并提出了内部一致性作为衡量模型自信度的新指标。此外，论文还提出了一种新方法来校准CoT推理，以提升推理性能。这些内容主要涉及LLMs的理论分析和改进，因此归类为LLM理论。` `人工智能`

> Calibrating Reasoning in Language Models with Internal Consistency

# 摘要

> 大型语言模型（LLMs）在推理任务中表现出色，得益于思维链（CoT）提示等技术，这些技术能激发语言化的推理过程。然而，LLMs生成的文本常含错误和矛盾，引发对其推理能力的质疑。本研究通过内部表示的视角，探究了LLMs中CoT推理的动态，发现尽管生成的理由提升了答案准确性，但模型中间层与最终层的内部表示存在不一致，可能影响推理的可靠性。为此，我们提出内部一致性作为衡量模型自信度的新指标，通过分析中间层预测的一致性。实证研究显示，内部一致性能有效区分正确与错误的推理路径。基于此发现，我们提出了一种新方法，通过增强高内部一致性的推理路径权重来校准CoT推理，显著提升了推理性能。深入分析揭示了不同层中注意力和前馈模块的特定模式，为理解内部不一致性提供了线索。综上所述，我们的研究展示了利用内部表示进行LLMs自我评估的潜力。

> Large language models (LLMs) have demonstrated impressive capabilities in various reasoning tasks, aided by techniques like chain-of-thought (CoT) prompting that elicits verbalized reasoning. However, LLMs often generate text with obvious mistakes and contradictions, raising doubts about their ability to robustly process and utilize generated rationales. In this work, we investigate CoT reasoning in LLMs through the lens of internal representations, focusing on how these representations are influenced by generated rationales. Our preliminary analysis reveals that while generated rationales improve answer accuracy, inconsistencies emerge between the model's internal representations in middle layers and those in final layers, potentially undermining the reliability of their reasoning processes. To address this, we propose internal consistency as a measure of the model's confidence by examining the agreement of latent predictions decoded from intermediate layers. Extensive empirical studies across different models and datasets demonstrate that internal consistency effectively distinguishes between correct and incorrect reasoning paths. Motivated by this, we propose a new approach to calibrate CoT reasoning by up-weighting reasoning paths with high internal consistency, resulting in a significant boost in reasoning performance. Further analysis uncovers distinct patterns in attention and feed-forward modules across layers, providing insights into the emergence of internal inconsistency. In summary, our results demonstrate the potential of using internal representations for self-evaluation of LLMs.

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x1.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x2.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x3.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x4.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x5.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x6.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x7.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x8.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x9.png)

![利用内部一致性优化语言模型的推理校准](../../../paper_images/2405.18711/x10.png)

[Arxiv](https://arxiv.org/abs/2405.18711)