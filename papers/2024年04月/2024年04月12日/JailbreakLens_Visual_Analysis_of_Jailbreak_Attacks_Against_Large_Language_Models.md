# JailbreakLens：揭秘大型语言模型面临的越狱攻击的视觉解析

发布时间：2024年04月12日

`LLM应用` `安全性` `大型语言模型`

> JailbreakLens: Visual Analysis of Jailbreak Attacks Against Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的日益普及，其安全隐患问题日益凸显，特别是面对越狱攻击的挑战，攻击者通过设计越狱提示来绕过安全机制，可能导致模型被滥用。为了应对这些挑战，我们需要对越狱提示进行全面的分析，以评估LLMs的防御实力并找出潜在的薄弱环节。然而，越狱性能的评估和提示特征的理解过程复杂且耗时。为此，我们携手领域专家共同剖析问题，并提出了一个由LLM驱动的分析框架，旨在简化这一分析流程。该框架能够自动进行越狱评估，便于性能的快速评估，并对提示中的各个组件和关键词进行深入分析。在此基础上，我们开发了JailbreakLens——一个直观的视觉分析系统，它不仅能够帮助用户深入探究模型对越狱攻击的抵御能力，还能对提示特征进行细致的多层次分析，并优化提示实例以验证研究成果。通过一系列案例研究、技术评估和专家访谈，我们证明了JailbreakLens系统在协助用户评估模型安全性和发现模型弱点方面的强大效力。

> The proliferation of large language models (LLMs) has underscored concerns regarding their security vulnerabilities, notably against jailbreak attacks, where adversaries design jailbreak prompts to circumvent safety mechanisms for potential misuse. Addressing these concerns necessitates a comprehensive analysis of jailbreak prompts to evaluate LLMs' defensive capabilities and identify potential weaknesses. However, the complexity of evaluating jailbreak performance and understanding prompt characteristics makes this analysis laborious. We collaborate with domain experts to characterize problems and propose an LLM-assisted framework to streamline the analysis process. It provides automatic jailbreak assessment to facilitate performance evaluation and support analysis of components and keywords in prompts. Based on the framework, we design JailbreakLens, a visual analysis system that enables users to explore the jailbreak performance against the target model, conduct multi-level analysis of prompt characteristics, and refine prompt instances to verify findings. Through a case study, technical evaluations, and expert interviews, we demonstrate our system's effectiveness in helping users evaluate model security and identify model weaknesses.

![JailbreakLens：揭秘大型语言模型面临的越狱攻击的视觉解析](../../../paper_images/2404.08793/framework.png)

![JailbreakLens：揭秘大型语言模型面临的越狱攻击的视觉解析](../../../paper_images/2404.08793/component_design.png)

![JailbreakLens：揭秘大型语言模型面临的越狱攻击的视觉解析](../../../paper_images/2404.08793/keyword_desgin.png)

![JailbreakLens：揭秘大型语言模型面临的越狱攻击的视觉解析](../../../paper_images/2404.08793/Case.png)

![JailbreakLens：揭秘大型语言模型面临的越狱攻击的视觉解析](../../../paper_images/2404.08793/evaluation.png)

[Arxiv](https://arxiv.org/abs/2404.08793)