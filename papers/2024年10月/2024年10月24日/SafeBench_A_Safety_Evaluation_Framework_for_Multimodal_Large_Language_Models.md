# SafeBench：多模态大型语言模型的安全评估框架

发布时间：2024年10月24日

`LLM应用` `语言模型` `安全评估`

> SafeBench: A Safety Evaluation Framework for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）正显示出强烈的安全担忧（例如，为用户生成有害输出），这促使了安全评估基准的发展。然而，我们观察到现有的 MLLMs 安全基准在查询质量和评估可靠性方面显示出局限性，限制了随着 MLLMs 不断发展对模型安全影响的检测。在本文中，我们提出了	oolns，一个为进行 MLLMs 安全评估而设计的综合框架。我们的框架由一个全面的有害查询数据集和一个自动评估协议组成，分别旨在解决上述限制。我们首先设计了一个自动安全数据集生成管道，在其中我们雇用了一组 LLM 评委来识别和分类对 MLLMs 最有害和多样化的风险场景；基于分类法，我们进一步要求这些评委相应地生成高质量的有害查询，从而产生了 23 个风险场景和 2300 个多模态有害查询对。在安全评估期间，我们从司法程序中的陪审团制度中获得灵感，并开创了采用协作 LLM 的陪审团审议评估协议，以评估目标模型是否表现出特定的有害行为，为内容安全风险提供可靠和无偏的评估。此外，我们的基准还可以扩展到音频模式，显示出高可扩展性和潜力。基于我们的框架，我们对 15 个广泛使用的开源 MLLMs 和 6 个商业 MLLMs（例如，GPT-4o，Gemini）进行了大规模实验，在其中我们揭示了现有 MLLMs 中普遍存在的安全问题，并实例化了关于 MLLM 安全性能的若干见解，如图像质量和参数大小。

> Multimodal Large Language Models (MLLMs) are showing strong safety concerns (e.g., generating harmful outputs for users), which motivates the development of safety evaluation benchmarks. However, we observe that existing safety benchmarks for MLLMs show limitations in query quality and evaluation reliability limiting the detection of model safety implications as MLLMs continue to evolve. In this paper, we propose \toolns, a comprehensive framework designed for conducting safety evaluations of MLLMs. Our framework consists of a comprehensive harmful query dataset and an automated evaluation protocol that aims to address the above limitations, respectively. We first design an automatic safety dataset generation pipeline, where we employ a set of LLM judges to recognize and categorize the risk scenarios that are most harmful and diverse for MLLMs; based on the taxonomy, we further ask these judges to generate high-quality harmful queries accordingly resulting in 23 risk scenarios with 2,300 multi-modal harmful query pairs. During safety evaluation, we draw inspiration from the jury system in judicial proceedings and pioneer the jury deliberation evaluation protocol that adopts collaborative LLMs to evaluate whether target models exhibit specific harmful behaviors, providing a reliable and unbiased assessment of content security risks. In addition, our benchmark can also be extended to the audio modality showing high scalability and potential. Based on our framework, we conducted large-scale experiments on 15 widely-used open-source MLLMs and 6 commercial MLLMs (e.g., GPT-4o, Gemini), where we revealed widespread safety issues in existing MLLMs and instantiated several insights on MLLM safety performance such as image quality and parameter size.

[Arxiv](https://arxiv.org/abs/2410.18927)