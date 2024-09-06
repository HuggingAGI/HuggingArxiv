# CLUE：探索大型语言模型概念级的不确定性

发布时间：2024年09月04日

`LLM理论` `人工智能`

> CLUE: Concept-Level Uncertainty Estimation for Large Language Models

# 摘要

> LLM 在 NLG 任务中表现出色，但其生成过程存在不确定性。现有方法多关注序列整体的不确定性，忽略了细节。为此，我们提出了 CLUE 框架，将输出分解为概念，并分别评估其不确定性。实验表明，CLUE 不仅提供更清晰的估计，还能应用于幻觉检测和故事生成等任务。

> Large Language Models (LLMs) have demonstrated remarkable proficiency in various natural language generation (NLG) tasks. Previous studies suggest that LLMs' generation process involves uncertainty. However, existing approaches to uncertainty estimation mainly focus on sequence-level uncertainty, overlooking individual pieces of information within sequences. These methods fall short in separately assessing the uncertainty of each component in a sequence. In response, we propose a novel framework for Concept-Level Uncertainty Estimation (CLUE) for LLMs. We leverage LLMs to convert output sequences into concept-level representations, breaking down sequences into individual concepts and measuring the uncertainty of each concept separately. We conduct experiments to demonstrate that CLUE can provide more interpretable uncertainty estimation results compared with sentence-level uncertainty, and could be a useful tool for various tasks such as hallucination detection and story generation.

[Arxiv](https://arxiv.org/abs/2409.03021)