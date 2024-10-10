# 突破思维界限：构建推理粒度框架，量化并优化思维链

发布时间：2024年10月08日

`LLM理论` `人工智能`

> Unlocking the Boundaries of Thought: A Reasoning Granularity Framework to Quantify and Optimize Chain-of-Thought

# 摘要

> CoT 推理作为一种提升 LLM 复杂推理任务性能的有效方法，近期备受关注。然而，现有研究在评估 CoT 能力和优化其性能方面仍面临两大难题。为此，我们提出了推理粒度框架 (RGF)，旨在解决这些挑战。首先，我们定义了推理粒度 (RG) 来量化 CoT 的上限，并建立了组合定律，为实际应用提供了量化方法。接着，我们提出了三种 RG 类别，并通过优化推理路径和提升 RG，进一步改进了 CoT 性能。通过 25 个模型和 4 个任务的实验，我们验证了框架的合理性，并分析了 10 种 CoT 策略的有效性，从多角度指导优化。希望这项工作能为 LLM 中的推理提供更全面的理解和优化策略。相关代码和数据已公开在 https://github.com/LightChen233/reasoning-granularity。

> Chain-of-Thought (CoT) reasoning has emerged as a promising approach for enhancing the performance of large language models (LLMs) on complex reasoning tasks. Recently, a series of studies attempt to explain the mechanisms underlying CoT, aiming to deepen the understanding of its efficacy. Nevertheless, the existing research faces two major challenges: (1) a lack of quantitative metrics to assess CoT capabilities and (2) a dearth of guidance on optimizing CoT performance. Motivated by this, in this work, we introduce a novel reasoning granularity framework (RGF) to address these challenges. To solve the lack of quantification, we first define a reasoning granularity (RG) to quantify the upper bound of CoT and establish a combination law for RG, enabling a practical quantitative approach applicable to various real-world CoT tasks. To address the lack of optimization, we propose three categories of RGs. We further optimize these categories with combination laws focused on RG promotion and reasoning path optimization for CoT improvement. Through extensive experiments on 25 models and 4 tasks, the study validates the existence and rationality of the proposed framework. Furthermore, it explains the effectiveness of 10 CoT strategies and guides optimization from two perspectives. We hope this work can provide a comprehensive understanding of the boundaries and optimization strategies for reasoning in LLMs. Our code and data are available at https://github.com/LightChen233/reasoning-granularity.

[Arxiv](https://arxiv.org/abs/2410.05695)