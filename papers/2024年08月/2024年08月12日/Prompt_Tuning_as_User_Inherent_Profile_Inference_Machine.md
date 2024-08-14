# Prompt Tuning：用户的内在特征推理机

发布时间：2024年08月12日

`LLM应用` `推荐系统` `人工智能`

> Prompt Tuning as User Inherent Profile Inference Machine

# 摘要

> 大型语言模型（LLM）凭借其丰富的世界知识和强大的推理能力，在推荐系统领域展现出显著潜力。然而，这些模型也面临着指令遵循不稳定、模态差异和高延迟推理等难题，这些问题不仅产生了文本噪声，还限制了其在推荐系统中的应用效果。为此，我们引入了UserIP-Tuning方法，该方法通过提示调优技术推断用户特征，巧妙地将用户特征与行为序列间的因果关系融入LLM提示中，并运用期望最大化算法推断潜在特征，有效减少了文本噪声。同时，通过配置文件量化码本，将特征嵌入分类为协同ID，提前存储以优化在线部署，从而提升了效率并降低了内存消耗。实验结果显示，UserIP-Tuning在多个公共数据集上超越了现有推荐算法，进一步的测试和案例分析也验证了其卓越的有效性、稳定性和可迁移性。

> Large Language Models (LLMs) have exhibited significant promise in recommender systems by empowering user profiles with their extensive world knowledge and superior reasoning capabilities. However, LLMs face challenges like unstable instruction compliance, modality gaps, and high inference latency, leading to textual noise and limiting their effectiveness in recommender systems. To address these challenges, we propose UserIP-Tuning, which uses prompt-tuning to infer user profiles. It integrates the causal relationship between user profiles and behavior sequences into LLMs' prompts. And employs expectation maximization to infer the embedded latent profile, minimizing textual noise by fixing the prompt template. Furthermore, A profile quantization codebook bridges the modality gap by categorizing profile embeddings into collaborative IDs, which are pre-stored for online deployment. This improves time efficiency and reduces memory usage. Experiments on four public datasets show that UserIP-Tuning outperforms state-of-the-art recommendation algorithms. Additional tests and case studies confirm its effectiveness, robustness, and transferability.

[Arxiv](https://arxiv.org/abs/2408.06577)