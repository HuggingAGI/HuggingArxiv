# Top-$nσ$: 并非所有的对数概率值都是您所需要的

发布时间：2024年11月12日

`LLM理论` `语言模型` `推理任务`

> Top-$nσ$: Not All Logits Are You Need

# 摘要

> 大型语言模型（LLMs）通常在推理任务中采用贪心解码或低温采样，反映出在多样性和准确性之间存在一种被认为的权衡。我们通过引入 top-$nσ$ 来挑战这一惯例，这是一种直接在预 softmax 对数几率上操作的新采样方法，利用了统计阈值。我们的关键见解是，对数几率自然地分为高斯分布的噪声区域和一个独特的信息区域，能够在无需复杂概率操作的情况下实现有效的标记过滤。与现有的方法（例如 top-$p$、min-$p$）不同，这些方法在较高温度下无意中包含了更多的噪声标记，top-$nσ$ 无论温度如何缩放都保持稳定的采样空间。我们还对 top-$nσ$ 进行了理论分析，以更好地理解其行为。在四个以推理为重点的数据集上的广泛实验结果表明，我们的方法不仅优于现有的采样方法，而且超过了贪心解码，同时即使在高温下也能保持稳定的性能。

> Large language models (LLMs) typically employ greedy decoding or low-temperature sampling for reasoning tasks, reflecting a perceived trade-off between diversity and accuracy. We challenge this convention by introducing top-$nσ$, a novel sampling method that operates directly on pre-softmax logits by leveraging a statistical threshold. Our key insight is that logits naturally separate into a Gaussian-distributed noisy region and a distinct informative region, enabling efficient token filtering without complex probability manipulations. Unlike existing methods (e.g., top-$p$, min-$p$) that inadvertently include more noise tokens at higher temperatures, top-$nσ$ maintains a stable sampling space regardless of temperature scaling. We also provide a theoretical analysis of top-$nσ$ to better understand its behavior. The extensive experimental results across four reasoning-focused datasets demonstrate that our method not only outperforms existing sampling approaches but also surpasses greedy decoding, while maintaining consistent performance even at high temperatures.

[Arxiv](https://arxiv.org/abs/2411.07641)