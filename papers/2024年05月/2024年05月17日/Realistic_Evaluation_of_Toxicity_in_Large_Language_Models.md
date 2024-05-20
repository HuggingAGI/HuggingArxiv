# 大型语言模型中毒性的真实评估

发布时间：2024年05月17日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在处理毒性和偏见方面的挑战，并提出了一个名为全面工程化毒性（TET）数据集的新工具，用于评估和揭示这些模型在特定提示下的潜在毒性问题。虽然这项工作涉及到对LLMs的评估和改进，但其核心在于应用层面的挑战和解决方案，即如何通过特定的数据集来评估和改善LLMs的性能，以防止有害内容的生成。因此，这篇论文更适合归类于LLM应用，因为它主要探讨了LLMs在实际应用中的问题和解决方案，而不是深入理论研究或Agent的设计与实现。` `数据集` `模型评估`

> Realistic Evaluation of Toxicity in Large Language Models

# 摘要

> 大型语言模型（LLMs）已深入我们的工作和日常生活，但它们的一个致命弱点是：虽然海量数据赋予了它们广博的知识，却也让它们暴露于不可避免的毒性和偏见之中。尽管多数LLMs设有防御机制以阻止有害内容的生成，但这些防护措施却能轻易通过精心设计的提示被绕过。本文中，我们推出了全新的全面工程化毒性（TET）数据集，其中包含精心设计的提示，旨在破解这些模型的保护层。通过详尽的评估，我们展示了TET在为多个主流LLMs的毒性意识评估提供严格基准中的核心作用：它揭示了在常规提示下可能被忽视的LLMs中的毒性问题，从而揭示了它们行为中更为微妙的缺陷。

> Large language models (LLMs) have become integral to our professional workflows and daily lives. Nevertheless, these machine companions of ours have a critical flaw: the huge amount of data which endows them with vast and diverse knowledge, also exposes them to the inevitable toxicity and bias. While most LLMs incorporate defense mechanisms to prevent the generation of harmful content, these safeguards can be easily bypassed with minimal prompt engineering. In this paper, we introduce the new Thoroughly Engineered Toxicity (TET) dataset, comprising manually crafted prompts designed to nullify the protective layers of such models. Through extensive evaluations, we demonstrate the pivotal role of TET in providing a rigorous benchmark for evaluation of toxicity awareness in several popular LLMs: it highlights the toxicity in the LLMs that might remain hidden when using normal prompts, thus revealing subtler issues in their behavior.

![大型语言模型中毒性的真实评估](../../../paper_images/2405.10659/x1.png)

![大型语言模型中毒性的真实评估](../../../paper_images/2405.10659/x2.png)

![大型语言模型中毒性的真实评估](../../../paper_images/2405.10659/x3.png)

![大型语言模型中毒性的真实评估](../../../paper_images/2405.10659/x4.png)

![大型语言模型中毒性的真实评估](../../../paper_images/2405.10659/x5.png)

[Arxiv](https://arxiv.org/abs/2405.10659)