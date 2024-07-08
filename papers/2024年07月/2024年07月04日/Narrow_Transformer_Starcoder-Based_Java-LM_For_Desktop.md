# 精简版 Transformer：基于 Starcoder 的 Java 语言模型，专为桌面设计

发布时间：2024年07月04日

`LLM应用` `软件开发` `人工智能`

> Narrow Transformer: Starcoder-Based Java-LM For Desktop

# 摘要

> 本文推出 NT-Java-1.1B，一款专为 Java 编程量身打造的开源代码语言模型，基于 StarCoderBase-1.1B 构建。NT-Java-1.1B 在 MultiPL-E Java 代码基准测试中表现卓越，超越了基础模型及同类模型。虽然大型通用预训练模型已用于提升 Python 等语言的编程能力，但针对其他编程语言的小型模型研究尚显不足。鉴于大型模型需依赖 GPU 等专用硬件，本文聚焦于开发 NT-Java-1.1B 及其量化版本，这些模型在性能上与 1.1B 规模的开放模型相媲美，非常适合桌面部署，为 NT 系列模型的多样化发展奠定了基础。

> This paper presents NT-Java-1.1B, an open-source specialized code language model built on StarCoderBase-1.1B, designed for coding tasks in Java programming. NT-Java-1.1B achieves state-of-the-art performance, surpassing its base model and majority of other models of similar size on MultiPL-E Java code benchmark. While there have been studies on extending large, generic pre-trained models to improve proficiency in specific programming languages like Python, similar investigations on small code models for other programming languages are lacking. Large code models require specialized hardware like GPUs for inference, highlighting the need for research into building small code models that can be deployed on developer desktops. This paper addresses this research gap by focusing on the development of a small Java code model, NT-Java-1.1B, and its quantized versions, which performs comparably to open models around 1.1B on MultiPL-E Java code benchmarks, making them ideal for desktop deployment. This paper establishes the foundation for specialized models across languages and sizes for a family of NT Models.

![精简版 Transformer：基于 Starcoder 的 Java 语言模型，专为桌面设计](../../../paper_images/2407.03941/event_scores.png)

[Arxiv](https://arxiv.org/abs/2407.03941)