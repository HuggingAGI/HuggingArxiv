# 稀疏定律：迈向具有更高激活稀疏度的大型语言模型

发布时间：2024年11月04日

`LLM理论` `语言模型` `人工智能`

> Sparsing Law: Towards Large Language Models with Greater Activation Sparsity

# 摘要

> 激活稀疏性指的是在激活输出中存在大量贡献微弱的元素可以被消除，这对许多与大型语言模型（LLM）有关的重要应用有益。尽管在 LLM 中促进更大的激活稀疏性值得深入研究，但现有工作缺乏对激活稀疏性和潜在影响因素之间相关性的全面和定量研究。在本文中，我们对仅解码器基于 Transformer 的 LLM 中激活稀疏性的定量缩放特性和影响因素进行了全面研究。具体来说，我们提出了 PPL - $p\%$ 稀疏性，这是一种精确且性能感知的激活稀疏性度量，适用于任何激活函数。通过大量实验，我们发现了几个重要现象。首先，不同的激活函数表现出相当的性能，但训练时的稀疏性趋势相反。对于 SiLU 激活和 ReLU 激活的 LLM，激活比率（即，$1 - 稀疏比率$）分别随着训练数据量呈现出收敛的递增幂律和递减的对数空间幂律演变。这表明 ReLU 作为激活函数比 SiLU 更高效，并且可以利用更多的训练数据来提高激活稀疏性。其次，激活比率在低于某个瓶颈点的宽深比下线性增加，表明在固定参数规模下更深层次架构的潜在优势。最后，在相似的宽深比下，我们惊讶地发现激活稀疏性的极限值随参数规模的变化微弱，即 LLM 内的激活模式对参数规模不敏感。这些关于具有更大激活稀疏性的 LLM 的经验规律对于使 LLM 更高效和可解释具有重要意义。

> Activation sparsity denotes the existence of substantial weakly-contributed elements within activation outputs that can be eliminated, benefiting many important applications concerned with large language models (LLMs). Although promoting greater activation sparsity within LLMs deserves deep studies, existing works lack comprehensive and quantitative research on the correlation between activation sparsity and potentially influential factors. In this paper, we present a comprehensive study on the quantitative scaling properties and influential factors of the activation sparsity within decoder-only Transformer-based LLMs. Specifically, we propose PPL-$p\%$ sparsity, a precise and performance-aware activation sparsity metric that is applicable to any activation function. Through extensive experiments, we find several important phenomena. Firstly, different activation functions exhibit comparable performance but opposite training-time sparsity trends. The activation ratio (i.e., $1-\mathrm{sparsity\ ratio}$) evolves as a convergent increasing power-law and decreasing logspace power-law with the amount of training data for SiLU-activated and ReLU-activated LLMs, respectively. These demonstrate that ReLU is more efficient as the activation function than SiLU and can leverage more training data to improve activation sparsity. Secondly, the activation ratio linearly increases with the width-depth ratio below a certain bottleneck point, indicating the potential advantage of a deeper architecture at a fixed parameter scale. Finally, at similar width-depth ratios, we surprisingly find that the limit value of activation sparsity varies weakly with the parameter scale, i.e., the activation patterns within LLMs are insensitive to the parameter scale. These empirical laws towards LLMs with greater activation sparsity have important implications for making LLMs more efficient and interpretable.

[Arxiv](https://arxiv.org/abs/2411.02335)