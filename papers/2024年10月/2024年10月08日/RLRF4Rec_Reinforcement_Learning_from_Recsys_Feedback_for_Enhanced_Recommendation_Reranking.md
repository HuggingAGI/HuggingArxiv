# RLRF4Rec：通过推荐系统反馈的强化学习，提升推荐重排序效果

发布时间：2024年10月08日

`LLM应用` `推荐系统` `人工智能`

> RLRF4Rec: Reinforcement Learning from Recsys Feedback for Enhanced Recommendation Reranking

# 摘要

> 大型语言模型 (LLM) 在多个领域表现出色，激发了研究人员将其应用于推荐系统的兴趣。早期尝试利用 LLM 的丰富知识和强大泛化能力，通过 In-context Learning 将推荐任务转化为提示。然而，由于训练任务与推荐任务的差异及预训练数据不足，LLM 在推荐任务中的表现仍不理想。为此，我们提出了 RLRF4Rec 框架，结合推荐系统反馈的强化学习与 LLM，以应对这些挑战。首先，LLM 根据用户历史交互生成用户偏好，增强传统序列推荐模型。接着，我们训练奖励模型评估 LLM 推理知识的质量，并从 N 个样本中挑选最佳和最差响应构建调优数据集。最后，采用直接偏好优化 (DPO) 的结构对齐策略。实验结果显示，RLRF4Rec 在推荐重排序指标上显著优于基线，大幅提升了 LLM 在推荐系统中的指令响应能力。

> Large Language Models (LLMs) have demonstrated remarkable performance across diverse domains, prompting researchers to explore their potential for use in recommendation systems. Initial attempts have leveraged the exceptional capabilities of LLMs, such as rich knowledge and strong generalization through In-context Learning, which involves phrasing the recommendation task as prompts. Nevertheless, the performance of LLMs in recommendation tasks remains suboptimal due to a substantial disparity between the training tasks for LLMs and recommendation tasks and inadequate recommendation data during pre-training. This paper introduces RLRF4Rec, a novel framework integrating Reinforcement Learning from Recsys Feedback for Enhanced Recommendation Reranking(RLRF4Rec) with LLMs to address these challenges. Specifically, We first have the LLM generate inferred user preferences based on user interaction history, which is then used to augment traditional ID-based sequence recommendation models. Subsequently, we trained a reward model based on knowledge augmentation recommendation models to evaluate the quality of the reasoning knowledge from LLM. We then select the best and worst responses from the N samples to construct a dataset for LLM tuning. Finally, we design a structure alignment strategy with Direct Preference Optimization(DPO). We validate the effectiveness of RLRF4Rec through extensive experiments, demonstrating significant improvements in recommendation re-ranking metrics compared to baselines. This demonstrates that our approach significantly improves the capability of LLMs to respond to instructions within recommender systems.

[Arxiv](https://arxiv.org/abs/2410.05939)