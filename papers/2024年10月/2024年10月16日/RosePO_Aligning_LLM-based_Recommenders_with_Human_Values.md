# RosePO：让基于 LLM 的推荐系统与人类价值观和谐共舞

发布时间：2024年10月16日

`LLM应用` `推荐系统` `人工智能`

> RosePO: Aligning LLM-based Recommenders with Human Values

# 摘要

> 近期，利用大型语言模型 (LLM) 进行推荐系统的研究日益增多，通常通过监督微调 (SFT) 将预训练的 LLM 应用于推荐场景。然而，预训练和 SFT 阶段均未能明确捕捉用户对不同项目的偏好比较。为此，我们提出了一种名为“基于平滑个性化偏好优化的推荐 (RosePO)”的通用框架，旨在训练后阶段更好地契合定制化的人类价值观。具体而言，除了与 SFT 数据自然匹配的输入和选定响应外，我们还设计了拒绝采样策略以增强有益性，并采用两种策略减轻偏见，提升无害性。为确保对自动构建的偏好数据中不确定标签的鲁棒性，我们引入了由偏好预言机预测的个性化平滑因子至优化目标中。在三个真实世界数据集上的评估结果显示，我们的方法不仅提升了推荐性能，还有效缓解了语义幻觉和流行度偏见。

> Recently, there has been a growing interest in leveraging Large Language Models (LLMs) for recommendation systems, which usually adapt a pre-trained LLM to the recommendation scenario through supervised fine-tuning (SFT). However, both the pre-training and SFT stages fail to explicitly model the comparative relationships of a user's preferences on different items. To construct a "helpful and harmless" LLM-based recommender, we propose a general framework -- Recommendation with smoothing personalized Preference Optimization (RosePO), which better aligns with customized human values during the post-training stage. Specifically, in addition to the input and chosen response that naturally align with SFT data, we design a rejected sampling strategy tailored for enhancing helpfulness, along with two strategies aimed at mitigating biases to promote harmlessness. To ensure robustness against uncertain labels present in automatically constructed preference data, we introduce a personalized smoothing factor predicted by a preference oracle into the optimization objective. Evaluation on three real-world datasets demonstrates the effectiveness of our method, showcasing not only improved recommendation performance but also mitigation of semantic hallucination and popularity bias.

[Arxiv](https://arxiv.org/abs/2410.12519)