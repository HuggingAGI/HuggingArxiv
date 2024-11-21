# 耐心乃大型语言模型推理之关键所在

发布时间：2024年11月20日

`LLM应用` `语言模型` `推理优化`

> Patience Is The Key to Large Language Model Reasoning

# 摘要

> 近期在大型语言模型领域，尤其是借助思维链（CoT）方法，在解决复杂问题上取得了显著成效。但现有模型要么因用户偏好为求简洁而舍弃详细推理，要么需大量昂贵的训练数据来习得复杂推理能力，这限制了它们解决复杂任务的潜力。为填补此差距，遵循缩放测试时间的理念，我们提出了一种简便方法，鼓励模型采用更具耐心的推理方式，无需引入新知识或技能。采用偏好优化手段，我们将详细推理过程设为正例，简单答案设为反例，以此训练模型使其回答更全面。我们的成果显示，仅在一个轻量数据集上训练，GSM8k 的性能提升高达 6.7%。

> Recent advancements in the field of large language models, particularly through the Chain of Thought (CoT) approach, have demonstrated significant improvements in solving complex problems. However, existing models either tend to sacrifice detailed reasoning for brevity due to user preferences, or require extensive and expensive training data to learn complicated reasoning ability, limiting their potential in solving complex tasks. To bridge this gap, following the concept of scaling test-time, we propose a simple method by encouraging models to adopt a more patient reasoning style without the need of introducing new knowledge or skills. To employ a preference optimization approach, we generate detailed reasoning processes as positive examples and simple answers as negative examples, thereby training the model to favor thoroughness in its responses. Our results demonstrate a performance increase of up to 6.7% on GSM8k with training just on a lightweight dataset.

[Arxiv](https://arxiv.org/abs/2411.13082)