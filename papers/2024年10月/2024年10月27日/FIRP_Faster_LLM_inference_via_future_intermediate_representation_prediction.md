# FIRP：借由未来中间表示预测加快 LLM 推理速度

发布时间：2024年10月27日

`LLM应用` `计算机技术`

> FIRP: Faster LLM inference via future intermediate representation prediction

# 摘要

> 近期，大型语言模型（LLMs）取得了显著进步，在众多任务中表现出色。但 LLM 解码的自回归特性（每次前向传播仅生成一个标记）无法充分发挥 GPU 的并行计算能力，造成了较大延迟。为此，我们推出一种名为 FIRP 的全新推测解码方法，它在每个解码步骤能生成多个标记，而非一个。我们通过预测未来标记（尚未解码的标记）的中间隐藏状态来达成此目的，然后利用这些伪隐藏状态来解码未来标记。具体来说，这些伪隐藏状态是在 LLM 的中间层通过简单线性变换预测得出的。一经预测，它们就参与到所有后续层的计算中，进而吸纳更丰富的语义信息。随着层数加深，伪隐藏状态与真实隐藏状态的语义差距缩小，高精度解码未来标记成为可能。为验证 FIRP 的有效性，我们开展了大量实验，在若干模型和数据集中实现了 1.9 倍至 3 倍的加速比，分析实验也证实了我们的初衷。

> Recent advancements in Large Language Models (LLMs) have shown remarkable performance across a wide range of tasks. Despite this, the auto-regressive nature of LLM decoding, which generates only a single token per forward propagation, fails to fully exploit the parallel computational power of GPUs, leading to considerable latency. To address this, we introduce a novel speculative decoding method named FIRP which generates multiple tokens instead of one at each decoding step. We achieve this by predicting the intermediate hidden states of future tokens (tokens have not been decoded yet) and then using these pseudo hidden states to decode future tokens, specifically, these pseudo hidden states are predicted with simple linear transformation in intermediate layers of LLMs. Once predicted, they participate in the computation of all the following layers, thereby assimilating richer semantic information. As the layers go deeper, the semantic gap between pseudo and real hidden states is narrowed and it becomes feasible to decode future tokens with high accuracy. To validate the effectiveness of FIRP, we conduct extensive experiments, showing a speedup ratio of 1.9x-3x in several models and datasets, analytical experiments also prove our motivations.

[Arxiv](https://arxiv.org/abs/2410.20488)