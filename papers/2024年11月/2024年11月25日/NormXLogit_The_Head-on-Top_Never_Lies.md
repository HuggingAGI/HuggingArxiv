# NormXLogit: 头顶之处从不骗人

发布时间：2024年11月25日

`LLM理论` `模型可解释性`

> NormXLogit: The Head-on-Top Never Lies

# 摘要

> Transformer 架构已成为构建大型语言模型（LLMs）的首选。不过，鉴于新的 LLMs 不断涌现，思考能在多种架构中提供可解释性的架构无关方法的潜在价值至关重要。尽管 LLMs 的可解释性近来有所突破，但许多现有方法依赖复杂手段，往往与特定模型设计挂钩，且计算成本颇高。为克服这些局限，我们提出了一种名为 NormXLogit 的新技术，用于评估单个输入标记的重要性。此方法依据与每个标记相关的输入和输出表示运作。首先，我们证实，在 LLMs 的预训练阶段，词嵌入的范数能捕捉输入标记的重要性。其次，我们揭示了标记的重要性与其表示和模型最终预测的相似程度之间存在显著关联。经过大量分析，我们表明，我们的方法在忠诚度方面始终优于现有的基于梯度的方法。另外，在分层解释方面，我们的方法比最出色的特定架构方法表现更优。

> The Transformer architecture has emerged as the dominant choice for building large language models (LLMs). However, with new LLMs emerging on a frequent basis, it is important to consider the potential value of architecture-agnostic approaches that can provide interpretability across a variety of architectures. Despite recent successes in the interpretability of LLMs, many existing approaches rely on complex methods that are often tied to a specific model design and come with a significant computational cost. To address these limitations, we propose a novel technique, called NormXLogit, for assessing the significance of individual input tokens. This method operates based on the input and output representations associated with each token. First, we demonstrate that during the pre-training of LLMs, the norms of word embeddings capture the importance of input tokens. Second, we reveal a significant relationship between a token's importance and the extent to which its representation can resemble the model's final prediction. Through extensive analysis, we show that our approach consistently outperforms existing gradient-based methods in terms of faithfulness. Additionally, our method achieves better performance in layer-wise explanations compared to the most prominent architecture-specific methods.

[Arxiv](https://arxiv.org/abs/2411.16252)