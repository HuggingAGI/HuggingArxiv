# 合成数据基准的有效性

发布时间：2024年09月18日

`LLM应用` `人工智能`

> Efficacy of Synthetic Data as a Benchmark

# 摘要

> 大型语言模型（LLM）在零-shot 和 few-shot 学习中广泛应用，包括生成用于训练和测试的合成数据集。然而，要可靠使用这些合成数据，必须了解它们与真实数据的代表性。我们通过评估 LLM 生成合成数据并将其用作 NLP 任务基准的有效性来探讨这一点。实验显示，合成数据在简单任务（如意图分类）中表现良好，但在复杂任务（如命名实体识别）中则不尽如人意。我们还提出了“偏差因子”这一新指标，用于评估同一 LLM 生成数据和执行任务时引入的偏差。研究发现，较小的 LLM 对其生成数据有偏见，而较大的模型则没有。总体而言，合成数据作为基准的有效性取决于任务类型，建议从业者尽可能使用多个较大模型生成的数据。

> Large language models (LLMs) have enabled a range of applications in zero-shot and few-shot learning settings, including the generation of synthetic datasets for training and testing. However, to reliably use these synthetic datasets, it is essential to understand how representative they are of real-world data. We investigate this by assessing the effectiveness of generating synthetic data through LLM and using it as a benchmark for various NLP tasks. Our experiments across six datasets, and three different tasks, show that while synthetic data can effectively capture performance of various methods for simpler tasks, such as intent classification, it falls short for more complex tasks like named entity recognition. Additionally, we propose a new metric called the bias factor, which evaluates the biases introduced when the same LLM is used to both generate benchmarking data and to perform the tasks. We find that smaller LLMs exhibit biases towards their own generated data, whereas larger models do not. Overall, our findings suggest that the effectiveness of synthetic data as a benchmark varies depending on the task, and that practitioners should rely on data generated from multiple larger models whenever possible.

[Arxiv](https://arxiv.org/abs/2409.11968)