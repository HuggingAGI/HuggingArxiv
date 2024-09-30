# 通过本体论上下文提升多模态大型语言模型的解释力

发布时间：2024年09月27日

`LLM应用` `人工智能`

> Enhancing Explainability in Multimodal Large Language Models Using Ontological Context

# 摘要

> 近期，多模态大型语言模型 (MLLM) 因其整合图像与文本等多模态任务的巨大潜力而备受关注，如图像描述和视觉问答。然而，这些模型在精准描述和解读特定视觉概念方面仍显不足，尤其在专业领域应用中。我们提出，将领域知识以本体形式融入 MLLM 能有效应对这些挑战。为此，我们设计了一个新框架，结合本体与 MLLM 来分类植物病害图像。该框架利用疾病本体中的植物病害概念，引导 MLLM 从图像中提取相关视觉信息，并借助本体推理能力进行疾病分类。确保模型准确运用这些疾病描述概念至关重要，而本体不仅能辅助验证，还能提升决策透明度与可信度，同时审查 MLLM 的注释是否与本体一致，并揭示错误原因。这一框架为融合本体与 MLLM 开辟了新路径，并通过实证研究得到了验证。

> Recently, there has been a growing interest in Multimodal Large Language Models (MLLMs) due to their remarkable potential in various tasks integrating different modalities, such as image and text, as well as applications such as image captioning and visual question answering. However, such models still face challenges in accurately captioning and interpreting specific visual concepts and classes, particularly in domain-specific applications. We argue that integrating domain knowledge in the form of an ontology can significantly address these issues. In this work, as a proof of concept, we propose a new framework that combines ontology with MLLMs to classify images of plant diseases. Our method uses concepts about plant diseases from an existing disease ontology to query MLLMs and extract relevant visual concepts from images. Then, we use the reasoning capabilities of the ontology to classify the disease according to the identified concepts. Ensuring that the model accurately uses the concepts describing the disease is crucial in domain-specific applications. By employing an ontology, we can assist in verifying this alignment. Additionally, using the ontology's inference capabilities increases transparency, explainability, and trust in the decision-making process while serving as a judge by checking if the annotations of the concepts by MLLMs are aligned with those in the ontology and displaying the rationales behind their errors. Our framework offers a new direction for synergizing ontologies and MLLMs, supported by an empirical study using different well-known MLLMs.

[Arxiv](https://arxiv.org/abs/2409.18753)