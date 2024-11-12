# 自我训练遇到一致性：通过一致性驱动的原理评估来改进大型语言模型（LLM）的推理能力

发布时间：2024年11月10日

`LLM应用` `语言模型` `问答系统`

> Self-Training Meets Consistency: Improving LLMs' Reasoning With Consistency-Driven Rationale Evaluation

# 摘要

> 大型语言模型（LLM）的自训练方法通过在模型自身生成的原理上进行训练来提高推理能力。以前的方法将为给定问题产生正确答案的原理标记为适合训练。然而，单一的衡量标准有错误判断原理质量的风险，导致模型学习有缺陷的推理模式。为了解决这个问题，我们提出了 CREST（用于自训练的一致性驱动原理评估），这是一个自训练框架，它通过后续问题进一步评估每个原理，并利用此评估来指导其训练。具体来说，我们引入了两种方法：（1）过滤掉在后续问题中经常导致错误答案的原理；（2）基于原始问题和后续问题的原理评估结果的混合偏好进行偏好学习。在使用开放 LLM 的三个问答数据集上的实验表明，与以前的自训练方法相比，CREST 不仅提高了原理的逻辑稳健性和正确性，而且提高了推理能力。

> Self-training approach for large language models (LLMs) improves reasoning abilities by training the models on their self-generated rationales. Previous approaches have labeled rationales that produce correct answers for a given question as appropriate for training. However, a single measure risks misjudging rationale quality, leading the models to learn flawed reasoning patterns. To address this issue, we propose CREST (Consistency-driven Rationale Evaluation for Self-Training), a self-training framework that further evaluates each rationale through follow-up questions and leverages this evaluation to guide its training. Specifically, we introduce two methods: (1) filtering out rationales that frequently result in incorrect answers on follow-up questions and (2) preference learning based on mixed preferences from rationale evaluation results of both original and follow-up questions. Experiments on three question-answering datasets using open LLMs show that CREST not only improves the logical robustness and correctness of rationales but also improves reasoning abilities compared to previous self-training approaches.

[Arxiv](https://arxiv.org/abs/2411.06387)