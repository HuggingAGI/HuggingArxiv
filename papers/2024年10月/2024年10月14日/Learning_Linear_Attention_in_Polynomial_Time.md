# 在多项式时间内学习线性注意力

发布时间：2024年10月14日

`LLM理论` `计算机科学` `人工智能`

> Learning Linear Attention in Polynomial Time

# 摘要

> 摘要：先前的研究已经探索了 Transformer 模型在模拟布尔电路或图灵机方面的计算表现力。然而，从观测数据中学习这些模拟器的能力仍然是一个未解决的问题。我们的研究通过为具有线性注意力的单层 Transformer 提供首个多项式时间可学习性结果（特别是强、不可知 PAC 学习）来解决这一差距。我们表明，线性注意力可以在适当定义的 RKHS 中被视为线性预测器。因此，学习任何线性 Transformer 的问题可以转化为在扩展特征空间中学习普通线性预测器的问题，并且任何这样的预测器都可以转换回多头线性 Transformer。谈到泛化，我们展示了如何有效地识别训练数据集，对于这些数据集，每个经验风险最小化器都等同于（在琐碎的对称性范围内）生成数据的线性 Transformer，从而保证学习的模型将在所有输入上正确泛化。最后，我们提供了通过线性注意力可表达并且因此可在多项式时间内学习的计算示例，包括联想记忆、有限自动机和一类具有多项式有界计算历史的通用图灵机（UTM）。我们在三个任务上对我们的理论发现进行了实证验证：学习随机线性注意力网络、键值关联和学习执行有限自动机。我们的发现弥合了 Transformer 理论表现力和可学习性之间的关键差距，并表明灵活和通用的计算模型是可以有效学习的。

> 
Abstract:Previous research has explored the computational expressivity of Transformer models in simulating Boolean circuits or Turing machines. However, the learnability of these simulators from observational data has remained an open question. Our study addresses this gap by providing the first polynomial-time learnability results (specifically strong, agnostic PAC learning) for single-layer Transformers with linear attention. We show that linear attention may be viewed as a linear predictor in a suitably defined RKHS. As a consequence, the problem of learning any linear transformer may be converted into the problem of learning an ordinary linear predictor in an expanded feature space, and any such predictor may be converted back into a multiheaded linear transformer. Moving to generalization, we show how to efficiently identify training datasets for which every empirical risk minimizer is equivalent (up to trivial symmetries) to the linear Transformer that generated the data, thereby guaranteeing the learned model will correctly generalize across all inputs. Finally, we provide examples of computations expressible via linear attention and therefore polynomial-time learnable, including associative memories, finite automata, and a class of Universal Turing Machine (UTMs) with polynomially bounded computation histories. We empirically validate our theoretical findings on three tasks: learning random linear attention networks, key--value associations, and learning to execute finite automata. Our findings bridge a critical gap between theoretical expressivity and learnability of Transformers, and show that flexible and general models of computation are efficiently learnable.
    

[Arxiv](https://arxiv.org/pdf/2410.10101)