# Rodimus*：以高效注意力打破准确性与效率的平衡

发布时间：2024年10月09日

`LLM理论` `人工智能`

> Rodimus*: Breaking the Accuracy-Efficiency Trade-Off with Efficient Attentions

# 摘要

> Transformer 大型语言模型 (LLM) 的最新进展为自然语言处理设定了新标杆。然而，传统 softmax 注意力机制的高计算成本导致每个 token 生成的复杂度为 $O(T)$。为此，我们引入了 Rodimus 及其升级版 Rodimus$^+$，旨在降低复杂性并保持性能。Rodimus 通过创新的线性注意力框架中的数据依赖温度选择 (DDTS) 机制，不仅提高了准确性，还大幅减少了内存使用。Rodimus$^+$ 则进一步融合了滑动窗口共享键注意力 (SW-SKA)，有效整合了多种压缩技术。实验显示，Rodimus$+$-1.6B 在下游任务中表现优异，超越了 Qwen2-1.5B 和 RWKV6-1.6B 等模型，展现了其在平衡准确性与效率方面的潜力。模型代码和预训练模型即将发布。

> Recent advancements in Transformer-based large language models (LLMs) have set new standards in natural language processing. However, the classical softmax attention incurs significant computational costs, leading to a $O(T)$ complexity for per-token generation, where $T$ represents the context length. This work explores reducing LLMs' complexity while maintaining performance by introducing Rodimus and its enhanced version, Rodimus$+$. Rodimus employs an innovative data-dependent tempered selection (DDTS) mechanism within a linear attention-based, purely recurrent framework, achieving significant accuracy while drastically reducing the memory usage typically associated with recurrent models. This method exemplifies semantic compression by maintaining essential input information with fixed-size hidden states. Building on this, Rodimus$+$ combines Rodimus with the innovative Sliding Window Shared-Key Attention (SW-SKA) in a hybrid approach, effectively leveraging the complementary semantic, token, and head compression techniques. Our experiments demonstrate that Rodimus$+$-1.6B, trained on 1 trillion tokens, achieves superior downstream performance against models trained on more tokens, including Qwen2-1.5B and RWKV6-1.6B, underscoring its potential to redefine the accuracy-efficiency balance in LLMs. Model code and pre-trained checkpoints will be available soon.

[Arxiv](https://arxiv.org/abs/2410.06577)