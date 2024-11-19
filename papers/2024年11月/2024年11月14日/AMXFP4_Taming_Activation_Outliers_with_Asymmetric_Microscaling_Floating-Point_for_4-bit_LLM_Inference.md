# AMXFP4：借助非对称微缩放浮点数来驯服 4 位 LLM 推理中的激活异常值

发布时间：2024年11月14日

`LLM应用` `语言模型` `量化技术`

> AMXFP4: Taming Activation Outliers with Asymmetric Microscaling Floating-Point for 4-bit LLM Inference

# 摘要

> 随着大型语言模型（LLMs）扩展上下文长度规模的增大，对高效低比特量化的需求也随之增加，以应对其庞大的计算需求。然而，将精度降至 4 位往往会因激活异常值而导致性能下降。为此，我们提出了用于高效 LLM 推理的非对称微缩放 4 位浮点数（AMXFP4）。这种新型数据格式借助非对称共享尺度来缓解异常值，同时自然地捕捉到分组量化所引入的不对称性。有别于依赖数据旋转和高成本校准的传统 4 位量化方法，AMXFP4 采用非对称共享尺度进行直接 4 位转换，在多轮对话、长上下文推理和视觉问答等各类 LLM 任务中实现了近乎理想的量化精度。我们的 AMXFP4 格式大幅超越 MXFP4 及其他领先的量化技术，实现了强大且无需校准的 4 位推理。

> Scaling Large Language Models (LLMs) with extended context lengths has increased the need for efficient low-bit quantization to manage their substantial computational demands. However, reducing precision to 4 bits frequently degrades performance due to activation outliers. To address this, we propose Asymmetric Microscaling 4-bit Floating-Point (AMXFP4) for efficient LLM inference. This novel data format leverages asymmetric shared scales to mitigate outliers while naturally capturing the asymmetry introduced by group-wise quantization. Unlike conventional 4-bit quantization methods that rely on data rotation and costly calibration, AMXFP4 uses asymmetric shared scales for direct 4-bit casting, achieving near-ideal quantization accuracy across various LLM tasks, including multi-turn conversations, long-context reasoning, and visual question answering. Our AMXFP4 format significantly outperforms MXFP4 and other leading quantization techniques, enabling robust, calibration-free 4-bit inference.

[Arxiv](https://arxiv.org/abs/2411.09909)