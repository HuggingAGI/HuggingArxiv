# 超越自我一致性：通过集成推理，大型语言模型在癌症分期任务中的一致性和准确度均得到显著提升。

发布时间：2024年04月19日

`LLM应用`

> Beyond Self-Consistency: Ensemble Reasoning Boosts Consistency and Accuracy of LLMs in Cancer Staging

# 摘要

> 大型语言模型（LLMs）的进展促进了其在医疗领域的应用，尤其是在处理包含关键临床信息的非结构化笔记时。癌症分期信息虽散见于临床报告，但借助自然语言处理技术，我们可以从这些文本中提取出相关信息。随着临床导向的LLMs技术的不断进步，我们有望无需复杂的算法训练就能高效提取这些信息。通过预训练的LLMs进行提示，例如采用“思维链”等方法，可以激发模型的推理过程，从而提升生成结果的可信性。此外，自我一致性的应用进一步提升了模型的表现，尽管这可能导致多条推理路径上的生成结果不一致。在本研究中，我们提出了一种集成推理方法，目的是提升模型生成结果的一致性。通过利用一个开放获取的临床大型语言模型，我们从实际病理报告中确定病理癌症分期，并证明了集成推理方法不仅提高了LLM在癌症分期判断上的一致性和准确性，也展示了这些模型在临床或其他对可靠性和信任度要求极高的领域中的潜在应用价值。

> Advances in large language models (LLMs) have encouraged their adoption in the healthcare domain where vital clinical information is often contained in unstructured notes. Cancer staging status is available in clinical reports, but it requires natural language processing to extract the status from the unstructured text. With the advance in clinical-oriented LLMs, it is promising to extract such status without extensive efforts in training the algorithms. Prompting approaches of the pre-trained LLMs that elicit a model's reasoning process, such as chain-of-thought, may help to improve the trustworthiness of the generated responses. Using self-consistency further improves model performance, but often results in inconsistent generations across the multiple reasoning paths. In this study, we propose an ensemble reasoning approach with the aim of improving the consistency of the model generations. Using an open access clinical large language model to determine the pathologic cancer stage from real-world pathology reports, we show that the ensemble reasoning approach is able to improve both the consistency and performance of the LLM in determining cancer stage, thereby demonstrating the potential to use these models in clinical or other domains where reliability and trustworthiness are critical.

![超越自我一致性：通过集成推理，大型语言模型在癌症分期任务中的一致性和准确度均得到显著提升。](../../../paper_images/2404.13149/brca-t14-type-changes.png)

![超越自我一致性：通过集成推理，大型语言模型在癌症分期任务中的一致性和准确度均得到显著提升。](../../../paper_images/2404.13149/brca-n03-type-changes.png)

[Arxiv](https://arxiv.org/abs/2404.13149)