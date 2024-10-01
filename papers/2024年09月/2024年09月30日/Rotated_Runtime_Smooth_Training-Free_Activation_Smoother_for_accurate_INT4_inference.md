# 旋转运行时平滑：无需训练的激活平滑技术，助力精准 INT4 推理

发布时间：2024年09月30日

`LLM理论` `人工智能` `云计算`

> Rotated Runtime Smooth: Training-Free Activation Smoother for accurate INT4 inference

# 摘要

> 大型语言模型在参数扩展后展现出强大能力，但其庞大的规模导致服务成本和延迟显著增加。量化方法虽能降低成本，但激活中的异常值却阻碍了 INT4 量化的进展。现有方法或分离异常值，或将异常值迁移，均导致延迟或精度下降。我们观察到异常值可分为通道间和尖峰异常值，并提出旋转运行时平滑（RRS），通过运行时平滑和旋转操作，有效消除异常值，提升量化效果。在 LLaMA 和 Qwen 系列中，RRS 超越了现有技术，将 INT4 推理的 WikiText-2 困惑度大幅降至 6.66。

> Large language models have demonstrated promising capabilities upon scaling up parameters. However, serving large language models incurs substantial computation and memory movement costs due to their large scale. Quantization methods have been employed to reduce service costs and latency. Nevertheless, outliers in activations hinder the development of INT4 weight-activation quantization. Existing approaches separate outliers and normal values into two matrices or migrate outliers from activations to weights, suffering from high latency or accuracy degradation. Based on observing activations from large language models, outliers can be classified into channel-wise and spike outliers. In this work, we propose Rotated Runtime Smooth (RRS), a plug-and-play activation smoother for quantization, consisting of Runtime Smooth and the Rotation operation. Runtime Smooth (RS) is introduced to eliminate channel-wise outliers by smoothing activations with channel-wise maximums during runtime. The rotation operation can narrow the gap between spike outliers and normal values, alleviating the effect of victims caused by channel-wise smoothing. The proposed method outperforms the state-of-the-art method in the LLaMA and Qwen families and improves WikiText-2 perplexity from 57.33 to 6.66 for INT4 inference.

[Arxiv](https://arxiv.org/abs/2409.20361)