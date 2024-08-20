# 训练后的 Transformer 在基于表示的上下文学习中展现出上下文泛化能力。

发布时间：2024年08月19日

`LLM理论` `人工智能` `机器学习`

> In-Context Learning with Representations: Contextual Generalization of Trained Transformers

# 摘要

> In-context learning (ICL) 是预训练大型语言模型的一项引人注目的能力，它能在推理时通过少量示例掌握新任务。然而，ICL 的理论探索尚浅，尤其是关于变压器能否通过训练泛化到提示中未见示例的问题，这要求模型掌握提示的上下文知识以实现泛化。本文通过非线性回归任务的视角，探讨了变压器通过梯度下降的训练动态。上下文泛化可通过在上下文中学习每个任务的模板函数来实现，这些模板函数位于一个包含 $m$ 个基函数的线性空间中。我们分析了一层多头变压器的训练动态，旨在通过部分标记的提示对未标记输入进行上下文预测，其中标签含噪声，且提示中的示例数量不足以确定模板。在合理假设下，我们证明了一层多头变压器的训练损失能线性收敛至全局最小值。此外，变压器能有效学习在基函数上执行岭回归。据我们所知，这是首个证明变压器能通过学习上下文信息（即模板），在提示仅含少量查询-答案对的情况下，泛化至未见示例和任务的研究。

> In-context learning (ICL) refers to a remarkable capability of pretrained large language models, which can learn a new task given a few examples during inference. However, theoretical understanding of ICL is largely under-explored, particularly whether transformers can be trained to generalize to unseen examples in a prompt, which will require the model to acquire contextual knowledge of the prompt for generalization. This paper investigates the training dynamics of transformers by gradient descent through the lens of non-linear regression tasks. The contextual generalization here can be attained via learning the template function for each task in-context, where all template functions lie in a linear space with $m$ basis functions. We analyze the training dynamics of one-layer multi-head transformers to in-contextly predict unlabeled inputs given partially labeled prompts, where the labels contain Gaussian noise and the number of examples in each prompt are not sufficient to determine the template. Under mild assumptions, we show that the training loss for a one-layer multi-head transformer converges linearly to a global minimum. Moreover, the transformer effectively learns to perform ridge regression over the basis functions. To our knowledge, this study is the first provable demonstration that transformers can learn contextual (i.e., template) information to generalize to both unseen examples and tasks when prompts contain only a small number of query-answer pairs.

[Arxiv](https://arxiv.org/abs/2408.10147)