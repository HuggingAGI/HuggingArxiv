# 通过自训练揭示上下文学习的潜在变化

发布时间：2024年10月02日

`LLM理论` `机器学习`

> Disentangling Latent Shifts of In-Context Learning Through Self-Training

# 摘要

> 在自然语言处理领域，ICL 已成为关键技术，尤其是在自回归大型语言模型中，能够从提示中的演示中学习。然而，ICL 在处理大量演示时，面临稳定性和长上下文的挑战，导致泛化能力差和推理效率低下。为此，我们提出了 STICL（自训练 ICL），通过自训练分离演示和查询的潜在偏移。STICL 利用教师模型生成伪标签，训练学生模型，逐步提升其泛化能力。实证结果显示，STICL 在泛化能力和稳定性上显著提升，超越了传统 ICL 方法和其他分离策略，无论是在域内还是域外数据上。

> In-context learning (ICL) has become essential in natural language processing, particularly with autoregressive large language models capable of learning from demonstrations provided within the prompt. However, ICL faces challenges with stability and long contexts, especially as the number of demonstrations grows, leading to poor generalization and inefficient inference. To address these issues, we introduce STICL (Self-Training ICL), an approach that disentangles the latent shifts of demonstrations from the latent shift of the query through self-training. STICL employs a teacher model to generate pseudo-labels and trains a student model using these labels, encoded in an adapter module. The student model exhibits weak-to-strong generalization, progressively refining its predictions over time. Our empirical results show that STICL improves generalization and stability, consistently outperforming traditional ICL methods and other disentangling strategies across both in-domain and out-of-domain data.

[Arxiv](https://arxiv.org/abs/2410.01508)