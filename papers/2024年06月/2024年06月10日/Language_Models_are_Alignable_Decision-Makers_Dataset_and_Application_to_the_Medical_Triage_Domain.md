# 语言模型：医疗分诊领域的可对齐决策者与应用探索

发布时间：2024年06月10日

`Agent

理由：这篇论文主要介绍了一个专为医疗分诊决策设计的数据集，并开发了一套软件框架，利用大型语言模型（LLMs）来模拟伦理决策者的角色，通过零-shot提示技术使其决策与不同的决策者属性（DMAs）相协调。这表明论文的核心在于构建和应用一个能够根据特定属性（如伦理原则）进行决策的智能系统，即Agent。虽然涉及到了LLM的应用，但重点在于Agent的设计和实现，以及其在特定决策环境中的应用，因此更适合归类为Agent。` `人工智能`

> Language Models are Alignable Decision-Makers: Dataset and Application to the Medical Triage Domain

# 摘要

> 在复杂的决策环境中，专家间的意见分歧屡见不鲜，因为正确的答案并非唯一。这些决策往往受到多种属性的影响，这些属性能够描绘出个人决策的特征。我们推出了一款专为医疗分诊决策设计的新数据集，其中包含了62个场景，涵盖了六种不同的决策者属性（DMAs），如公平与道德应得等伦理原则。我们开发了一套创新的软件框架，利用这些DMAs来实现与人类价值观相符的决策，为构建更为可靠的AI系统奠定了基础。特别地，我们展示了大型语言模型（LLMs）如何扮演伦理决策者的角色，并通过零-shot提示技术使其决策与不同的DMAs相协调。我们的研究涵盖了多种开源模型，包括Falcon、Mistral和Llama 2等，它们在规模和训练方法上各有不同。此外，我们还提出了一种新的加权自一致性方法，显著提升了整体性能。这些发现为LLMs在可调整决策领域的应用开辟了新的研究路径。数据集及开源软件已公开发布于：https://github.com/ITM-Kitware/llm-alignable-dm。

> In difficult decision-making scenarios, it is common to have conflicting opinions among expert human decision-makers as there may not be a single right answer. Such decisions may be guided by different attributes that can be used to characterize an individual's decision. We introduce a novel dataset for medical triage decision-making, labeled with a set of decision-maker attributes (DMAs). This dataset consists of 62 scenarios, covering six different DMAs, including ethical principles such as fairness and moral desert. We present a novel software framework for human-aligned decision-making by utilizing these DMAs, paving the way for trustworthy AI with better guardrails. Specifically, we demonstrate how large language models (LLMs) can serve as ethical decision-makers, and how their decisions can be aligned to different DMAs using zero-shot prompting. Our experiments focus on different open-source models with varying sizes and training techniques, such as Falcon, Mistral, and Llama 2. Finally, we also introduce a new form of weighted self-consistency that improves the overall quantified performance. Our results provide new research directions in the use of LLMs as alignable decision-makers. The dataset and open-source software are publicly available at: https://github.com/ITM-Kitware/llm-alignable-dm.

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x1.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x2.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x3.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x4.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x5.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x6.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x7.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/x8.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/top-5-high-alignment.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/protocol_focus__all_algorithms.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/moral_deservingness__all_algorithms.png)

![语言模型：医疗分诊领域的可对齐决策者与应用探索](../../../paper_images/2406.06435/fairness__all_algorithms.png)

[Arxiv](https://arxiv.org/abs/2406.06435)