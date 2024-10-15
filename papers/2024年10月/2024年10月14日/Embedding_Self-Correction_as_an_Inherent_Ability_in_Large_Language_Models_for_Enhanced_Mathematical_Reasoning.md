# 在大型语言模型中融入自我修正能力，以提升数学推理的精准度

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Embedding Self-Correction as an Inherent Ability in Large Language Models for Enhanced Mathematical Reasoning

# 摘要

> 在依赖数学推理的领域中，大型语言模型（LLMs）的准确推理能力至关重要。然而，LLMs在某些数学推理方面常遇难题，导致错误结果。为此，我们引入了自我修正链（CoSC）机制，使LLMs能自我验证和纠正。CoSC通过一系列自我修正阶段运行，逐步优化推理步骤，提高数学推理准确性。为低成本实现CoSC，我们采用两阶段微调方法，先使用GPT-4生成的种子数据建立初始能力，再通过自生成数据进一步增强。实验表明，CoSC显著提升了现有开源LLMs在数学数据集上的性能。特别是，CoSC-Code-34B在MATH数据集上取得了53.5%的分数，超越了ChatGPT、GPT-4及多模态LLMs等知名模型。

> Accurate mathematical reasoning with Large Language Models (LLMs) is crucial in revolutionizing domains that heavily rely on such reasoning. However, LLMs often encounter difficulties in certain aspects of mathematical reasoning, leading to flawed reasoning and erroneous results. To mitigate these issues, we introduce a novel mechanism, the Chain of Self-Correction (CoSC), specifically designed to embed self-correction as an inherent ability in LLMs, enabling them to validate and rectify their own results. The CoSC mechanism operates through a sequence of self-correction stages. In each stage, the LLMs generate a program to address a given problem, execute this program using program-based tools to obtain an output, subsequently verify this output. Based on the verification, the LLMs either proceed to the next correction stage or finalize the answer. This iterative self-correction process allows the LLMs to refine their reasoning steps and improve the accuracy of their mathematical reasoning. To enable the CoSC mechanism at a low cost, we employ a two-phase finetuning approach. In the first phase, the LLMs are trained with a relatively small volume of seeding data generated from GPT-4, establishing an initial CoSC capability. In the second phase, the CoSC capability is further enhanced by training with a larger volume of self-generated data using the trained model in the first phase, without relying on the paid GPT-4. Our comprehensive experiments demonstrate that CoSC significantly improves performance on traditional mathematical datasets among existing open-source LLMs. Notably, our CoSC-Code-34B model achieved a 53.5% score on MATH, the most challenging mathematical reasoning dataset in the public domain, surpassing the performance of well-established models such as ChatGPT, GPT-4, and even multi-modal LLMs like GPT-4V, Gemini-1.0 Pro, and Gemini-1.0 Ultra.

[Arxiv](https://arxiv.org/abs/2410.10735)