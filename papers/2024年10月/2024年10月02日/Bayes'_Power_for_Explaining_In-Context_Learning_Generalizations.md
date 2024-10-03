# 贝叶斯理论揭示了上下文学习泛化的奥秘

发布时间：2024年10月02日

`LLM理论` `人工智能` `机器学习`

> Bayes' Power for Explaining In-Context Learning Generalizations

# 摘要

> 传统上，神经网络训练被视为最大似然估计 (MLE) 的近似。然而，在大规模单轮训练时代，这种解释显得不足。随着模型变得更加强大，in-context learning (ICL) 成为主导范式。本文提出，神经网络行为应被视为数据生成过程中定义的真实后验的近似。我们展示了这种解释对 ICL 的力量及其对预测先前未见任务泛化的有用性。通过实验，我们揭示了模型如何通过有效组合训练数据中的知识，成为强大的 in-context 学习者。最后，我们探讨了后验泛化能力的固有限制以及神经网络近似这些后验的局限性。

> Traditionally, neural network training has been primarily viewed as an approximation of maximum likelihood estimation (MLE). This interpretation originated in a time when training for multiple epochs on small datasets was common and performance was data bound; but it falls short in the era of large-scale single-epoch trainings ushered in by large self-supervised setups, like language models. In this new setup, performance is compute-bound, but data is readily available. As models became more powerful, in-context learning (ICL), i.e., learning in a single forward-pass based on the context, emerged as one of the dominant paradigms. In this paper, we argue that a more useful interpretation of neural network behavior in this era is as an approximation of the true posterior, as defined by the data-generating process. We demonstrate this interpretations' power for ICL and its usefulness to predict generalizations to previously unseen tasks. We show how models become robust in-context learners by effectively composing knowledge from their training data. We illustrate this with experiments that reveal surprising generalizations, all explicable through the exact posterior. Finally, we show the inherent constraints of the generalization capabilities of posteriors and the limitations of neural networks in approximating these posteriors.

[Arxiv](https://arxiv.org/abs/2410.01565)