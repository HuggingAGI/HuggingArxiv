# 自更新大型语言模型，通过参数集成实现持续进化

发布时间：2024年10月01日

`LLM理论` `人工智能` `机器学习`

> Self-Updatable Large Language Models with Parameter Integration

# 摘要

> 尽管 LLM 取得了显著进展，但快速整合小规模经验（如与周围物体的互动）仍是一大挑战。关键在于效能（准确记住最近事件）和保持（回忆久远经验）。当前方法要么难以应对快速更新和复杂互动，要么增加存储需求。我们提出 SELF-PARAM，无需额外参数，同时确保高效能和长期保持。通过最小化原始模型与目标模型预测间的 KL 散度，我们更新目标模型，使其无缝内化知识。评估显示，即使考虑存储需求，SELF-PARAM 也显著优于现有方法。这一创新为 LLM 中更高效的经验整合铺平了道路。

> Despite significant advancements in large language models (LLMs), the rapid and frequent integration of small-scale experiences, such as interactions with surrounding objects, remains a substantial challenge. Two critical factors in assimilating these experiences are (1) Efficacy: the ability to accurately remember recent events; (2) Retention: the capacity to recall long-past experiences. Current methods either embed experiences within model parameters using continual learning, model editing, or knowledge distillation techniques, which often struggle with rapid updates and complex interactions, or rely on external storage to achieve long-term retention, thereby increasing storage requirements. In this paper, we propose SELF-PARAM (Self-Updatable Large Language Models with Parameter Integration). SELF-PARAM requires no extra parameters while ensuring near-optimal efficacy and long-term retention. Our method employs a training objective that minimizes the Kullback-Leibler (KL) divergence between the predictions of an original model (with access to contextual information) and a target model (without such access). By generating diverse question-answer pairs related to the knowledge and minimizing the KL divergence across this dataset, we update the target model to internalize the knowledge seamlessly within its parameters. Evaluations on question-answering and conversational recommendation tasks demonstrate that SELF-PARAM significantly outperforms existing methods, even when accounting for non-zero storage requirements. This advancement paves the way for more efficient and scalable integration of experiences in large language models by embedding knowledge directly into model parameters.

[Arxiv](https://arxiv.org/abs/2410.00487)