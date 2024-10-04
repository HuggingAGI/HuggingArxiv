# CodePMP：为大型语言模型推理提供可扩展的偏好模型预训练

发布时间：2024年10月03日

`LLM理论` `软件开发` `人工智能`

> CodePMP: Scalable Preference Model Pretraining for Large Language Model Reasoning

# 摘要

> 大型语言模型 (LLM) 在自然语言理解和生成方面取得了显著进展，这得益于可扩展的预训练和先进的微调。然而，增强 LLM 的推理能力，特别是通过从人类反馈中进行强化学习 (RLHF)，仍然具有挑战性，因为高质量偏好数据的稀缺性，这些数据需要大量劳动力进行注释，并且对奖励模型 (RM) 微调至关重要。为了缓解这个问题，我们引入了 CodePMP，这是一个可扩展的偏好模型预训练 (PMP) 管道，利用从公开可用的高质量源代码中合成的大量代码-偏好对。CodePMP 通过在大规模合成的代码-偏好对上预训练偏好模型，提高了 RM 微调的效率。我们在数学推理任务 (GSM8K, MATH) 和逻辑推理任务 (ReClor, LogiQA2.0) 上评估了 CodePMP，一致显示 LLM 的推理性能显著提高，并强调了可扩展偏好模型预训练对高效奖励建模的重要性。

> Large language models (LLMs) have made significant progress in natural language understanding and generation, driven by scalable pretraining and advanced finetuning. However, enhancing reasoning abilities in LLMs, particularly via reinforcement learning from human feedback (RLHF), remains challenging due to the scarcity of high-quality preference data, which is labor-intensive to annotate and crucial for reward model (RM) finetuning. To alleviate this issue, we introduce CodePMP, a scalable preference model pretraining (PMP) pipeline that utilizes a large corpus of synthesized code-preference pairs from publicly available high-quality source code. CodePMP improves RM finetuning efficiency by pretraining preference models on large-scale synthesized code-preference pairs. We evaluate CodePMP on mathematical reasoning tasks (GSM8K, MATH) and logical reasoning tasks (ReClor, LogiQA2.0), consistently showing significant improvements in reasoning performance of LLMs and highlighting the importance of scalable preference model pretraining for efficient reward modeling.

[Arxiv](https://arxiv.org/abs/2410.02229)