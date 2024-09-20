# 扩展 FP8 训练至万亿 token 的 LLM

发布时间：2024年09月19日

`LLM理论` `人工智能` `半导体`

> Scaling FP8 training to trillion-token LLMs

# 摘要

> 我们首次在高达 2 万亿个标记的数据集上使用 FP8 精度训练大型语言模型，比以往提升了 20 倍。通过这些长时间训练，我们发现了 FP8 训练中的关键不稳定性，这些在早期短时间研究中未被察觉。这些不稳定性源于 SwiGLU 激活函数的异常放大。有趣的是，我们发现这种放大仅在长时间训练中出现，并与 SwiGLU 权重对齐过程相关。为解决这一问题，我们提出了 Smooth-SwiGLU，确保 FP8 训练稳定而不改变函数行为。此外，我们首次实现了 Adam 优化器时刻的 FP8 量化。结合这些创新，我们在 256 个 Intel Gaudi2 加速器上成功训练了 7B 参数模型，性能与 BF16 基线相当，吞吐量提升高达 $\sim 34 \%$。

> We train, for the first time, large language models using FP8 precision on datasets up to 2 trillion tokens -- a 20-fold increase over previous limits. Through these extended training runs, we uncover critical instabilities in FP8 training that were not observable in earlier works with shorter durations. We trace these instabilities to outlier amplification by the SwiGLU activation function. Interestingly, we show, both analytically and empirically, that this amplification happens only over prolonged training periods, and link it to a SwiGLU weight alignment process. To address this newly identified issue, we introduce Smooth-SwiGLU, a novel modification that ensures stable FP8 training without altering function behavior. We also demonstrate, for the first time, FP8 quantization of both Adam optimizer moments. Combining these innovations, we successfully train a 7B parameter model using FP8 precision on 256 Intel Gaudi2 accelerators, achieving on-par results with the BF16 baseline while delivering up to a $\sim 34 \%$ throughput improvement.

[Arxiv](https://arxiv.org/abs/2409.12517)