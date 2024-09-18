# 迈向富有同理心的对话推荐系统

发布时间：2024年08月30日

`LLM应用` `情感分析`

> Towards Empathetic Conversational Recommender Systems

# 摘要

> 对话推荐系统 (CRS) 通过多轮对话引出用户偏好，通常结合外部知识和预训练语言模型来捕捉对话上下文。然而，大多数 CRS 方法在基准数据集上训练，假设标准项目和响应最优，却忽略了用户可能对标准项目表达负面情绪，且对标准响应缺乏情感共鸣。这导致系统倾向于复制数据集中的推荐逻辑，而非与用户需求保持一致。为解决这一问题，我们在 CRS 中引入了共情，即系统捕捉和表达情感的能力。我们提出了共情对话推荐 (ECR) 框架，包含情感感知的项目推荐和情感对齐的响应生成两大模块。具体来说，我们利用用户情感优化偏好建模，实现更准确的推荐；并通过检索增强的提示微调预训练语言模型，生成更贴近人类情感的响应，同时减少幻觉。为应对监督标签不足的挑战，我们使用大型语言模型注释的情感标签和外部资源中的情感评论来扩充共情数据。此外，我们提出了新的评估指标，以更真实地捕捉用户满意度。在 ReDial 数据集上的实验表明，我们的框架有效提升了推荐准确性和用户满意度。

> Conversational recommender systems (CRSs) are able to elicit user preferences through multi-turn dialogues. They typically incorporate external knowledge and pre-trained language models to capture the dialogue context. Most CRS approaches, trained on benchmark datasets, assume that the standard items and responses in these benchmarks are optimal. However, they overlook that users may express negative emotions with the standard items and may not feel emotionally engaged by the standard responses. This issue leads to a tendency to replicate the logic of recommenders in the dataset instead of aligning with user needs. To remedy this misalignment, we introduce empathy within a CRS. With empathy we refer to a system's ability to capture and express emotions. We propose an empathetic conversational recommender (ECR) framework.
  ECR contains two main modules: emotion-aware item recommendation and emotion-aligned response generation. Specifically, we employ user emotions to refine user preference modeling for accurate recommendations. To generate human-like emotional responses, ECR applies retrieval-augmented prompts to fine-tune a pre-trained language model aligning with emotions and mitigating hallucination. To address the challenge of insufficient supervision labels, we enlarge our empathetic data using emotion labels annotated by large language models and emotional reviews collected from external resources. We propose novel evaluation metrics to capture user satisfaction in real-world CRS scenarios. Our experiments on the ReDial dataset validate the efficacy of our framework in enhancing recommendation accuracy and improving user satisfaction.

[Arxiv](https://arxiv.org/abs/2409.10527)