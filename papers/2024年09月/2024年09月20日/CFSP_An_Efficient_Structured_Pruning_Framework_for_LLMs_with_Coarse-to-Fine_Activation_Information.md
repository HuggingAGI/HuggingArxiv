# CFSP：一种高效的大型语言模型结构化剪枝框架，通过粗到细的激活信息实现优化。

发布时间：2024年09月20日

`LLM理论` `人工智能` `计算机硬件`

> CFSP: An Efficient Structured Pruning Framework for LLMs with Coarse-to-Fine Activation Information

# 摘要

> 大型语言模型（LLM）因其庞大的参数和计算开销，在实际应用中面临挑战。网络剪枝技术通过移除冗余参数，实现非结构化或结构化稀疏，为LLM加速提供了新思路。现有研究多聚焦于非结构化剪枝，但这种技术通常需要特殊硬件支持才能实现实际提速。相比之下，结构化剪枝在通用设备上即可减少延迟，但其高效实施并保持性能仍具挑战，尤其是在高稀疏比率下。为此，我们推出了CFSP框架，巧妙结合粗粒度（块间）与细粒度（块内）激活信息，作为剪枝的重要依据。该框架仅需一次前向传递计算特征激活，高效便捷。具体操作上，我们首先根据块的重要性分配稀疏预算，再在各块内保留关键权重。此外，我们还设计了自适应微调策略，根据粗粒度重要性动态调整训练开销，进一步提升性能。实验证明，CFSP在多种模型和稀疏预算下均表现优异，超越了现有方法。代码即将在https://github.com/wyxscir/CFSP发布。

> The colossal parameters and computational overhead of Large Language Models (LLMs) challenge their real-world applications. Network pruning, which targets unstructured or structured sparsity by removing redundant parameters, has recently been explored for LLM acceleration. Existing LLM pruning works focus on unstructured pruning, which typically requires special hardware support for a practical speed-up. In contrast, structured pruning can reduce latency on general devices. However, it remains a challenge to perform structured pruning efficiently and maintain performance, especially at high sparsity ratios. To this end, we introduce an efficient structured pruning framework named CFSP, which leverages both Coarse (interblock) and Fine-grained (intrablock) activation information as an importance criterion to guide pruning. The pruning is highly efficient, as it only requires one forward pass to compute feature activations. Specifically, we first allocate the sparsity budget across blocks based on their importance and then retain important weights within each block. In addition, we introduce a recovery fine-tuning strategy that adaptively allocates training overhead based on coarse-grained importance to further improve performance. Experimental results demonstrate that CFSP outperforms existing methods on diverse models across various sparsity budgets. Our code will be available at https://github.com/wyxscir/CFSP.

[Arxiv](https://arxiv.org/abs/2409.13199)