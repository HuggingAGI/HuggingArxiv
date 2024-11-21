# MemoryFormer：借由移除全连接层以最小化 Transformer 计算量

发布时间：2024年11月19日

`LLM应用` `计算机` `人工智能`

> MemoryFormer: Minimize Transformer Computation by Removing Fully-Connected Layers

# 摘要

> 为降低大型语言模型的计算复杂度，人们大力提升诸如线性注意力和闪存注意力等变压器模型的效率。但为追求更优性能，模型规模与相应的计算复杂度持续攀升。在此工作中，我们推出了 MemoryFormer，这一全新的变压器架构从新视角显著降低了计算复杂度（FLOPs）。我们几乎剔除了变压器模型的所有计算，只保留多头注意力操作必需的计算。这通过采用替代特征变换方法取代全连接层的线性投影得以实现。具体而言，我们先构建一组内存查找表，存储大量离散向量以替代线性投影所用的权重矩阵。接着，运用哈希算法依据输入嵌入动态检索相关向量子集。检索到的向量组合起来形成输出嵌入，能估算全连接层中矩阵乘法运算的结果。相较于进行矩阵乘法，从内存中检索数据块的操作成本低得多，计算量小。我们从零开始训练 MemoryFormer，并在各类基准上开展广泛实验，以证实所提模型的有效性。

> In order to reduce the computational complexity of large language models, great efforts have been made to to improve the efficiency of transformer models such as linear attention and flash-attention. However, the model size and corresponding computational complexity are constantly scaled up in pursuit of higher performance. In this work, we present MemoryFormer, a novel transformer architecture which significantly reduces the computational complexity (FLOPs) from a new perspective. We eliminate nearly all the computations of the transformer model except for the necessary computation required by the multi-head attention operation. This is made possible by utilizing an alternative method for feature transformation to replace the linear projection of fully-connected layers. Specifically, we first construct a group of in-memory lookup tables that store a large amount of discrete vectors to replace the weight matrix used in linear projection. We then use a hash algorithm to retrieve a correlated subset of vectors dynamically based on the input embedding. The retrieved vectors combined together will form the output embedding, which provides an estimation of the result of matrix multiplication operation in a fully-connected layer. Compared to conducting matrix multiplication, retrieving data blocks from memory is a much cheaper operation which requires little computations. We train MemoryFormer from scratch and conduct extensive experiments on various benchmarks to demonstrate the effectiveness of the proposed model.

[Arxiv](https://arxiv.org/abs/2411.12992)