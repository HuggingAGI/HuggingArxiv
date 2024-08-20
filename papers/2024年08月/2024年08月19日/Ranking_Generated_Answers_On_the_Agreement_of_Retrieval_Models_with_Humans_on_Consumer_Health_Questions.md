# 探讨检索模型与人类在消费者健康问题答案排序上的共识

发布时间：2024年08月19日

`LLM应用` `人工智能`

> Ranking Generated Answers: On the Agreement of Retrieval Models with Humans on Consumer Health Questions

# 摘要

> 评估 LLM 生成的内容既具挑战性又难以规模化。当前的评估多聚焦于单选题或文本分类，这些方式无法有效衡量开放式问答能力，而后者在专业领域如医疗中尤为关键，因为错误的答案可能严重影响用户健康。虽然人类专家评估被视为最佳实践，但其成本高昂且效率低下。为此，我们提出一种利用排名信号替代传统相关性判断的评估方法，该方法与专家偏好高度相关。通过验证模型规模与提示策略对答案质量的影响，我们确保了评估的有效性。

> Evaluating the output of generative large language models (LLMs) is challenging and difficult to scale. Most evaluations of LLMs focus on tasks such as single-choice question-answering or text classification. These tasks are not suitable for assessing open-ended question-answering capabilities, which are critical in domains where expertise is required, such as health, and where misleading or incorrect answers can have a significant impact on a user's health. Using human experts to evaluate the quality of LLM answers is generally considered the gold standard, but expert annotation is costly and slow. We present a method for evaluating LLM answers that uses ranking signals as a substitute for explicit relevance judgements. Our scoring method correlates with the preferences of human experts. We validate it by investigating the well-known fact that the quality of generated answers improves with the size of the model as well as with more sophisticated prompting strategies.

[Arxiv](https://arxiv.org/abs/2408.09831)