# 大型语言模型实际上是过度参数化的文本编码器。

发布时间：2024年10月18日

`LLM理论` `人工智能`

> Large Language Models Are Overparameterized Text Encoders

# 摘要

> 大型语言模型（LLM）在经过监督对比训练后，作为文本嵌入模型表现出色。然而，其庞大的规模导致推理时间和内存需求激增。本文展示了一种创新方法：在监督训练前，仅通过修剪 LLM 的最后 $p\%$ 层，进行 1000 步训练，即可显著减少内存和推理时间。我们在四种最先进的 LLM 上进行了测试，结果显示，该方法在性能几乎无损的情况下，可修剪多达 30% 的层，甚至在性能仅轻微下降的情况下，修剪高达 80% 的层。仅需三行代码，此方法即可轻松集成到任何将 LLM 转换为文本编码器的流程中。此外，我们提出了 $\text{L}^3 \text{Prune}$，一种基于模型初始损失的层修剪策略，提供两种优化配置：大变体性能损失极小，小变体则适用于资源受限环境。平均而言，大变体修剪 21% 参数，性能仅下降 $-0.3$，而小变体在性能下降 $-5.1$ 的情况下，修剪了 74% 的模型。这些发现有力地证明了 LLM 在文本嵌入任务中存在过度参数化，且易于修剪。

> Large language models (LLMs) demonstrate strong performance as text embedding models when finetuned with supervised contrastive training. However, their large size balloons inference time and memory requirements. In this paper, we show that by pruning the last $p\%$ layers of an LLM before supervised training for only 1000 steps, we can achieve a proportional reduction in memory and inference time. We evaluate four different state-of-the-art LLMs on text embedding tasks and find that our method can prune up to 30\% of layers with negligible impact on performance and up to 80\% with only a modest drop. With only three lines of code, our method is easily implemented in any pipeline for transforming LLMs to text encoders. We also propose $\text{L}^3 \text{Prune}$, a novel layer-pruning strategy based on the model's initial loss that provides two optimal pruning configurations: a large variant with negligible performance loss and a small variant for resource-constrained settings. On average, the large variant prunes 21\% of the parameters with a $-0.3$ performance drop, and the small variant only suffers from a $-5.1$ decrease while pruning 74\% of the model. We consider these results strong evidence that LLMs are overparameterized for text embedding tasks, and can be easily pruned.

[Arxiv](https://arxiv.org/abs/2410.14578)