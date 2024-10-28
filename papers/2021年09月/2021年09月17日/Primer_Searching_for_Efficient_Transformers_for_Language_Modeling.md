# 入门指南：为语言建模寻找高效的 Transformer

发布时间：2021年09月17日

`LLM应用` `模型架构`

> Primer: Searching for Efficient Transformers for Language Modeling

# 摘要

> 摘要：大型 Transformer 模型一直是自然语言处理近期进展的核心。然而，这些模型的训练和推理成本迅速增长，变得极其昂贵。在这里，我们旨在通过寻找更高效的变体来降低 Transformer 的成本。与以前的方法相比，我们的搜索是在更低的级别进行的，是在定义 Transformer TensorFlow 程序的原语上进行的。我们确定了一种名为 Primer 的架构，它在自回归语言建模方面比原始的 Transformer 和其他变体具有更低的训练成本。Primer 的改进主要归因于两个简单的修改：对 ReLU 激活进行平方，以及在自注意力中每个 Q、K 和 V 投影之后添加一个深度卷积层。
实验表明，随着计算规模的增长，Primer 相对于 Transformer 的优势增加，并在最优模型大小方面遵循关于质量的幂律。我们还通过经验验证，Primer 可以放入不同的代码库中，在无需额外调整的情况下显著加快训练速度。例如，在 5 亿参数规模下，Primer 在 C4 自回归语言建模上改进了原始的 T5 架构，将训练成本降低了 4 倍。此外，降低的训练成本意味着 Primer 达到目标一次性性能所需的计算量要少得多。例如，在类似于 GPT-3 XL 的 19 亿参数配置中，Primer 使用 1/3 的训练计算量就能达到与 Transformer 相同的一次性性能。我们开源了我们的模型和 T5 中的几个比较，以帮助重现。

> 
Abstract:Large Transformer models have been central to recent advances in natural language processing. The training and inference costs of these models, however, have grown rapidly and become prohibitively expensive. Here we aim to reduce the costs of Transformers by searching for a more efficient variant. Compared to previous approaches, our search is performed at a lower level, over the primitives that define a Transformer TensorFlow program. We identify an architecture, named Primer, that has a smaller training cost than the original Transformer and other variants for auto-regressive language modeling. Primer's improvements can be mostly attributed to two simple modifications: squaring ReLU activations and adding a depthwise convolution layer after each Q, K, and V projection in self-attention.
Experiments show Primer's gains over Transformer increase as compute scale grows and follow a power law with respect to quality at optimal model sizes. We also verify empirically that Primer can be dropped into different codebases to significantly speed up training without additional tuning. For example, at a 500M parameter size, Primer improves the original T5 architecture on C4 auto-regressive language modeling, reducing the training cost by 4X. Furthermore, the reduced training cost means Primer needs much less compute to reach a target one-shot performance. For instance, in a 1.9B parameter configuration similar to GPT-3 XL, Primer uses 1/3 of the training compute to achieve the same one-shot performance as Transformer. We open source our models and several comparisons in T5 to help with reproducibility.
    

[Arxiv](https://arxiv.org/pdf/2109.08668)