# 提高大型语言模型训练稳定性的方法

发布时间：2024年10月22日

`LLM理论` `模型训练`

> Methods of improving LLM training stability

# 摘要

> 大型语言模型（LLMs）的训练稳定性是一个重要的研究课题。重现训练不稳定性可能代价高昂，所以我们使用具有 8.3 亿参数的小型语言模型，并尝试更高的学习率以迫使模型发散。训练不稳定的来源之一是注意力层中 logits 的增长。我们扩展了之前工作的重点，不仅关注 logits 的量级，还关注 Transformer 块中线性层的所有输出。我们观察到，在高学习率下，所有线性层输出的 L2 范数会随着每个训练步骤而增长，并且模型会发散。具体来说，我们观察到 QKV、Proj 和 FC2 层的输出量级增长最大。这促使我们探索几个选项：1）不仅在 QK 层之后应用层归一化，而且在 Proj 和 FC2 层之后也应用；2）在 QKV 层之后应用层归一化（并去除预归一化）；3）应用 QK 层归一化以及 softmax 上限。我们表明，与仅基于 QK 层归一化的方法相比，使用后两种方法我们可以将学习率提高 1.5 倍（模型不会发散）。此外，与基线模型相比，我们观察到所有三种方法的困惑度都有显著改善。

> Training stability of large language models(LLMs) is an important research topic. Reproducing training instabilities can be costly, so we use a small language model with 830M parameters and experiment with higher learning rates to force models to diverge. One of the sources of training instability is the growth of logits in attention layers. We extend the focus of the previous work and look not only at the magnitude of the logits but at all outputs of linear layers in the Transformer block. We observe that with a high learning rate the L2 norm of all linear layer outputs can grow with each training step and the model diverges. Specifically we observe that QKV, Proj and FC2 layers have the largest growth of the output magnitude. This prompts us to explore several options: 1) apply layer normalization not only after QK layers but also after Proj and FC2 layers too; 2) apply layer normalization after the QKV layer (and remove pre normalization). 3) apply QK layer normalization together with softmax capping. We show that with the last two methods we can increase learning rate by 1.5x (without model divergence) in comparison to an approach based on QK layer normalization only. Also we observe significant perplexity improvements for all three methods in comparison to the baseline model.

[Arxiv](https://arxiv.org/abs/2410.16682)