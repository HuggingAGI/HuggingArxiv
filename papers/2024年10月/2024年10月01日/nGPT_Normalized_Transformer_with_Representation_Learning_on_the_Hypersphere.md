# nGPT：超球面表示学习的归一化Transformer

发布时间：2024年10月01日

`LLM理论` `人工智能`

> nGPT: Normalized Transformer with Representation Learning on the Hypersphere

# 摘要

> 我们创新性地设计了归一化Transformer（nGPT），其所有向量均在超球面上进行单位范数归一化。输入token在超球面上流动，每层都推动其向目标输出靠近。这些位移由MLP和注意力机制在同一超球面上计算。实验结果显示，nGPT显著加速了学习过程，训练步骤减少4至20倍，具体视序列长度而定。

> 
Abstract:We propose a novel neural network architecture, the normalized Transformer (nGPT) with representation learning on the hypersphere. In nGPT, all vectors forming the embeddings, MLP, attention matrices and hidden states are unit norm normalized. The input stream of tokens travels on the surface of a hypersphere, with each layer contributing a displacement towards the target output predictions. These displacements are defined by the MLP and attention blocks, whose vector components also reside on the same hypersphere. Experiments show that nGPT learns much faster, reducing the number of training steps required to achieve the same accuracy by a factor of 4 to 20, depending on the sequence length.
    

[Arxiv](https://arxiv.org/pdf/2410.01131)