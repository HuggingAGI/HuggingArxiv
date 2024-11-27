# VLRewardBench：一个针对视觉语言生成奖励模型的颇具挑战性的基准

发布时间：2024年11月26日

`LLM应用` `多模态` `人工智能`

> VLRewardBench: A Challenging Benchmark for Vision-Language Generative Reward Models

# 摘要

> 视觉语言生成奖励模型（VL-GenRMs）在多模态人工智能系统的对齐与评估中起着至关重要的作用，但其自身的评估却尚未得到充分探究。当下的评估手段主要依赖于传统视觉语言任务中人工智能标注的偏好标签，这可能引入偏差，且往往难以有效挑战前沿模型。为突破这些局限，我们推出了 VL-RewardBench，这是一个囊括一般多模态查询、视觉幻觉检测及复杂推理任务的综合性基准。借助我们融合样本选择与人工校验的人工智能辅助标注流程，我们精心筛选出 1250 个高质量示例，专门用于探寻模型的局限。对 16 个领先的大型视觉语言模型展开的综合评估显示，VL-RewardBench 作为一个富有挑战性的测试平台成效显著，即便 GPT-4o 的准确率也仅为 65.4%，像 Qwen2-VL-72B 这类先进的开源模型，也难以超越随机猜测。关键的是，VL-RewardBench 上的表现与采用 VL-GenRMs 的 Best-of-N 采样的 MMMU-Pro 准确率高度相关（皮尔逊相关系数 r > 0.9）。分析实验揭示了改进 VL-GenRMs 的三个关键要点：（i）模型主要在基础视觉感知任务上失利，而非推理任务；（ii）推理时的缩放效益因模型容量差异巨大；（iii）训练 VL-GenRMs 学习判断大幅提升了判断能力（对于 7B 的 VL-GenRM，准确率提升了 +14.7%）。我们坚信 VL-RewardBench 连同实验所得见解将成为推动 VL-GenRMs 发展的宝贵资源。

> Vision-language generative reward models (VL-GenRMs) play a crucial role in aligning and evaluating multimodal AI systems, yet their own evaluation remains under-explored. Current assessment methods primarily rely on AI-annotated preference labels from traditional VL tasks, which can introduce biases and often fail to effectively challenge state-of-the-art models. To address these limitations, we introduce VL-RewardBench, a comprehensive benchmark spanning general multimodal queries, visual hallucination detection, and complex reasoning tasks. Through our AI-assisted annotation pipeline combining sample selection with human verification, we curate 1,250 high-quality examples specifically designed to probe model limitations. Comprehensive evaluation across 16 leading large vision-language models, demonstrates VL-RewardBench's effectiveness as a challenging testbed, where even GPT-4o achieves only 65.4% accuracy, and state-of-the-art open-source models such as Qwen2-VL-72B, struggle to surpass random-guessing. Importantly, performance on VL-RewardBench strongly correlates (Pearson's r > 0.9) with MMMU-Pro accuracy using Best-of-N sampling with VL-GenRMs. Analysis experiments uncover three critical insights for improving VL-GenRMs: (i) models predominantly fail at basic visual perception tasks rather than reasoning tasks; (ii) inference-time scaling benefits vary dramatically by model capacity; and (iii) training VL-GenRMs to learn to judge substantially boosts judgment capability (+14.7% accuracy for a 7B VL-GenRM). We believe VL-RewardBench along with the experimental insights will become a valuable resource for advancing VL-GenRMs.

[Arxiv](https://arxiv.org/abs/2411.17451)