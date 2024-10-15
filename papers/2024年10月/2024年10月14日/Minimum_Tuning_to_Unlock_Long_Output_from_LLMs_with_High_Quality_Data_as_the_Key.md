# 通过最小调整，以高质量数据为关键，解锁 LLM 的长输出能力

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Minimum Tuning to Unlock Long Output from LLMs with High Quality Data as the Key

# 摘要

> 随着大型语言模型支持的上下文越来越长，它们在生成更长文本方面的能力却参差不齐。最新研究发现，这种差异可能源于对齐训练中缺乏长文本数据。为此，我们尝试用更多长文本数据重新训练模型，使其能按需生成更长内容。本文探讨了数据质量对长文本生成模型调整的影响，并展示了从人类对齐模型出发进行调整的可行性。通过精心筛选数据，我们发现只需少量数据和计算资源，就能显著提升模型性能。我们还测试了这种方法在多个模型上的适用性，结果表明，无论模型初始能力如何，使用高质量数据和轻量计算进行调整，都能带来一致的改进。我们已公开了相关数据集、调整方法和微调模型，供大家自由使用。

> As large language models rapidly evolve to support longer context, there is a notable disparity in their capability to generate output at greater lengths. Recent study suggests that the primary cause for this imbalance may arise from the lack of data with long-output during alignment training. In light of this observation, attempts are made to re-align foundation models with data that fills the gap, which result in models capable of generating lengthy output when instructed. In this paper, we explore the impact of data-quality in tuning a model for long output, and the possibility of doing so from the starting points of human-aligned (instruct or chat) models. With careful data curation, we show that it possible to achieve similar performance improvement in our tuned models, with only a small fraction of training data instances and compute. In addition, we assess the generalizability of such approaches by applying our tuning-recipes to several models. our findings suggest that, while capacities for generating long output vary across different models out-of-the-box, our approach to tune them with high-quality data using lite compute, consistently yields notable improvement across all models we experimented on. We have made public our curated dataset for tuning long-writing capability, the implementations of model tuning and evaluation, as well as the fine-tuned models, all of which can be openly-accessed.

[Arxiv](https://arxiv.org/abs/2410.10210)