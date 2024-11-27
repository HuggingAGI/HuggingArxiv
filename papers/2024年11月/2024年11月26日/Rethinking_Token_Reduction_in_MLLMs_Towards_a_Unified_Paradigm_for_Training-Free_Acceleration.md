# 重新思索 MLLMs 中的令牌精简：朝着无训练加速的统一模式迈进

发布时间：2024年11月26日

`LLM应用` `语言模型` `推理加速`

> Rethinking Token Reduction in MLLMs: Towards a Unified Paradigm for Training-Free Acceleration

# 摘要

> 为加速重型多模态大型语言模型（MLLMs）的推理，本研究重新审视了当下无训练的令牌精简研究的局面。令人遗憾的是，我们发现现有方法的关键部分紧密交织，它们之间的关联和效果在比较、迁移及拓展方面尚不清晰。故而，我们提出了统一的“过滤 - 关联 - 压缩”范式，将令牌精简在一个流程中分解为三个不同阶段，保持一致的设计目标和要素，同时允许独特的实现方式。此外，我们揭开了热门作品的神秘面纱，并将其纳入我们的范式，以彰显其通用性。最后，我们基于该范式提供了一系列方法，在推理的不同阶段实现速度与准确性的平衡。在 10 个基准测试中的实验结果表明，我们的方法能够实现高达 82.4%的 FLOPs 削减，对性能的影响极小，同时超越了最先进的无训练方法。我们的项目页面位于 https://ficoco-accelerate.github.io/。

> To accelerate the inference of heavy Multimodal Large Language Models (MLLMs), this study rethinks the current landscape of training-free token reduction research. We regret to find that the critical components of existing methods are tightly intertwined, with their interconnections and effects remaining unclear for comparison, transfer, and expansion. Therefore, we propose a unified ''filter-correlate-compress'' paradigm that decomposes the token reduction into three distinct stages within a pipeline, maintaining consistent design objectives and elements while allowing for unique implementations. We additionally demystify the popular works and subsume them into our paradigm to showcase its universality. Finally, we offer a suite of methods grounded in the paradigm, striking a balance between speed and accuracy throughout different phases of the inference. Experimental results across 10 benchmarks indicate that our methods can achieve up to an 82.4% reduction in FLOPs with a minimal impact on performance, simultaneously surpassing state-of-the-art training-free methods. Our project page is at https://ficoco-accelerate.github.io/.

[Arxiv](https://arxiv.org/abs/2411.17686)