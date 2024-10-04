# ControlAR：借助自回归模型实现图像生成的精准操控

发布时间：2024年10月03日

`LLM应用` `图像生成` `计算机视觉`

> ControlAR: Controllable Image Generation with Autoregressive Models

# 摘要

> 自回归 (AR) 模型通过将图像生成重新定义为下一个标记预测，展示了强大的潜力，并成为扩散模型的有力竞争者。然而，类似于 ControlNet 的控制到图像生成在 AR 模型中仍未被充分探索。尽管一种自然的方法是将控制图像标记化并预填充到 AR 模型中，但这种方法在生成质量和效率上仍不如 ControlNet。为此，我们提出了 ControlAR，一个高效且有效的框架，用于将空间控制集成到 AR 图像生成模型中。我们首先提出了一种轻量级的控制编码器，将空间输入转换为控制标记。然后，ControlAR 利用条件解码方法，根据控制标记和图像标记的融合生成下一个图像标记，从而显著增强控制能力并保持效率。此外，ControlAR 还实现了任意分辨率的图像生成。实验证明，ControlAR 在各种输入下的可控性，并超越了现有的最先进模型。代码、模型和演示即将在 GitHub 上发布。

> Autoregressive (AR) models have reformulated image generation as next-token prediction, demonstrating remarkable potential and emerging as strong competitors to diffusion models. However, control-to-image generation, akin to ControlNet, remains largely unexplored within AR models. Although a natural approach, inspired by advancements in Large Language Models, is to tokenize control images into tokens and prefill them into the autoregressive model before decoding image tokens, it still falls short in generation quality compared to ControlNet and suffers from inefficiency. To this end, we introduce ControlAR, an efficient and effective framework for integrating spatial controls into autoregressive image generation models. Firstly, we explore control encoding for AR models and propose a lightweight control encoder to transform spatial inputs (e.g., canny edges or depth maps) into control tokens. Then ControlAR exploits the conditional decoding method to generate the next image token conditioned on the per-token fusion between control and image tokens, similar to positional encodings. Compared to prefilling tokens, using conditional decoding significantly strengthens the control capability of AR models but also maintains the model's efficiency. Furthermore, the proposed ControlAR surprisingly empowers AR models with arbitrary-resolution image generation via conditional decoding and specific controls. Extensive experiments can demonstrate the controllability of the proposed ControlAR for the autoregressive control-to-image generation across diverse inputs, including edges, depths, and segmentation masks. Furthermore, both quantitative and qualitative results indicate that ControlAR surpasses previous state-of-the-art controllable diffusion models, e.g., ControlNet++. Code, models, and demo will soon be available at https://github.com/hustvl/ControlAR.

[Arxiv](https://arxiv.org/abs/2410.02705)