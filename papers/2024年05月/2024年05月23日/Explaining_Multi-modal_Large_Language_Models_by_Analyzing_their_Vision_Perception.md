# 解析多模态大型语言模型的视觉感知能力

发布时间：2024年05月23日

`LLM应用

这篇论文探讨了多模态大型语言模型（MLLMs）的可解释性问题，并提出了一种通过优化图像嵌入来增强模型可解释性的方法。该研究通过构建一个新架构，结合了开放世界定位模型与MLLM，实现了从同一视觉嵌入中同时输出文本和对象定位信息。这种方法不仅提高了模型的透明度，还允许使用显著性图来解释每个输出标记，识别模型产生的幻觉，并通过语义对抗性扰动来评估模型的偏见。因此，这项工作属于LLM应用类别，因为它专注于改进和应用现有的LLM技术，以增强其在实际场景中的可用性和可靠性。` `人工智能` `计算机视觉`

> Explaining Multi-modal Large Language Models by Analyzing their Vision Perception

# 摘要

> 多模态大型语言模型（MLLMs）在跨模态内容理解和生成方面表现出色，但其可解释性仍是一大难题，限制了其在关键领域的应用。本研究提出了一种创新方法，通过优化图像嵌入部分来提升MLLMs的可解释性。我们结合了开放世界定位模型与MLLM，构建了一种新架构，能从同一视觉嵌入中同步输出文本和对象定位信息。这一架构极大地增强了模型的可解释性，使我们能够创造性地使用显著性图来阐释每个输出标记，识别模型产生的幻觉，并通过语义对抗性扰动来评估模型的偏见。

> Multi-modal Large Language Models (MLLMs) have demonstrated remarkable capabilities in understanding and generating content across various modalities, such as images and text. However, their interpretability remains a challenge, hindering their adoption in critical applications. This research proposes a novel approach to enhance the interpretability of MLLMs by focusing on the image embedding component. We combine an open-world localization model with a MLLM, thus creating a new architecture able to simultaneously produce text and object localization outputs from the same vision embedding. The proposed architecture greatly promotes interpretability, enabling us to design a novel saliency map to explain any output token, to identify model hallucinations, and to assess model biases through semantic adversarial perturbations.

[Arxiv](https://arxiv.org/abs/2405.14612)