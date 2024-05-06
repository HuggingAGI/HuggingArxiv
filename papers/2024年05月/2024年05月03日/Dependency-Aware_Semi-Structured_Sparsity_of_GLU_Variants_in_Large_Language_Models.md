# 在大型语言模型中，GLU 变种的依赖感知半结构化稀疏性研究

发布时间：2024年05月03日

`LLM理论` `硬件优化`

> Dependency-Aware Semi-Structured Sparsity of GLU Variants in Large Language Models

# 摘要

> 大型语言模型（LLMs）的迅猛进步极大地提升了我们对语言的理解和生成能力。但模型体量的庞大也给硬件带来了挑战，包括服务时的内存需求和令牌生成时的推理延迟。为解决这些问题，我们提出了一种创新的修剪方法——依赖感知半结构化稀疏性（DaSS），专为当前流行的基于SwiGLU的LLMs设计。该方法将结构依赖性整合到基于权重大小的无结构修剪之中，并引入了一种针对多层感知器（MLP）的修剪度量，综合考量权重大小及其对应的MLP中间激活范数来评估权重的重要性。DaSS在无结构修剪的灵活性与依赖性结构修剪的结构一致性之间取得了平衡。在Mistral和LLaMA2模型系列上的实验评估显示，DaSS在实现硬件友好的N:M稀疏模式方面不仅超越了SparseGPT和Wanda，还保持了与Wanda相当的计算效率。

> The rapid advancement in Large Language Models (LLMs) has markedly enhanced the capabilities of language understanding and generation. However, the substantial model size poses hardware challenges, affecting both memory size for serving and inference latency for token generation. To address those challenges, we propose Dependency-aware Semi-structured Sparsity (DaSS), a novel method for the recent prevalent SwiGLU-based LLMs pruning. Our approach incorporates structural dependency into the weight magnitude-based unstructured pruning. We introduce an MLP-specific pruning metric that evaluates the importance of each weight by jointly considering its magnitude and its corresponding MLP intermediate activation norms. DaSS facilitates a balance between the adaptability offered by unstructured pruning and the structural consistency inherent in dependency-based structured pruning. Empirical evaluations on Mistral and LLaMA2 model families demonstrate that DaSS not only outperforms both SparseGPT and Wanda in achieving hardware-friendly N:M sparsity patterns but also maintains the computational efficiency of Wanda.

[Arxiv](https://arxiv.org/abs/2405.01943)