# KOALA 技术通过结合多层草稿头和对抗学习，提升了 LLM 推测解码的性能。

发布时间：2024年08月15日

`LLM应用` `人工智能` `软件开发`

> KOALA: Enhancing Speculative Decoding for LLM via Multi-Layer Draft Heads with Adversarial Learning

# 摘要

> 大型语言模型因自回归解码特性而推理延迟高。本文引入KOALA，通过多层架构和对抗学习，显著提升草稿头预测准确性，虽略增开销，但大幅提升了解码效率。KOALA在多种任务中表现出色，延迟加速比提升至0.24x-0.41x，比原草稿头快10.57%-14.09%。

> Large Language Models (LLMs) exhibit high inference latency due to their autoregressive decoding nature. While the draft head in speculative decoding mitigates this issue, its full potential remains unexplored. In this paper, we introduce KOALA (K-layer Optimized Adversarial Learning Architecture), an orthogonal approach to the draft head. By transforming the conventional single-layer draft head into a multi-layer architecture and incorporating adversarial learning into the traditional supervised training, KOALA significantly improves the accuracy of the draft head in predicting subsequent tokens, thus more closely mirroring the functionality of LLMs. Although this improvement comes at the cost of slightly increased drafting overhead, KOALA substantially unlocks the draft head's potential, greatly enhancing speculative decoding. We conducted comprehensive evaluations of KOALA, including both autoregressive and non-autoregressive draft heads across various tasks, demonstrating a latency speedup ratio improvement of 0.24x-0.41x, which is 10.57%-14.09% faster than the original draft heads.

[Arxiv](https://arxiv.org/abs/2408.08146)