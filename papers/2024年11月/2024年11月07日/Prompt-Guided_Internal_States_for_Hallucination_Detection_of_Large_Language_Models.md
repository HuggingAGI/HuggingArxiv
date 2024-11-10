# 提示引导的内部状态用于大型语言模型的幻觉检测

发布时间：2024年11月07日

`LLM应用` `语言模型` `幻觉检测`

> Prompt-Guided Internal States for Hallucination Detection of Large Language Models

# 摘要

> 大型语言模型（LLMs）在不同领域的各种任务中展现出了非凡的能力。然而，它们有时会生成逻辑连贯但事实上不正确或具有误导性的响应，这被称为 LLM 幻觉。数据驱动的监督方法通过利用 LLMs 的内部状态来训练幻觉检测器，但在特定领域训练的检测器往往难以很好地推广到其他领域。在本文中，我们旨在仅使用域内数据来提高监督检测器的跨域性能。我们提出了一个新颖的框架，即用于 LLM 幻觉检测的提示引导内部状态，简称 PRISM。通过利用适当的提示来引导 LLMs 内部状态中与文本真实性相关的结构变化，我们使这种结构在来自不同领域的文本中更加突出和一致。我们将我们的框架与现有的幻觉检测方法相结合，并在来自不同领域的数据集上进行了实验。实验结果表明，我们的框架显著提高了现有幻觉检测方法的跨域泛化能力。

> Large Language Models (LLMs) have demonstrated remarkable capabilities across a variety of tasks in different domains. However, they sometimes generate responses that are logically coherent but factually incorrect or misleading, which is known as LLM hallucinations. Data-driven supervised methods train hallucination detectors by leveraging the internal states of LLMs, but detectors trained on specific domains often struggle to generalize well to other domains. In this paper, we aim to enhance the cross-domain performance of supervised detectors with only in-domain data. We propose a novel framework, prompt-guided internal states for hallucination detection of LLMs, namely PRISM. By utilizing appropriate prompts to guide changes in the structure related to text truthfulness within the LLM's internal states, we make this structure more salient and consistent across texts from different domains. We integrated our framework with existing hallucination detection methods and conducted experiments on datasets from different domains. The experimental results indicate that our framework significantly enhances the cross-domain generalization of existing hallucination detection methods.

[Arxiv](https://arxiv.org/abs/2411.04847)