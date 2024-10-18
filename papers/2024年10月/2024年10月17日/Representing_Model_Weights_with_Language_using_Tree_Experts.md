# 借助树专家，以语言形式呈现模型权重

发布时间：2024年10月17日

`LLM理论` `机器学习` `人工智能`

> Representing Model Weights with Language using Tree Experts

# 摘要

> 随着公共模型的增多，我们能否训练以其他网络为输入的神经网络？本文探讨了在联合空间中表示模型的方法，该空间融合了模型权重与语言。然而，模型权重的机器学习颇具挑战，因其常含无关语义属性的显著变化（干扰变化）。我们发现，多数公共模型属于少数模型树，树内模型皆源自同一祖先（如基础模型）微调。有趣的是，树内模型间的干扰变化较少。例如，尽管按训练数据集分类模型通常需复杂架构，我们的单层线性分类器却常奏效。但线性层计算成本高，因模型权重维度极高。为此，我们推出探针专家（ProbeX），一种轻量级探针方法，专为单层模型权重学习设计。我们还构建并发布了模拟公共模型仓库结构的基准数据集。实验表明，ProbeX 能高效地将大型模型权重映射至共享的权重-语言嵌入空间，并展示了其零样本模型分类与检索的强大泛化能力。

> The increasing availability of public models begs the question: can we train neural networks that use other networks as input? This paper learns to represent models within a joint space that embeds both model weights and language. However, machine learning on model weights is challenging as model weights often exhibit significant variation unrelated to the models' semantic properties (nuisance variation). We identify a key property of real-world models: most public models belong to a small set of Model Trees, where all models within a tree are fine-tuned from a common ancestor (e.g., a foundation model). Importantly, we find that within each tree there is less nuisance variation between models. For example, while classifying models according to their training dataset generally requires complex architectures, in our case, even a linear classifier trained on a single layer is often effective. While effective, linear layers are computationally expensive as model weights are very high dimensional. To address this, we introduce Probing Experts (ProbeX), a theoretically motivated, lightweight probing method. Notably, ProbeX is the first probing method designed to learn from the weights of just a single model layer. We also construct and release a dataset that simulates the structure of public model repositories. Our results show that ProbeX can effectively map the weights of large models into a shared weight-language embedding space. Furthermore, we demonstrate the impressive generalization of our method, achieving zero-shot model classification and retrieval.

[Arxiv](https://arxiv.org/abs/2410.13569)