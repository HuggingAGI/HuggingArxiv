# 以伦理为导向：通过轻量级优化实现文本到图像合成的价值对齐

发布时间：2024年10月16日

`LLM应用` `图像生成` `人工智能伦理`

> Embedding an Ethical Mind: Aligning Text-to-Image Synthesis via Lightweight Value Optimization

# 摘要

> 近期，扩散模型在大规模数据训练下，已能生成逼真的人类水平图像，但常产出与人类价值观相悖的有害内容，如社会偏见和冒犯性图像。尽管大型语言模型 (LLM) 研究广泛，文本到图像 (T2I) 模型的对齐问题仍待深入。为此，我们推出 LiVO (轻量级价值优化)，一种新颖的轻量级方法，旨在将 T2I 模型与人类价值观对齐。LiVO 通过优化即插即用的价值编码器，将特定价值原则融入输入提示，从而精准控制生成图像的语义与价值。我们设计了扩散模型专用的偏好优化损失，理论近似 LLM 对齐中的 Bradley-Terry 模型，但更灵活地平衡图像质量与价值一致性。此外，我们开发框架，自动构建包含 86k 样本的文本图像偏好数据集，优化价值编码器。LiVO 在不大幅更新模型参数的前提下，显著减少有害输出，加速收敛，超越多个强基线，为道德对齐的 T2I 模型奠定基础。

> Recent advancements in diffusion models trained on large-scale data have enabled the generation of indistinguishable human-level images, yet they often produce harmful content misaligned with human values, e.g., social bias, and offensive content. Despite extensive research on Large Language Models (LLMs), the challenge of Text-to-Image (T2I) model alignment remains largely unexplored. Addressing this problem, we propose LiVO (Lightweight Value Optimization), a novel lightweight method for aligning T2I models with human values. LiVO only optimizes a plug-and-play value encoder to integrate a specified value principle with the input prompt, allowing the control of generated images over both semantics and values. Specifically, we design a diffusion model-tailored preference optimization loss, which theoretically approximates the Bradley-Terry model used in LLM alignment but provides a more flexible trade-off between image quality and value conformity. To optimize the value encoder, we also develop a framework to automatically construct a text-image preference dataset of 86k (prompt, aligned image, violating image, value principle) samples. Without updating most model parameters and through adaptive value selection from the input prompt, LiVO significantly reduces harmful outputs and achieves faster convergence, surpassing several strong baselines and taking an initial step towards ethically aligned T2I models.

[Arxiv](https://arxiv.org/abs/2410.12700)