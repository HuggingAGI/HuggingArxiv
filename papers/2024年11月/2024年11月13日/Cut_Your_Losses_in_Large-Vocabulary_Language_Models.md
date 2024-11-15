# 于大词汇量语言模型中降低损失

发布时间：2024年11月13日

`LLM理论` `语言模型` `内存优化`

> Cut Your Losses in Large-Vocabulary Language Models

# 摘要

> 随着语言模型规模不断扩大，其词汇量也随之增长。这导致大型语言模型（LLM）在训练时的内存占用不成比例地集中于一层：损失计算中的交叉熵。交叉熵会为每个输入标记和词汇项的配对构建一个对数矩阵，对于小型模型而言，其消耗的内存比 LLM 的其余部分总和还多一个数量级。我们提出了切割交叉熵（CCE）这一方法，它在计算交叉熵损失时，不会将所有标记的对数概率存入全局内存。相反，CCE 仅计算正确标记的对数概率，并实时评估所有对数概率的对数和指数。我们实现了一个自定义内核，在闪存中对词汇表进行矩阵乘法和对数和指数归约，使交叉熵计算的全局内存消耗几乎可以忽略。这效果显著。以 Gemma 2（2B）模型为例，CCE 将损失计算的内存占用从 24GB 降至 1MB，分类器头部的总训练时间内存消耗从 28GB 减至 1GB。为提升 CCE 的吞吐量，我们借助 softmax 的固有稀疏性，提议跳过对梯度贡献极小（即低于数值精度）的梯度计算元素。实验表明，在不影响训练速度和收敛性的情况下，大幅降低了内存消耗。

> As language models grow ever larger, so do their vocabularies. This has shifted the memory footprint of LLMs during training disproportionately to one single layer: the cross-entropy in the loss computation. Cross-entropy builds up a logit matrix with entries for each pair of input tokens and vocabulary items and, for small models, consumes an order of magnitude more memory than the rest of the LLM combined. We propose Cut Cross-Entropy (CCE), a method that computes the cross-entropy loss without materializing the logits for all tokens into global memory. Rather, CCE only computes the logit for the correct token and evaluates the log-sum-exp over all logits on the fly. We implement a custom kernel that performs the matrix multiplications and the log-sum-exp reduction over the vocabulary in flash memory, making global memory consumption for the cross-entropy computation negligible. This has a dramatic effect. Taking the Gemma 2 (2B) model as an example, CCE reduces the memory footprint of the loss computation from 24 GB to 1 MB, and the total training-time memory consumption of the classifier head from 28 GB to 1 GB. To improve the throughput of CCE, we leverage the inherent sparsity of softmax and propose to skip elements of the gradient computation that have a negligible (i.e., below numerical precision) contribution to the gradient. Experiments demonstrate that the dramatic reduction in memory consumption is accomplished without sacrificing training speed or convergence.

[Arxiv](https://arxiv.org/abs/2411.09009)