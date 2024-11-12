# 用统计和近似理论理解关于内在低维数据的 Transformer 神经网络的缩放定律

发布时间：2024年11月10日

`LLM理论`

> Understanding Scaling Laws with Statistical and Approximation Theory for Transformer Neural Networks on Intrinsically Low-dimensional Data

# 摘要

> 在训练深度神经网络时，经常观察到模型的泛化误差遵循一个幂次缩放定律，该定律取决于模型大小和数据大小。也许这种缩放定律最著名的例子是基于 Transformer 的大型语言模型，其中数十亿参数的网络在数万亿的文本标记上进行训练。然而，尽管一直受到广泛关注，但对于为什么存在 Transformer 缩放定律仍缺乏严格的理解。为了回答这个问题，当输入数据集中在低维流形上时，我们为 Transformer 建立了新的统计估计和数学近似理论。我们的理论预测了 Transformer 的泛化误差与训练数据大小和网络大小之间的幂次定律，其中幂次取决于训练数据的内在维度$d$。值得注意的是，构建的模型架构是浅层的，在$d$中只需要对数深度。通过利用流形假设下的低维数据结构，我们能够以尊重数据几何的方式解释 Transformer 缩放定律。此外，我们通过在自然语言数据集上训练大型语言模型来用经验观察检验我们的理论。我们发现观察到的经验数据缩放定律与我们的理论预测密切一致。综上所述，这些结果严格表明数据的内在维度在理论和实践中都是影响 Transformer 缩放定律的关键量。

> When training deep neural networks, a model's generalization error is often observed to follow a power scaling law dependent both on the model size and the data size. Perhaps the best known example of such scaling laws are for transformer-based large language models, where networks with billions of parameters are trained on trillions of tokens of text. Yet, despite sustained widespread interest, a rigorous understanding of why transformer scaling laws exist is still missing. To answer this question, we establish novel statistical estimation and mathematical approximation theories for transformers when the input data are concentrated on a low-dimensional manifold. Our theory predicts a power law between the generalization error and both the training data size and the network size for transformers, where the power depends on the intrinsic dimension $d$ of the training data. Notably, the constructed model architecture is shallow, requiring only logarithmic depth in $d$. By leveraging low-dimensional data structures under a manifold hypothesis, we are able to explain transformer scaling laws in a way which respects the data geometry. Moreover, we test our theory with empirical observation by training LLMs on natural language datasets. We find the observed empirical data scaling laws closely agree with our theoretical predictions. Taken together, these results rigorously show the intrinsic dimension of data to be a crucial quantity affecting transformer scaling laws in both theory and practice.

[Arxiv](https://arxiv.org/abs/2411.06646)