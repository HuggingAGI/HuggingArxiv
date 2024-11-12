# SCAR：用于大型语言模型中概念检测和引导的稀疏条件自编码器

发布时间：2024年11月11日

`LLM应用` `伦理与安全`

> SCAR: Sparse Conditioned Autoencoders for Concept Detection and Steering in LLMs

# 摘要

> 大型语言模型（LLMs）在生成类人文本方面展现出了非凡的能力，但它们的输出可能与用户的需求不一致，甚至会产生有害内容。本文提出了一种在生成之前检测和引导诸如毒性等概念的新方法。我们引入了稀疏条件自编码器（SCAR），这是一个经过单独训练的模块，扩展了原本未受影响的 LLM。SCAR 确保了完全的可引导性，能够朝向或远离概念（例如有毒内容），同时不影响模型在标准评估基准上的文本生成质量。我们通过各种概念，包括毒性、安全性和写作风格一致性，展示了我们方法的有效应用。因此，这项工作为控制 LLM 的生成建立了一个强大的框架，确保它们在现实世界的应用中得到合乎伦理和安全的部署。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in generating human-like text, but their output may not be aligned with the user or even produce harmful content. This paper presents a novel approach to detect and steer concepts such as toxicity before generation. We introduce the Sparse Conditioned Autoencoder (SCAR), a single trained module that extends the otherwise untouched LLM. SCAR ensures full steerability, towards and away from concepts (e.g., toxic content), without compromising the quality of the model's text generation on standard evaluation benchmarks. We demonstrate the effective application of our approach through a variety of concepts, including toxicity, safety, and writing style alignment. As such, this work establishes a robust framework for controlling LLM generations, ensuring their ethical and safe deployment in real-world applications.

[Arxiv](https://arxiv.org/abs/2411.07122)