# 贝叶斯低秩适配大型语言模型的高斯随机权重平均法

发布时间：2024年05月06日

`LLM理论` `机器学习`

> Gaussian Stochastic Weight Averaging for Bayesian Low-Rank Adaptation of Large Language Models

# 摘要

> 微调后的LLMs在面对小型数据集时，容易出现过度自信和校准不准确的问题。为应对这些难题，我们提出了一种结合低秩适应（LoRA）与高斯随机权重平均（SWAG）的简洁方案，以实现LLMs的近似贝叶斯推理。经过多个NLP基准的广泛测试，我们证实了这一方法在提升模型泛化和校准方面的效果显著，且计算效率极高。此外，我们还发现该方法在面对分布偏移时展现出更强的鲁棒性，尤其是在处理分布外任务时的性能表现。

> Fine-tuned Large Language Models (LLMs) often suffer from overconfidence and poor calibration, particularly when fine-tuned on small datasets. To address these challenges, we propose a simple combination of Low-Rank Adaptation (LoRA) with Gaussian Stochastic Weight Averaging (SWAG), facilitating approximate Bayesian inference in LLMs. Through extensive testing across several Natural Language Processing (NLP) benchmarks, we demonstrate that our straightforward and computationally efficient approach improves model generalization and calibration. We further show that our method exhibits greater robustness against distribution shift, as reflected in its performance on out-of-distribution tasks.

[Arxiv](https://arxiv.org/abs/2405.03425)