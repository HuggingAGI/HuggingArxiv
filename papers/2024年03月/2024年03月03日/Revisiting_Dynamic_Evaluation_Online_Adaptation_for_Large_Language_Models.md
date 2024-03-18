# [我们重新审视“动态评估”这一概念，探讨其在大型语言模型中的应用——即在线适应策略，以实现模型性能的即时优化与更新。]

发布时间：2024年03月03日

`LLM理论`

> Revisiting Dynamic Evaluation: Online Adaptation for Large Language Models

> 在本次研究中，我们探讨了测试时在线微调语言模型参数——即动态评估这一问题。尽管众所周知，此方法能有效提升总体预测效果，尤其针对训练与评估数据间的分布偏移情况，但我们在此重点阐述了一个新视角：在线调整使参数成为随时间演化的状态，并通过权重中的记忆机制实现了类似神经科学中记忆概念的上下文长度延展。我们特别关注适应速度（体现在样本效率上）、对全局分布漂移的敏感度及进行梯度计算和参数更新带来的计算负担。实证研究表明了在线适应在哪些场景下更具价值。我们强调，随着在线适应的应用，in-context 学习与微调之间的概念界限逐渐模糊，两者实质上都是依据先前观测到的令牌信息来调节模型的方法。

> We consider the problem of online fine tuning the parameters of a language model at test time, also known as dynamic evaluation. While it is generally known that this approach improves the overall predictive performance, especially when considering distributional shift between training and evaluation data, we here emphasize the perspective that online adaptation turns parameters into temporally changing states and provides a form of context-length extension with memory in weights, more in line with the concept of memory in neuroscience. We pay particular attention to the speed of adaptation (in terms of sample efficiency),sensitivity to the overall distributional drift, and the computational overhead for performing gradient computations and parameter updates. Our empirical study provides insights on when online adaptation is particularly interesting. We highlight that with online adaptation the conceptual distinction between in-context learning and fine tuning blurs: both are methods to condition the model on previously observed tokens.

[Arxiv](https://arxiv.org/abs/2403.01518)