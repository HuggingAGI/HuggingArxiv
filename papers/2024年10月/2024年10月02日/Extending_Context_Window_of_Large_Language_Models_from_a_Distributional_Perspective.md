# 从分布视角探讨如何扩展大型语言模型的上下文窗口

发布时间：2024年10月02日

`LLM理论` `人工智能`

> Extending Context Window of Large Language Models from a Distributional Perspective

# 摘要

> 扩展 RoPE 已成为提升 LLM 上下文窗口的常用手段。然而，现有方法多依赖经验，对 RoPE 内部分布理解不足，导致扩展效果不佳。本文提出从旋转角度分布入手，优化上下文窗口扩展任务。首先，我们估算模型中旋转角度的分布，分析长度扩展对其的影响。接着，提出一种新策略，通过最小化旋转角度分布的扰动，确保与预训练阶段的一致性，提升模型对长序列的泛化能力。实验显示，与强基线方法相比，扩展 LLaMA2 上下文窗口至 8k 时，分布扰动减少 72%；扩展至 16k 时，减少 32%。在 LongBench-E 基准测试中，性能提升高达 4.33%。此外，扩展后在 Hugging Face Open LLM 基准测试中，模型性能保持稳定，波动范围仅在 -0.12 到 +0.22 之间。

> Scaling the rotary position embedding (RoPE) has become a common method for extending the context window of RoPE-based large language models (LLMs). However, existing scaling methods often rely on empirical approaches and lack a profound understanding of the internal distribution within RoPE, resulting in suboptimal performance in extending the context window length. In this paper, we propose to optimize the context window extending task from the view of rotary angle distribution. Specifically, we first estimate the distribution of the rotary angles within the model and analyze the extent to which length extension perturbs this distribution. Then, we present a novel extension strategy that minimizes the disturbance between rotary angle distributions to maintain consistency with the pre-training phase, enhancing the model's capability to generalize to longer sequences. Experimental results compared to the strong baseline methods demonstrate that our approach reduces by up to 72% of the distributional disturbance when extending LLaMA2's context window to 8k, and reduces by up to 32% when extending to 16k. On the LongBench-E benchmark, our method achieves an average improvement of up to 4.33% over existing state-of-the-art methods. Furthermore, Our method maintains the model's performance on the Hugging Face Open LLM benchmark after context window extension, with only an average performance fluctuation ranging from -0.12 to +0.22.

[Arxiv](https://arxiv.org/abs/2410.01490)