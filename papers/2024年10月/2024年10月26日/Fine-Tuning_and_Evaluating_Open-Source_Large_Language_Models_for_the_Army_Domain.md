# 针对陆军领域的开源大型语言模型进行微调与评估

发布时间：2024年10月26日

`LLM应用` `人工智能`

> Fine-Tuning and Evaluating Open-Source Large Language Models for the Army Domain

# 摘要

> 近年来，大型语言模型（LLMs）的广泛运用激起了人们对其在军事领域应用潜力的关注。但由于特定领域词汇和术语的大量存在，当下这一代 LLMs 在陆军的应用案例中表现欠佳。为了在该领域充分利用 LLMs，众多组织选择微调，以规避从零开始训练新 LLMs 的高昂成本。鉴于此趋势，我们探究了让开源 LLMs 适用于陆军领域的可行性，以弥补其当前缺乏特定领域性的不足。我们的研究造就了三代不同的 TRACLM，这是由陆军未来司令部（AFC）的研究与分析中心（TRAC）微调而成的一系列 LLMs。通过持续优化我们的训练流程，TRACLM 的每一次迭代在用于陆军任务和应用案例时，能力都有所提升。而且，在微调实验过程中，我们意识到需要一个评估框架来客观量化 LLMs 的陆军特定领域知识。为此，我们开发了 MilBench，这是一个可扩展的软件框架，能利用源自教义和评估的任务，有效评估给定 LLMs 的陆军知识。我们分享了创建 TRACLM 和 MilBench 的初步成果、模型、方法及建议。我们的工作有力推动了国防部内 LLM 技术的发展，并为高级领导在人工智能集成方面的决策提供了参考。

> In recent years, the widespread adoption of Large Language Models (LLMs) has sparked interest in their potential for application within the military domain. However, the current generation of LLMs demonstrate sub-optimal performance on Army use cases, due to the prevalence of domain-specific vocabulary and jargon. In order to fully leverage LLMs in-domain, many organizations have turned to fine-tuning to circumvent the prohibitive costs involved in training new LLMs from scratch. In light of this trend, we explore the viability of adapting open-source LLMs for usage in the Army domain in order to address their existing lack of domain-specificity. Our investigations have resulted in the creation of three distinct generations of TRACLM, a family of LLMs fine-tuned by The Research and Analysis Center (TRAC), Army Futures Command (AFC). Through continuous refinement of our training pipeline, each successive iteration of TRACLM displayed improved capabilities when applied to Army tasks and use cases. Furthermore, throughout our fine-tuning experiments, we recognized the need for an evaluation framework that objectively quantifies the Army domain-specific knowledge of LLMs. To address this, we developed MilBench, an extensible software framework that efficiently evaluates the Army knowledge of a given LLM using tasks derived from doctrine and assessments. We share preliminary results, models, methods, and recommendations on the creation of TRACLM and MilBench. Our work significantly informs the development of LLM technology across the DoD and augments senior leader decisions with respect to artificial intelligence integration.

[Arxiv](https://arxiv.org/abs/2410.20297)