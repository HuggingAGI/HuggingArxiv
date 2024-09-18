# 探究压缩技术如何影响大型语言模型的任务表现

发布时间：2024年09月17日

`LLM理论` `人工智能` `计算机科学`

> Evaluating the Impact of Compression Techniques on Task-Specific Performance of Large Language Models

# 摘要

> 大型语言模型（LLM）虽强大，但计算成本高昂，促使我们寻求高效的压缩技术。本研究针对 LLaMA-2-7B 模型，评估了 Magnitude Pruning、SparseGPT 和 Wanda 等流行压缩方法的效果，特别关注模型大小缩减、下游任务性能及校准数据的作用。研究发现，尽管 SparseGPT 和 Wanda 在 50% 稀疏度下仍保持困惑度，但下游任务性能显著下降，表明困惑度作为唯一评估指标的局限性。为此，我们引入 Jensen-Shannon (JS) Divergence，以更全面地衡量压缩后模型的行为变化。此外，任务特定的校准数据相比通用数据，更能显著提升压缩模型的下游性能。这项研究强调，多样化的评估指标和精心的校准数据选择，对于深入理解 LLM 压缩的复杂性及其对实际应用的影响至关重要。

> Large language models (LLMs) offer powerful capabilities but incur substantial computational costs, driving the need for efficient compression techniques. This study evaluates the impact of popular compression methods - Magnitude Pruning, SparseGPT, and Wanda - on the LLaMA-2-7B model, focusing on the trade-offs between model size reduction, downstream task performance, and the role of calibration data. Our findings reveal that while SparseGPT and Wanda preserve perplexity even at 50% sparsity, they suffer significant degradation on downstream tasks, highlighting the inadequacy of perplexity as the sole evaluation metric. To address this, we introduce Jensen-Shannon (JS) Divergence as a more comprehensive metric that captures nuanced changes in model behavior post-compression. We further demonstrate that task-specific calibration data significantly enhances the downstream performance of compressed models compared to general calibration data. This research underscores the necessity for diverse evaluation metrics and careful calibration data selection to fully understand the complexities of LLM compression and its implications for practical applications.

[Arxiv](https://arxiv.org/abs/2409.11233)