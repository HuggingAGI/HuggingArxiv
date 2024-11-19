# 多模态大型语言模型的推理局限性。以 Bongard 问题为例展开研究

发布时间：2024年11月02日

`LLM应用` `视觉推理` `多模态模型`

> Reasoning Limitations of Multimodal Large Language Models. A case study of Bongard Problems

# 摘要

> 摘要
抽象视觉推理（AVR）包含一系列任务，其解决需要通过类比过程找出一组图片背后的共同概念，这与人类的智商测试类似。1968 年提出的邦加德问题（BPs）是此领域的一项基本挑战，主要因其需要融合视觉推理与语言描述。本研究提出一个问题：专为融合视觉与语言而设计的多模态大型语言模型（MLLMs）能否解决 BPs？为此，我们提出一系列适用于 MLLM 的多样化策略来应对 BPs，并研究了四个流行的专有 MLLM：GPT-4o、GPT-4 Turbo、Gemini 1.5 Pro 和 Claude 3.5 Sonnet，以及四个开放模型：InternVL2-8B、LLaVa-1.6 Mistral-7B、Phi-3.5-Vision 和 Pixtral 12B。上述 MLLM 在三个 BP 数据集上进行了对比：一组基于合成、几何图像的原始 BP 实例，以及两个基于真实世界图像的最新数据集，即 Bongard-HOI 和 Bongard-OpenWorld。实验揭示了 MLLM 在解决 BPs 时存在显著局限。特别是，尽管视觉上较为简单，但模型难以解决经典的合成 BPs 集合。尽管在 Bongard-HOI 和 Bongard-OpenWorld 所表达的真实世界概念上表现有所改善，但模型仍难以利用新信息改进预测，也难以有效利用对话上下文窗口。为探究合成与真实世界 AVR 领域性能差异的原因，我们提出 Bongard-RWR，这是一个新的 BP 数据集，由真实世界图像构成，将手工制作的合成 BPs 概念转化为真实世界概念。MLLM 在 Bongard-RWR 上的结果表明，它们在经典 BPs 上的不佳表现并非源于领域特殊性，而是反映了其一般性的 AVR 局限。

> Abstract visual reasoning (AVR) encompasses a suite of tasks whose solving requires the ability to discover common concepts underlying the set of pictures through an analogy-making process, similarly to human IQ tests. Bongard Problems (BPs), proposed in 1968, constitute a fundamental challenge in this domain mainly due to their requirement to combine visual reasoning and verbal description. This work poses a question whether multimodal large language models (MLLMs) inherently designed to combine vision and language are capable of tackling BPs. To this end, we propose a set of diverse MLLM-suited strategies to tackle BPs and examine four popular proprietary MLLMs: GPT-4o, GPT-4 Turbo, Gemini 1.5 Pro, and Claude 3.5 Sonnet, and four open models: InternVL2-8B, LLaVa-1.6 Mistral-7B, Phi-3.5-Vision, and Pixtral 12B. The above MLLMs are compared on three BP datasets: a set of original BP instances relying on synthetic, geometry-based images and two recent datasets based on real-world images, i.e., Bongard-HOI and Bongard-OpenWorld. The experiments reveal significant limitations of MLLMs in solving BPs. In particular, the models struggle to solve the classical set of synthetic BPs, despite their visual simplicity. Though their performance ameliorates on real-world concepts expressed in Bongard-HOI and Bongard-OpenWorld, the models still have difficulty in utilizing new information to improve their predictions, as well as utilizing a dialog context window effectively. To capture the reasons of performance discrepancy between synthetic and real-world AVR domains, we propose Bongard-RWR, a new BP dataset consisting of real-world images that translates concepts from hand-crafted synthetic BPs to real-world concepts. The MLLMs' results on Bongard-RWR suggest that their poor performance on classical BPs is not due to domain specificity but rather reflects their general AVR limitations.

[Arxiv](https://arxiv.org/abs/2411.01173)