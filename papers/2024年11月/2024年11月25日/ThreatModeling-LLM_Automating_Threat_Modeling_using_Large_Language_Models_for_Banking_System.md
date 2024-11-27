# ThreatModeling-LLM：利用大型语言模型为银行系统实现威胁建模自动化

发布时间：2024年11月25日

`LLM应用` `网络安全`

> ThreatModeling-LLM: Automating Threat Modeling using Large Language Models for Banking System

# 摘要

> 威胁建模乃是网络安全的关键一环，对银行这类行业而言更是如此，因为金融数据的安全至关重要。传统的威胁建模方式需要专家介入和人工操作，常常致使效率低下和人为失误。大型语言模型（LLMs）的出现为这些流程的自动化开辟了一条充满希望的道路，提升了效率和效果。然而，由于三大挑战，这一转变并非坦途：（1）缺少公开可用的特定领域数据集，（2）需要定制模型来应对复杂的银行系统架构，（3）需要符合像 NIST 800-53 这样合规标准的实时、自适应缓解策略。
    在本文中，我们推出了 ThreatModeling-LLM，这是一个借助 LLMs 为银行系统自动开展威胁建模的新颖且适应性强的框架。ThreatModeling-LLM 分三个阶段运作：1）创建数据集，2）进行提示工程，3）模型微调。我们首先利用微软威胁建模工具（TMT）生成基准数据集。接着，在预训练的 LLMs 上运用思维链（CoT）和通过提示进行优化（OPRO）来优化初始提示。最后，基于基准数据集和优化后的提示，使用低秩自适应（LoRA）对 LLM 进行微调，以增强预训练 LLMs 的威胁识别和缓解生成能力。

> Threat modeling is a crucial component of cybersecurity, particularly for industries such as banking, where the security of financial data is paramount. Traditional threat modeling approaches require expert intervention and manual effort, often leading to inefficiencies and human error. The advent of Large Language Models (LLMs) offers a promising avenue for automating these processes, enhancing both efficiency and efficacy. However, this transition is not straightforward due to three main challenges: (1) the lack of publicly available, domain-specific datasets, (2) the need for tailored models to handle complex banking system architectures, and (3) the requirement for real-time, adaptive mitigation strategies that align with compliance standards like NIST 800-53.
  In this paper, we introduce ThreatModeling-LLM, a novel and adaptable framework that automates threat modeling for banking systems using LLMs. ThreatModeling-LLM operates in three stages: 1) dataset creation, 2) prompt engineering and 3) model fine-tuning. We first generate a benchmark dataset using Microsoft Threat Modeling Tool (TMT). Then, we apply Chain of Thought (CoT) and Optimization by PROmpting (OPRO) on the pre-trained LLMs to optimize the initial prompt. Lastly, we fine-tune the LLM using Low-Rank Adaptation (LoRA) based on the benchmark dataset and the optimized prompt to improve the threat identification and mitigation generation capabilities of pre-trained LLMs.

[Arxiv](https://arxiv.org/abs/2411.17058)