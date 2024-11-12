# 大型语言模型中的超级权重

发布时间：2024年11月11日

`LLM理论` `模型优化`

> The Super Weight in Large Language Models

# 摘要

> 近期的研究工作展示了一个令人惊讶的结果：大型语言模型（LLM）参数中的一小部分异常值对模型的质量有着不成比例的重要性。LLM 包含数十亿个参数，所以这些小部分，比如 0.01%，就相当于数十万个参数。在这项工作中，我们提出了一个更令人惊讶的发现：修剪哪怕仅仅一个参数都可能破坏 LLM 生成文本的能力——使困惑度增加 3 个数量级，并将零样本准确率降低到猜测水平。我们提出了一种无需数据的方法来识别这些参数，称为超级权重，通过模型的单次前向传递来实现。我们还发现这些超级权重会相应地引发罕见且巨大的激活异常值，称为超级激活。当高精度保留时，超级激活可以改进简单的就近取整量化，使其与最先进的方法相竞争。对于权重量化，我们同样发现通过保留超级权重并裁剪其他权重异常值，就近取整量化可以扩展到比以前考虑的大得多的块大小。为了促进对超级权重的进一步研究，我们为常见的、公开可用的 LLM 提供了超级权重坐标的索引。

> Recent works have shown a surprising result: a small fraction of Large Language Model (LLM) parameter outliers are disproportionately important to the quality of the model. LLMs contain billions of parameters, so these small fractions, such as 0.01%, translate to hundreds of thousands of parameters. In this work, we present an even more surprising finding: Pruning as few as a single parameter can destroy an LLM's ability to generate text -- increasing perplexity by 3 orders of magnitude and reducing zero-shot accuracy to guessing. We propose a data-free method for identifying such parameters, termed super weights, using a single forward pass through the model. We additionally find that these super weights induce correspondingly rare and large activation outliers, termed super activations. When preserved with high precision, super activations can improve simple round-to-nearest quantization to become competitive with state-of-the-art methods. For weight quantization, we similarly find that by preserving the super weight and clipping other weight outliers, round-to-nearest quantization can scale to much larger block sizes than previously considered. To facilitate further research into super weights, we provide an index of super weight coordinates for common, openly available LLMs.

[Arxiv](https://arxiv.org/abs/2411.07191)