# 循环残差神经网络：迭代细化的利器

发布时间：2024年09月21日

`LLM理论` `人工智能`

> Loop-Residual Neural Networks for Iterative Refinement

# 摘要

> GPT 等大规模语言模型的成功源于其高效预测下一个 token 的能力。然而，这些模型在预测时始终消耗大量计算资源，缺乏迭代优化的灵活性。本文提出了一种创新的 Loop-Residual Neural Network，通过延长计算时间而不扩大模型规模，实现了更优的性能。我们的方法通过多次迭代处理输入，利用残差连接在模型子集上循环优化预测。实验证明，与 GPT-2 相比，我们的模型在语言建模任务中表现更佳，且参数数量相当。更为关键的是，这些提升无需额外训练数据。

> The success of large-scale language models like GPT can be attributed to their ability to efficiently predict the next token in a sequence. However, these models rely on constant computational effort regardless of the complexity of the token they are predicting, lacking the capacity for iterative refinement. In this paper, we introduce a novel Loop-Residual Neural Network, which achieves better performance by utilizing longer computational time without increasing the model size. Our approach revisits the input multiple times, refining the prediction by iteratively looping over a subset of the model with residual connections. We demonstrate the effectiveness of this method through experiments comparing versions of GPT-2 with our Loop-Residual models, showing improved performance in language modeling tasks while maintaining similar parameter counts. Importantly, these improvements are achieved without the need for extra training data.

[Arxiv](https://arxiv.org/abs/2409.14199)