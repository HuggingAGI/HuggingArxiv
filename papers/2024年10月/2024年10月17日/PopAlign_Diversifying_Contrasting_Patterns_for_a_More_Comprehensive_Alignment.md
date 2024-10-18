# PopAlign：通过多样化对比模式，实现更全面的对齐

发布时间：2024年10月17日

`LLM理论` `人工智能`

> PopAlign: Diversifying Contrasting Patterns for a More Comprehensive Alignment

# 摘要

> 大型语言模型 (LLM) 的对齐需要通过训练模型在偏好对比输出对上，以符合人类偏好。传统方法如 RLHF 和 RLAIF 依赖于有限的对比模式，如模型变体或解码温度的变化，这导致对齐不全面且易受攻击。为此，我们探索了如何构建更全面和多样化的对比模式来增强偏好数据 (RQ1)，并验证其对模型对齐的影响 (RQ2)。我们提出了 PopAlign 框架，该框架在多个层面上集成多样化对比模式，并引入六种无需额外标注的对比策略。实验证明，PopAlign 显著提升了对齐效果，超越了现有方法。

> Alignment of large language models (LLMs) involves training models on preference-contrastive output pairs to adjust their responses according to human preferences. To obtain such contrastive pairs, traditional methods like RLHF and RLAIF rely on limited contrasting patterns, such as varying model variants or decoding temperatures. This singularity leads to two issues: (1) alignment is not comprehensive; and thereby (2) models are susceptible to jailbreaking attacks. To address these issues, we investigate how to construct more comprehensive and diversified contrasting patterns to enhance preference data (RQ1) and verify the impact of the diversification of contrasting patterns on model alignment (RQ2). For RQ1, we propose PopAlign, a framework that integrates diversified contrasting patterns across the prompt, model, and pipeline levels, introducing six contrasting strategies that do not require additional feedback labeling procedures. Regarding RQ2, we conduct thorough experiments demonstrating that PopAlign significantly outperforms existing methods, leading to more comprehensive alignment.

[Arxiv](https://arxiv.org/abs/2410.13785)