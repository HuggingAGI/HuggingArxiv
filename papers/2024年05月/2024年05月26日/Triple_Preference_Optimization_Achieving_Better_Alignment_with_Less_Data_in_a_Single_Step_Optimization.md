# 一步优化，三重偏好：以更少数据实现精准对齐

发布时间：2024年05月26日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）的偏好优化问题，特别是提出了三重偏好优化（TPO）方法，旨在改善模型的对齐性能，同时减少对大量数据和独立监督微调步骤的依赖。这种方法的应用性质明显，因为它直接关注于优化LLM的性能，以更好地与人类偏好对齐，这是LLM在实际应用中的一个关键问题。因此，这篇论文属于LLM应用分类。` `人工智能`

> Triple Preference Optimization: Achieving Better Alignment with Less Data in a Single Step Optimization

# 摘要

> 大型语言模型（LLMs）虽在多任务中表现卓越，但与人类示范对齐仍是一大挑战。近期，无需强化学习（RL）的直接偏好优化（DPO）等方法崭露头角，不仅提升了稳定性和可扩展性，还保持了与传统RL方法的竞争力。然而，这些方法虽表现出色，却需大量数据构建稳健的监督微调（SFT）模型，并额外进行偏好数据集上的微调，限制了其应用范围和扩展性。为此，我们提出了三重偏好优化（TPO），一种新型偏好学习技术，旨在无需独立SFT步骤，且使用较少数据的情况下，使LLM与三种偏好精准对齐。通过一系列实验和理论分析，我们验证了TPO作为一步到位对齐策略的高效性。特别地，我们在UltraFeedback数据集上直接应用TPO对Phi-2（2.7B）和Mistral（7B）模型进行微调，结果显著优于其他方法。此外，TPO在MT-Bench评分上，无需SFT组件即实现了显著提升，分别超过SFT和DPO 1.27分和0.63分。在Open LLM Leaderboard上，TPO的平均准确度也分别领先DPO和SFT 4.2%和4.97%。我们的代码已公开于https://github.com/sahsaeedi/triple-preference-optimization。

> Large Language Models (LLMs) perform well across diverse tasks, but aligning them with human demonstrations is challenging. Recently, Reinforcement Learning (RL)-free methods like Direct Preference Optimization (DPO) have emerged, offering improved stability and scalability while retaining competitive performance relative to RL-based methods. However, while RL-free methods deliver satisfactory performance, they require significant data to develop a robust Supervised Fine-Tuned (SFT) model and an additional step to fine-tune this model on a preference dataset, which constrains their utility and scalability. In this paper, we introduce Triple Preference Optimization (TPO), a new preference learning method designed to align an LLM with three preferences without requiring a separate SFT step and using considerably less data. Through a combination of practical experiments and theoretical analysis, we show the efficacy of TPO as a single-step alignment strategy. Specifically, we fine-tuned the Phi-2 (2.7B) and Mistral (7B) models using TPO directly on the UltraFeedback dataset, achieving superior results compared to models aligned through other methods such as SFT, DPO, KTO, IPO, CPO, and ORPO. Moreover, the performance of TPO without the SFT component led to notable improvements in the MT-Bench score, with increases of +1.27 and +0.63 over SFT and DPO, respectively. Additionally, TPO showed higher average accuracy, surpassing DPO and SFT by 4.2% and 4.97% on the Open LLM Leaderboard benchmarks. Our code is publicly available at https://github.com/sahsaeedi/triple-preference-optimization .

![一步优化，三重偏好：以更少数据实现精准对齐](../../../paper_images/2405.16681/x1.png)

![一步优化，三重偏好：以更少数据实现精准对齐](../../../paper_images/2405.16681/x2.png)

![一步优化，三重偏好：以更少数据实现精准对齐](../../../paper_images/2405.16681/x3.png)

![一步优化，三重偏好：以更少数据实现精准对齐](../../../paper_images/2405.16681/x4.png)

[Arxiv](https://arxiv.org/abs/2405.16681)