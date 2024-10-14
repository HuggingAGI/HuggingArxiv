# QEFT：通过量化实现 LLM 的高效微调

发布时间：2024年10月11日

`LLM理论` `人工智能` `软件工程`

> QEFT: Quantization for Efficient Fine-Tuning of LLMs

# 摘要

> 随着 LLM 微调的普及，如何在保持高效推理的同时优化微调成为关键。然而，这需要在推理速度、微调速度、内存消耗和模型质量等多方面同时提升，极具挑战。以往研究虽尝试结合量化与微调，但未能全面提升。为此，我们提出高效微调量化 (QEFT) 技术，不仅加速推理与微调，还具备坚实的理论基础、高灵活性和良好的硬件兼容性。实验证明，QEFT 在资源更少的情况下，仍能媲美全精度微调的质量与多功能性。代码已开源，详见 https://github.com/xvyaward/qeft。

> With the rapid growth in the use of fine-tuning for large language models (LLMs), optimizing fine-tuning while keeping inference efficient has become highly important. However, this is a challenging task as it requires improvements in all aspects, including inference speed, fine-tuning speed, memory consumption, and, most importantly, model quality. Previous studies have attempted to achieve this by combining quantization with fine-tuning, but they have failed to enhance all four aspects simultaneously. In this study, we propose a new lightweight technique called Quantization for Efficient Fine-Tuning (QEFT). QEFT accelerates both inference and fine-tuning, is supported by robust theoretical foundations, offers high flexibility, and maintains good hardware compatibility. Our extensive experiments demonstrate that QEFT matches the quality and versatility of full-precision parameter-efficient fine-tuning, while using fewer resources. Our code is available at https://github.com/xvyaward/qeft.

[Arxiv](https://arxiv.org/abs/2410.08661)