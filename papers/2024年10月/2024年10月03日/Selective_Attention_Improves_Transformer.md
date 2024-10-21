# 选择性注意力让 Transformer 更上一层楼

发布时间：2024年10月03日

`LLM理论` `人工智能`

> Selective Attention Improves Transformer

# 摘要

> 摘要：注意力机制中的不必要元素会拖累性能。我们提出了选择性注意力，这是一种无需额外参数的简单改进，能减少对不必要元素的关注。这种改进在不同模型规模和上下文长度下均提升了语言建模效果。例如，使用选择性注意力训练的变压器在C4数据集上的表现，与标准变压器相当，但后者在注意力模块中使用了近两倍的参数和头数。此外，选择性注意力还能缩小注意力上下文缓冲区，从而在推理时大幅减少内存和计算需求。例如，在C4上训练的100M参数变压器，当上下文大小为512、1024和2048时，配备选择性注意力的变压器在注意力模块中所需的内存分别减少了16倍、25倍和47倍，且验证困惑度保持不变。

> 
Abstract:Unneeded elements in the attention's context degrade performance. We introduce Selective Attention, a simple parameter-free change to the standard attention mechanism which reduces attention to unneeded elements. Selective attention improves language modeling performance in a variety of model sizes and context lengths. For example, a range of transformers trained with the language modeling objective on C4 with selective attention perform equivalently to standard transformers with ~2X more heads and parameters in their attention modules. Selective attention also allows decreasing the size of the attention's context buffer, leading to meaningful reductions in the memory and compute requirements during inference. For example, transformers with 100M parameters trained on C4 with context sizes of 512, 1,024, and 2,048 need 16X, 25X, and 47X less memory for their attention module, respectively, when equipped with selective attention, as those without selective attention, with the same validation perplexity.
    

[Arxiv](https://arxiv.org/pdf/2410.02703)