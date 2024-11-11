# 回收注意力：长上下文语言模型的高效推理

发布时间：2024年11月08日

`LLM应用` `语言模型` `推理加速`

> Recycled Attention: Efficient inference for long-context language models

# 摘要

> 给定一个长上下文输入来生成长序列的标记会给大型语言模型（LLM）带来沉重的计算负担。其中一个计算瓶颈来自于在每个生成步骤中对长序列输入进行注意力计算。在本文中，我们提出了“回收注意力”，这是一种推理时的方法，它在全上下文注意力和对输入标记子集的注意力之间交替。在执行部分注意力时，我们回收之前执行全注意力的标记的注意力模式，并且只关注前 K 个最受关注的标记，降低了数据移动和注意力计算的成本。与之前提出的仅关注局部上下文或具有高累积注意力分数的标记的推理时加速方法相比，我们的方法灵活地选择与当前解码步骤相关的标记。我们在 RULER 上评估我们的方法，RULER 是一套旨在全面评估长上下文能力和长上下文语言建模任务的任务集。将我们的方法应用于现成的 LLM，实现了与仅考虑局部上下文的基线相当的加速，同时将性能提高了 2 倍。我们进一步探索了两个想法来改进性能 - 效率权衡：（1）根据查询相似度动态决定何时执行回收或全注意力步骤，（2）使用“回收注意力”继续对模型进行预训练。

> Generating long sequences of tokens given a long-context input imposes a heavy computational burden for large language models (LLMs). One of the computational bottleneck comes from computing attention over a long sequence of input at each generation step. In this paper, we propose Recycled Attention, an inference-time method which alternates between full context attention and attention over a subset of input tokens. When performing partial attention, we recycle the attention pattern of a previous token that has performed full attention and attend only to the top K most attended tokens, reducing the cost of data movement and attention computation. Compared to previously proposed inference-time acceleration method which attends only to local context or tokens with high accumulative attention scores, our approach flexibly chooses tokens that are relevant to the current decoding step. We evaluate our methods on RULER, a suite of tasks designed to comprehensively evaluate long-context abilities, and long-context language modeling tasks. Applying our method to off-the-shelf LLMs achieves comparable speedup to baselines which only consider local context while improving the performance by 2x. We further explore two ideas to improve performance-efficiency trade-offs: (1) dynamically decide when to perform recycled or full attention step based on the query similarities and (2) continued pre-training the model with Recycled Attention.

[Arxiv](https://arxiv.org/abs/2411.05787)