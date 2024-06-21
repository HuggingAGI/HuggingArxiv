# 通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。

发布时间：2024年06月19日

`LLM应用

这篇论文介绍了一种名为AutoIF的方法，用于自动生成高质量的训练数据，以提升大型语言模型（LLMs）处理复杂指令的能力。该方法通过代码验证确保数据质量，并利用执行反馈的拒绝采样为监督微调和人类反馈强化学习训练提供数据。这种方法在多个开源LLMs上应用时，对不同的训练算法均带来了显著提升。因此，这篇论文属于LLM应用分类，因为它关注的是LLMs的实际应用和改进，特别是通过自动生成训练数据来增强模型的指令遵循能力。` `人工智能`

> Self-play with Execution Feedback: Improving Instruction-following Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）的核心能力之一是遵循自然语言指令，但自动构建高质量训练数据以提升其复杂指令处理能力的问题仍未解决。本文推出的AutoIF，是首个既可扩展又可靠的自动生成指令遵循训练数据的方法。它通过代码验证确保数据质量，要求LLMs生成指令及验证响应正确性的代码，并提供单元测试样本以验证代码的正确性。利用执行反馈的拒绝采样，AutoIF为监督微调和人类反馈强化学习训练提供了数据。在Qwen2和LLaMA3等顶级开源LLMs上应用时，AutoIF在自对齐和强弱蒸馏场景下，对SFT、离线DPO和在线DPO三种训练算法均带来了显著提升。相关代码已公开于https://github.com/QwenLM/AutoIF。

> One core capability of large language models (LLMs) is to follow natural language instructions. However, the issue of automatically constructing high-quality training data to enhance the complex instruction-following abilities of LLMs without manual annotation remains unresolved. In this paper, we introduce AutoIF, the first scalable and reliable method for automatically generating instruction-following training data. AutoIF transforms the validation of instruction-following data quality into code verification, requiring LLMs to generate instructions, the corresponding code to check the correctness of the instruction responses, and unit test samples to verify the code's correctness. Then, execution feedback-based rejection sampling can generate data for Supervised Fine-Tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF) training. AutoIF achieves significant improvements across three training algorithms, SFT, Offline DPO, and Online DPO, when applied to the top open-source LLMs, Qwen2 and LLaMA3, in self-alignment and strong-to-weak distillation settings. Our code is publicly available at https://github.com/QwenLM/AutoIF.

![通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。](../../../paper_images/2406.13542/x1.png)

![通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。](../../../paper_images/2406.13542/x2.png)

![通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。](../../../paper_images/2406.13542/x3.png)

![通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。](../../../paper_images/2406.13542/x4.png)

![通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。](../../../paper_images/2406.13542/x5.png)

![通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。](../../../paper_images/2406.13542/x6.png)

![通过自我对弈与执行反馈相结合，我们致力于提升大型语言模型在遵循指令方面的能力。](../../../paper_images/2406.13542/x7.png)

[Arxiv](https://arxiv.org/abs/2406.13542)