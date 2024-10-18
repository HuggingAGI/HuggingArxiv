# 通过自我提升，推动大型语言模型的归因技术进步。

发布时间：2024年10月17日

`LLM应用` `信息检索`

> Advancing Large Language Model Attribution through Self-Improving

# 摘要

> 教会大型语言模型 (LLM) 生成带有引用来源的文本，能有效减少幻觉，提升信息检索系统的可信度。然而，这需要高质量的归属数据，成本高且耗时。借鉴近期无需人工标注的自改进技术，我们推出了 START，一个自学习归属框架，旨在迭代提升 LLM 的归属能力。首先，为避免初始监督信号不足导致的停滞，START 让模型自我生成训练数据进行预热。随后，通过迭代利用模型自身响应构建的细粒度偏好信号，START 进一步强化了生成内容的稳健性、全面性和可归属性。实验表明，在长篇问答和多步骤推理任务中，START 平均性能提升了 25.13%，且无需人工标注或更高级模型。深入分析发现，START 在整合多源信息方面尤为出色。

> Teaching large language models (LLMs) to generate text with citations to evidence sources can mitigate hallucinations and enhance verifiability in information-seeking systems. However, improving this capability requires high-quality attribution data, which is costly and labor-intensive. Inspired by recent advances in self-improvement that enhance LLMs without manual annotation, we present START, a Self-Taught AttRibuTion framework for iteratively improving the attribution capability of LLMs. First, to prevent models from stagnating due to initially insufficient supervision signals, START leverages the model to self-construct synthetic training data for warming up. To further self-improve the model's attribution ability, START iteratively utilizes fine-grained preference supervision signals constructed from its sampled responses to encourage robust, comprehensive, and attributable generation. Experiments on three open-domain question-answering datasets, covering long-form QA and multi-step reasoning, demonstrate significant performance gains of 25.13% on average without relying on human annotations and more advanced models. Further analysis reveals that START excels in aggregating information across multiple sources.

[Arxiv](https://arxiv.org/abs/2410.13298)