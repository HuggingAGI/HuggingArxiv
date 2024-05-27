# 稀疏最大更新参数化：探索稀疏训练动态的全局视角

发布时间：2024年05月24日

`LLM理论

这篇论文主要探讨了稀疏神经网络在大型语言模型（LLM）中的应用问题，并提出了一种新的方法（S$μ$Par）来解决这些问题。该方法通过重新参数化超参数，确保激活、梯度和权重更新独立于稀疏度缩放，从而使得在调整稀疏度和模型宽度时，相同的超参数值仍保持最优。这种方法的提出是为了解决稀疏神经网络在训练过程中遇到的挑战，如权重归零导致的信号传播削弱，以及稀疏度调整的高成本问题。因此，这篇论文的内容更偏向于LLM的理论研究，特别是关于稀疏神经网络在LLM中的优化和改进。` `机器学习` `神经网络`

> Sparse maximal update parameterization: A holistic approach to sparse training dynamics

# 摘要

> 稀疏神经网络面临几大挑战，难以与密集模型匹敌。首先，大量权重归零会削弱前向和梯度信号的传播。其次，稀疏研究需测试多种稀疏度，并引入新超参数，导致调整成本高昂。通常，我们沿用为密集模型设计的学习超参数，但事实证明，稀疏与密集网络的最佳超参数并不相同。缺乏稳定的训练动态和有效方法，大规模测试稀疏度成本高昂，这是超越密集网络并在硬件中实现稀疏加速的关键。为此，我们提出了一种整体方法 S$μ$Par。它确保激活、梯度和权重更新独立于稀疏度缩放，并通过重新参数化超参数，使得在调整稀疏度和模型宽度时，相同的超参数值仍保持最优。这样，超参数可在小型密集网络上调整后，轻松应用于大型稀疏模型，显著降低调整成本。在大规模语言建模中，S$μ$Par 训练相比传统密集模型参数化方法，损失降低了高达 8.2%。

> Several challenges make it difficult for sparse neural networks to compete with dense models. First, setting a large fraction of weights to zero impairs forward and gradient signal propagation. Second, sparse studies often need to test multiple sparsity levels, while also introducing new hyperparameters (HPs), leading to prohibitive tuning costs. Indeed, the standard practice is to re-use the learning HPs originally crafted for dense models. Unfortunately, we show sparse and dense networks do not share the same optimal HPs. Without stable dynamics and effective training recipes, it is costly to test sparsity at scale, which is key to surpassing dense networks and making the business case for sparsity acceleration in hardware. A holistic approach is needed to tackle these challenges and we propose S$μ$Par as one such approach. S$μ$Par ensures activations, gradients, and weight updates all scale independently of sparsity level. Further, by reparameterizing the HPs, S$μ$Par enables the same HP values to be optimal as we vary both sparsity level and model width. HPs can be tuned on small dense networks and transferred to large sparse models, greatly reducing tuning costs. On large-scale language modeling, S$μ$Par training improves loss by up to 8.2% over the common approach of using the dense model standard parameterization.

[Arxiv](https://arxiv.org/abs/2405.15743)