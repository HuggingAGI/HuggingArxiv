# Transformer 在上下文中学习可变阶马尔可夫链

发布时间：2024年10月07日

`LLM理论` `机器学习`

> Transformers learn variable-order Markov chains in-context

# 摘要

> 大型语言模型展示了强大的 in-context learning (ICL) 能力，但其底层 transformers 如何在复杂场景中实现这一点仍是个谜。最近的研究探讨了 transformers 如何学习固定顺序马尔可夫链 (FOMC)，但自然语言更适合用可变顺序马尔可夫链 (VOMC) 即上下文树 (CTs) 来建模。我们通过将语言建模视为数据压缩，专注于小字母表和低阶 VOMC，利用成熟的压缩算法如 CTW 和 PPM 作为基线。实证发现：1) Transformers 能有效压缩 VOMC，而 PPM 则表现不佳；2) Transformers 性能对层数不敏感，两层即可表现良好；3) 在非 CTW 先验上训练的 transformers 显著优于 CTW 算法。我们分析了 transformers 的注意力机制，提出了两种构造：1) $D+2$ 层构造模仿 CTW 算法；2) 两层构造利用前馈网络进行概率混合。计数机制在 VOMC 中尤为重要。实验表明，这些混合 transformers 不仅匹配了 ICL 性能，甚至在参数减少的情况下表现更佳。

> Large language models have demonstrated impressive in-context learning (ICL) capability. However, it is still unclear how the underlying transformers accomplish it, especially in more complex scenarios. Toward this goal, several recent works studied how transformers learn fixed-order Markov chains (FOMC) in context, yet natural languages are more suitably modeled by variable-order Markov chains (VOMC), i.e., context trees (CTs). In this work, we study the ICL of VOMC by viewing language modeling as a form of data compression and focus on small alphabets and low-order VOMCs. This perspective allows us to leverage mature compression algorithms, such as context-tree weighting (CTW) and prediction by partial matching (PPM) algorithms as baselines, the former of which is Bayesian optimal for a class of CTW priors. We empirically observe a few phenomena: 1) Transformers can indeed learn to compress VOMC in-context, while PPM suffers significantly; 2) The performance of transformers is not very sensitive to the number of layers, and even a two-layer transformer can learn in-context quite well; and 3) Transformers trained and tested on non-CTW priors can significantly outperform the CTW algorithm. To explain these phenomena, we analyze the attention map of the transformers and extract two mechanisms, on which we provide two transformer constructions: 1) A construction with $D+2$ layers that can mimic the CTW algorithm accurately for CTs of maximum order $D$, 2) A 2-layer transformer that utilizes the feed-forward network for probability blending. One distinction from the FOMC setting is that a counting mechanism appears to play an important role. We implement these synthetic transformer layers and show that such hybrid transformers can match the ICL performance of transformers, and more interestingly, some of them can perform even better despite the much-reduced parameter sets.

[Arxiv](https://arxiv.org/abs/2410.05493)