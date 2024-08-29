# 借助预训练语言模型的内在知识，我们能够应对复杂的文本分类挑战。

发布时间：2024年08月28日

`LLM应用` `文本分类`

> Harnessing the Intrinsic Knowledge of Pretrained Language Models for Challenging Text Classification Settings

# 摘要

> 文本分类在情感分析和有害内容过滤等应用中至关重要，但自然语言的复杂性和歧义性仍是挑战。深度学习，尤其是transformer和大规模预训练，已在NLP领域取得显著成就。本论文利用预训练语言模型的知识，探索了文本分类的三个难点：首先，针对填补空白问题中的误导性干扰项，我们开发了基于PLMs上下文词表示的模型，性能媲美甚至超越人类。其次，为提升模型对新标签的适应性，我们设计了领域无关的微调数据集，增强性能和鲁棒性。最后，通过精选演示，我们解决了大型模型对学习提示的敏感性，聚焦误分类案例，消除了模型对标签的模糊理解。

> Text classification is crucial for applications such as sentiment analysis and toxic text filtering, but it still faces challenges due to the complexity and ambiguity of natural language. Recent advancements in deep learning, particularly transformer architectures and large-scale pretraining, have achieved inspiring success in NLP fields. Building on these advancements, this thesis explores three challenging settings in text classification by leveraging the intrinsic knowledge of pretrained language models (PLMs). Firstly, to address the challenge of selecting misleading yet incorrect distractors for cloze questions, we develop models that utilize features based on contextualized word representations from PLMs, achieving performance that rivals or surpasses human accuracy. Secondly, to enhance model generalization to unseen labels, we create small finetuning datasets with domain-independent task label descriptions, improving model performance and robustness. Lastly, we tackle the sensitivity of large language models to in-context learning prompts by selecting effective demonstrations, focusing on misclassified examples and resolving model ambiguity regarding test example labels.

[Arxiv](https://arxiv.org/abs/2408.15650)