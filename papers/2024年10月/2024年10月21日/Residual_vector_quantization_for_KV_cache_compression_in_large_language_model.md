# 大型语言模型中的 KV 缓存压缩，借助残差向量量化技术实现。

发布时间：2024年10月21日

`LLM应用` `人工智能` `数据压缩`

> Residual vector quantization for KV cache compression in large language model

# 摘要

> KV缓存压缩主要依赖标量量化技术来减少解码时的内存占用。我们引入残差向量量化技术，该技术在音频压缩领域表现出色，用于压缩LLM中的KV缓存。通过微调标准方法，我们实现了对预训练LLM中键值投影矩阵输出的高效压缩：按标准差缩放向量，分组通道，并使用残差向量量化器量化各组。码本通过指数移动平均学习，无其他可学习参数。实验表明，残差深度为8时，模型性能几乎不受影响。此外，非连续通道分组比连续通道分组更有效，且轻量级微调进一步提升了压缩效果。总体而言，该技术简单高效，压缩比达到5.5倍，优于半精度方法。

> KV cache compression methods have mainly relied on scalar quantization techniques to reduce the memory requirements during decoding. In this work, we apply residual vector quantization, which has been widely used for high fidelity audio compression, to compress KV cache in large language models (LLM). We adapt the standard recipe with minimal changes to compress the output of any key or value projection matrix in a pretrained LLM: we scale the vector by its standard deviation, divide channels into groups and then quantize each group with the same residual vector quantizer. We learn the codebook using exponential moving average and there are no other learnable parameters including the input and output projections normally used in a vector quantization set up. We find that a residual depth of 8 recovers most of the performance of the unquantized model. We also find that grouping non-contiguous channels together works better than grouping contiguous channels for compressing key matrix and the method further benefits from a light weight finetuning of LLM together with the quantization. Overall, the proposed technique is competitive with existing quantization methods while being much simpler and results in 5.5x compression compared to half precision.

[Arxiv](https://arxiv.org/abs/2410.15704)