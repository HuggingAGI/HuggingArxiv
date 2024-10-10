# SWIFT：为 LLM 推理加速而生的即时自我推测解码技术

发布时间：2024年10月09日

`LLM理论` `人工智能`

> SWIFT: On-the-Fly Self-Speculative Decoding for LLM Inference Acceleration

# 摘要

> 推测解码 (SD) 已成为加速大型语言模型 (LLM) 推理的热门方法，且不影响生成质量。它先由紧凑模型高效起草多个标记，再由目标 LLM 并行验证。尽管提速显著，现有方法多需额外参数或广泛训练，限制了其适用性。为此，我们提出一种即插即用的层跳过 SD 方案，跳过 LLM 中间层作为紧凑模型。分析显示，LLM 通过层稀疏性和任务特定稀疏性，具备巨大自我加速潜力。基于此，我们推出 SWIFT，一种实时自适应跳过中间层的自推测解码算法。SWIFT 无需辅助模型或额外训练，适用于各种输入数据流。实验表明，SWIFT 在保持文本原始分布的同时，可实现 1.3 至 1.6 倍的加速。

> Speculative decoding (SD) has emerged as a widely used paradigm to accelerate the inference of large language models (LLMs) without compromising generation quality. It works by first employing a compact model to draft multiple tokens efficiently and then using the target LLM to verify them in parallel. While this technique has achieved notable speedups, most existing approaches necessitate either additional parameters or extensive training to construct effective draft models, thereby restricting their applicability across different LLMs and tasks. To address this limitation, we explore a novel plug-and-play SD solution with layer-skipping, which skips intermediate layers of the target LLM as the compact draft model. Our analysis reveals that LLMs exhibit great potential for self-acceleration through layer sparsity and the task-specific nature of this sparsity. Building on these insights, we introduce SWIFT, an on-the-fly self-speculative decoding algorithm that adaptively selects intermediate layers of LLMs to skip during inference. SWIFT does not require auxiliary models or additional training, making it a plug-and-play solution for accelerating LLM inference across diverse input data streams. Our extensive experiments across a wide range of models and downstream tasks demonstrate that SWIFT can achieve over a 1.3x-1.6x speedup while preserving the original distribution of the generated text.

[Arxiv](https://arxiv.org/abs/2410.06916)