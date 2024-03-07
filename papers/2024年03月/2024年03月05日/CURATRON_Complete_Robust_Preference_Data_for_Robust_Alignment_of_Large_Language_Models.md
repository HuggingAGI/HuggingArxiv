# [CURATRON 提供了一套完整的、针对大型语言模型进行稳健对齐所必需的高质量偏好数据，以实现其在各类任务中的可靠和稳健表现。](https://arxiv.org/abs/2403.02745)

> CURATRON: Complete Robust Preference Data for Robust Alignment of Large Language Models

发布时间：2024年03月05日

> 本文聚焦于如何通过偏好学习让大型语言模型更好地契合人类价值观，并特别关注偏好数据集中存在的不完整及被污染数据问题。我们创新性地提出一种新方法，在此类数据集中全面而稳健地调整价值参数，从而提升LLMs抵抗相关问题的能力。为此，我们研发了一种具有理论保证的多项式时间复杂度排序算法，它能有效强化包括经典BTL模型及其若干拓展模型在内的多个现有模型。值得一提的是，我们首次提出了一个即使每条模型反馈中存在O(n)数量级的扰动成对比较结果，仍能在高概率下确保恢复接近最优（ε-optimal）排序的算法。不仅如此，我们在部分观测场景下也展示了算法的稳健恢复效果。实验证明，无论是通用偏好数据集还是LLM特定偏好数据集，我们的算法都能出色应对对抗性噪声和未观测到的比较情况。此项研究通过赋予数据集整理过程处理缺失及恶意篡改输入的能力，有力推动构建更加可靠且符合伦理的人工智能模型的发展与规模化应用。

> This paper addresses the challenges of aligning large language models (LLMs) with human values via preference learning (PL), with a focus on the issues of incomplete and corrupted data in preference datasets. We propose a novel method for robustly and completely recalibrating values within these datasets to enhance LLMs resilience against the issues. In particular, we devise a guaranteed polynomial time ranking algorithm that robustifies several existing models, such as the classic Bradley--Terry--Luce (BTL) (Bradley and Terry, 1952) model and certain generalizations of it. To the best of our knowledge, our present work is the first to propose an algorithm that provably recovers an ε-optimal ranking with high probability while allowing as large as O(n) perturbed pairwise comparison results per model response. Furthermore, we show robust recovery results in the partially observed setting. Our experiments confirm that our algorithms handle adversarial noise and unobserved comparisons well in both general and LLM preference dataset settings. This work contributes to the development and scaling of more reliable and ethically aligned AI models by equipping the dataset curation pipeline with the ability to handle missing and maliciously manipulated inputs.

`LLM理论`