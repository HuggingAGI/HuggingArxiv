# GIFT-SW：为 LLM 的显著权重注入高斯噪声进行微调

发布时间：2024年08月27日

`LLM理论` `人工智能` `软件工程`

> GIFT-SW: Gaussian noise Injected Fine-Tuning of Salient Weights for LLMs

# 摘要

> 参数高效微调 (PEFT) 方法的兴起，让大型语言模型 (LLM) 的使用更加民主化。最新研究发现，少数关键权重对性能影响巨大。据此，我们创新性地提出了显著权重的高斯噪声注入微调 (GIFT-SW) 方法，仅调整关键部分，并在非关键部分加入高斯噪声。为精准识别这些关键部分，我们设计了广义敏感度指标，整合并拓展了以往研究的指标。实验证明，在同等计算资源下，GIFT-SW 表现超越全面微调和其他现代 PEFT 方法。不仅如此，GIFT-SW 还能在保持关键权重全精度的同时，有效恢复受混合精度量化影响的模型性能。

> Parameter Efficient Fine-Tuning (PEFT) methods have gained popularity and democratized the usage of Large Language Models (LLMs). Recent studies have shown that a small subset of weights significantly impacts performance. Based on this observation, we introduce a novel PEFT method, called Gaussian noise Injected Fine Tuning of Salient Weights (GIFT-SW). Our method updates only salient columns, while injecting Gaussian noise into non-salient ones. To identify these columns, we developeda generalized sensitivity metric that extends and unifies metrics from previous studies. Experiments with LLaMA models demonstrate that GIFT-SW outperforms full fine-tuning and modern PEFT methods under the same computational budget. Moreover, GIFT-SW offers practical advantages to recover performance of models subjected to mixed-precision quantization with keeping salient weights in full precision.

[Arxiv](https://arxiv.org/abs/2408.15300)