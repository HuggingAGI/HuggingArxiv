# 利用大型语言模型，通过评论驱动个性化偏好推理，提升推荐系统性能。

发布时间：2024年08月12日

`LLM应用` `推荐系统` `电子商务`

> Review-driven Personalized Preference Reasoning with Large Language Models for Recommendation

# 摘要

> 大型语言模型 (LLM) 的最新进展在众多任务中表现卓越，激发了将其应用于推荐系统的兴趣。然而，现有方法未能充分挖掘 LLM 的潜力，常因输入信息有限或未能充分利用其高级推理能力而受限。为此，我们推出了 EXP3RT，一种基于 LLM 的新型推荐系统，旨在利用用户和商品评论中的丰富偏好信息。EXP3RT 通过从教师 LLM 中提取知识进行微调，依次执行三大关键任务：首先，从原始评论中提取并整合主观偏好，形成用户和商品档案；接着，结合用户/商品档案和商品描述中的主观与客观信息，进行详尽的推理，并预测评分，实现推理增强的评分预测。EXP3RT 的个性化偏好推理不仅提升了评分预测的准确性，还为推荐提供了合理且可信的解释。实验证明，EXP3RT 在评分预测和 top-k 推荐中的商品重排序方面均超越现有方法，大幅提升了推荐系统的可解释性。

> Recent advancements in Large Language Models (LLMs) have demonstrated exceptional performance across a wide range of tasks, generating significant interest in their application to recommendation systems. However, existing methods have not fully capitalized on the potential of LLMs, often constrained by limited input information or failing to fully utilize their advanced reasoning capabilities. To address these limitations, we introduce EXP3RT, a novel LLM-based recommender designed to leverage rich preference information contained in user and item reviews. EXP3RT is basically fine-tuned through distillation from a teacher LLM to perform three key tasks in order: EXP3RT first extracts and encapsulates essential subjective preferences from raw reviews, aggregates and summarizes them according to specific criteria to create user and item profiles. It then generates detailed step-by-step reasoning followed by predicted rating, i.e., reasoning-enhanced rating prediction, by considering both subjective and objective information from user/item profiles and item descriptions. This personalized preference reasoning from EXP3RT enhances rating prediction accuracy and also provides faithful and reasonable explanations for recommendation. Extensive experiments show that EXP3RT outperforms existing methods on both rating prediction and candidate item reranking for top-k recommendation, while significantly enhancing the explainability of recommendation systems.

[Arxiv](https://arxiv.org/abs/2408.06276)