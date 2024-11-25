# 针对大型语言模型的预训练，使用不同语言和质量水平对自然文本数据进行重新表述

发布时间：2024年10月28日

`LLM应用` `多语言处理`

> Rephrasing natural text data with different languages and quality levels for Large Language Model pre-training

# 摘要

> 最近有关为预训练大型语言模型（LLMs）改写自然文本数据的研究成果斐然，将原始数据集与合成改写的数据相结合成效显著。我们在前人的工作基础上，于 C4 重现了已有成果，并凭借优化的改写流程将其拓展至 CulturaX 的英语、德语、意大利语和西班牙语的 Oscar 子集。我们的流程在单语和多语环境下的标准评估基准测试中均提升了性能。另外，我们对该流程展开了细致研究，探究了用于改写的基础数据集和 LLM 的选取，以及模型规模与预训练后性能的关联。通过探索不同感知质量水平的数据，我们发现质量越高，收益越低。而且，我们发现模型家族之间的性能差异比不同模型规模之间的差异更大。这凸显了在选用 LLM 改写大量数据前进行详尽测试的必要性。此外，我们还研究了用合成数据进行预训练对监督微调的影响。在此，我们发现结果虽有提升但不明确，且高度依赖所使用的基准。这些结果（再次）强调了需要更优的基准设置。总之，我们表明改写多语言和低质量数据是拓展 LLM 预训练数据的极有前景的方向。

> Recently published work on rephrasing natural text data for pre-training LLMs has shown promising results when combining the original dataset with the synthetically rephrased data. We build upon previous work by replicating existing results on C4 and extending them with our optimized rephrasing pipeline to the English, German, Italian, and Spanish Oscar subsets of CulturaX. Our pipeline leads to increased performance on standard evaluation benchmarks in both the mono- and multilingual setup. In addition, we provide a detailed study of our pipeline, investigating the choice of the base dataset and LLM for the rephrasing, as well as the relationship between the model size and the performance after pre-training. By exploring data with different perceived quality levels, we show that gains decrease with higher quality. Furthermore, we find the difference in performance between model families to be bigger than between different model sizes. This highlights the necessity for detailed tests before choosing an LLM to rephrase large amounts of data. Moreover, we investigate the effect of pre-training with synthetic data on supervised fine-tuning. Here, we find increasing but inconclusive results that highly depend on the used benchmark. These results (again) highlight the need for better benchmarking setups. In summary, we show that rephrasing multilingual and low-quality data is a very promising direction to extend LLM pre-training data.

[Arxiv](https://arxiv.org/abs/2410.20796)