# 通过多模态分布的精准对齐，提升大型语言模型的知识蒸馏效率。

发布时间：2024年09月19日

`LLM理论` `人工智能`

> Enhancing Knowledge Distillation of Large Language Models through Efficient Multi-Modal Distribution Alignment

# 摘要

> 知识蒸馏 (KD) 能将大型语言模型 (LLM) 的能力转移到小模型上，但教师 LLM 的多模态概率分布却让学生模型难以学习。本文通过实验强调了多模态分布对齐的重要性，并指出现有 KD 方法在这方面的不足。为此，我们提出了基于排序损失的知识蒸馏 (RLKD)，通过词级排序损失，确保学生模型在峰值预测排序上与教师模型一致，从而更好地学习多模态分布。实验证明，RLKD 在下游任务中显著提升了学生模型的性能。

> Knowledge distillation (KD) is an effective model compression method that can transfer the internal capabilities of large language models (LLMs) to smaller ones. However, the multi-modal probability distribution predicted by teacher LLMs causes difficulties for student models to learn. In this paper, we first demonstrate the importance of multi-modal distribution alignment with experiments and then highlight the inefficiency of existing KD approaches in learning multi-modal distributions. To address this problem, we propose Ranking Loss based Knowledge Distillation (RLKD), which encourages the consistency of the ranking of peak predictions between the teacher and student models. By incorporating word-level ranking loss, we ensure excellent compatibility with existing distillation objectives while fully leveraging the fine-grained information between different categories in peaks of two predicted distribution. Experimental results demonstrate that our method enables the student model to better learn the multi-modal distributions of the teacher model, leading to a significant performance improvement in various downstream tasks.

[Arxiv](https://arxiv.org/abs/2409.12545)