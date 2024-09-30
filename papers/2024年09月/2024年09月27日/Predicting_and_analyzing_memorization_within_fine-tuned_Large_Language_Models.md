# 预测并分析微调大型语言模型中的记忆现象

发布时间：2024年09月27日

`LLM理论` `人工智能` `数据安全`

> Predicting and analyzing memorization within fine-tuned Large Language Models

# 摘要

> 大型语言模型因其广泛解决复杂任务的能力备受瞩目，但它们对训练数据的记忆在推理时构成了严重威胁。为了应对这一问题，我们需深入了解记忆的内容及其原因。现有研究多提供事后解释，实际应用价值有限。为此，我们提出了一种基于切片互信息的新方法，能在训练初期高效检测记忆样本，并轻松适应实际需求。该方法得到了新理论的支持，计算成本低廉。实证结果表明，我们的方法为在记忆发生前系统保护这些脆弱样本开辟了新途径。

> Large Language Models have received significant attention due to their abilities to solve a wide range of complex tasks. However these models memorize a significant proportion of their training data, posing a serious threat when disclosed at inference time. To mitigate this unintended memorization, it is crucial to understand what elements are memorized and why. Most existing works provide a posteriori explanations, which has a limited interest in practice. To address this gap, we propose a new approach based on sliced mutual information to detect memorized samples a priori, in a classification setting. It is efficient from the early stages of training, and is readily adaptable to practical scenarios. Our method is supported by new theoretical results that we demonstrate, and requires a low computational budget. We obtain strong empirical results, paving the way for systematic inspection and protection of these vulnerable samples before memorization happens.

[Arxiv](https://arxiv.org/abs/2409.18858)