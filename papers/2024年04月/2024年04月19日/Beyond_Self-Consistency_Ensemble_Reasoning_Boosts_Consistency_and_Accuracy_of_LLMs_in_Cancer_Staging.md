# 突破自我一致性：通过集成推理，大型语言模型在癌症分期中的表现不仅更加一致，而且准确性也得到了显著提升。

发布时间：2024年04月19日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在医疗领域的应用，特别是在处理临床报告中的癌症分期信息方面。通过引入集成推理策略来增强模型生成的连贯性，研究展示了LLMs在提高临床信息处理准确性和一致性方面的潜力。这与LLM应用分类相符，因为它关注的是LLMs在特定领域（医疗）的实际应用和改进。` `临床决策支持`

> Beyond Self-Consistency: Ensemble Reasoning Boosts Consistency and Accuracy of LLMs in Cancer Staging

# 摘要

> 随着大型语言模型（LLMs）技术的进步，医疗领域开始广泛采用这些模型，以处理包含重要临床信息的非结构化笔记。尽管临床报告中的癌症分期信息需要通过自然语言处理技术提取，但面向临床的LLMs的发展使得这一过程变得更为简便。通过思维链等提示方法，预训练的LLMs能更可信地生成响应。自一致性虽提升了模型性能，却常导致推理路径间生成的不一致。为此，本研究提出了一种集成推理策略，旨在增强模型生成的连贯性。我们利用一个公开的临床大型语言模型，从实际病理报告中准确判定癌症阶段，结果显示集成推理方法有效提升了LLM在癌症分期判定上的一致性与性能，凸显了这些模型在临床及其他对可靠性和可信度要求极高的领域中的应用潜力。

> Advances in large language models (LLMs) have encouraged their adoption in the healthcare domain where vital clinical information is often contained in unstructured notes. Cancer staging status is available in clinical reports, but it requires natural language processing to extract the status from the unstructured text. With the advance in clinical-oriented LLMs, it is promising to extract such status without extensive efforts in training the algorithms. Prompting approaches of the pre-trained LLMs that elicit a model's reasoning process, such as chain-of-thought, may help to improve the trustworthiness of the generated responses. Using self-consistency further improves model performance, but often results in inconsistent generations across the multiple reasoning paths. In this study, we propose an ensemble reasoning approach with the aim of improving the consistency of the model generations. Using an open access clinical large language model to determine the pathologic cancer stage from real-world pathology reports, we show that the ensemble reasoning approach is able to improve both the consistency and performance of the LLM in determining cancer stage, thereby demonstrating the potential to use these models in clinical or other domains where reliability and trustworthiness are critical.

![突破自我一致性：通过集成推理，大型语言模型在癌症分期中的表现不仅更加一致，而且准确性也得到了显著提升。](../../../paper_images/2404.13149/brca-t14-type-changes.png)

![突破自我一致性：通过集成推理，大型语言模型在癌症分期中的表现不仅更加一致，而且准确性也得到了显著提升。](../../../paper_images/2404.13149/brca-n03-type-changes.png)

[Arxiv](https://arxiv.org/abs/2404.13149)