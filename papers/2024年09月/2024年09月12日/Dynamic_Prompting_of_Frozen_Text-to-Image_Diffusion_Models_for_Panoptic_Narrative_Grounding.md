# 动态提示冻结的文本到图像扩散模型，实现全景叙事定位

发布时间：2024年09月12日

`LLM应用` `计算机视觉`

> Dynamic Prompting of Frozen Text-to-Image Diffusion Models for Panoptic Narrative Grounding

# 摘要

> 全景叙事定位 (PNG) 旨在实现图像与文本的细粒度对齐，但现有方法多依赖于全景分割预训练或 CLIP 模型适应，效果有限。随着文本到图像扩散模型的进步，一些研究展示了通过交叉注意力图实现细粒度对齐的潜力。然而，直接将短语特征作为静态提示应用于 PNG 任务，仍面临任务差距和视觉-语言交互不足的问题。为此，我们提出了提取-注入短语适配器 (EIPA)，通过动态更新短语提示并注入多模态线索，更充分地利用扩散模型的对齐能力。同时，设计了多层次相互聚合 (MLMA) 模块，以融合多层次图像和短语特征，提升分割精度。实验结果表明，我们的方法在 PNG 基准上取得了新的最佳性能。

> Panoptic narrative grounding (PNG), whose core target is fine-grained image-text alignment, requires a panoptic segmentation of referred objects given a narrative caption. Previous discriminative methods achieve only weak or coarse-grained alignment by panoptic segmentation pretraining or CLIP model adaptation. Given the recent progress of text-to-image Diffusion models, several works have shown their capability to achieve fine-grained image-text alignment through cross-attention maps and improved general segmentation performance. However, the direct use of phrase features as static prompts to apply frozen Diffusion models to the PNG task still suffers from a large task gap and insufficient vision-language interaction, yielding inferior performance. Therefore, we propose an Extractive-Injective Phrase Adapter (EIPA) bypass within the Diffusion UNet to dynamically update phrase prompts with image features and inject the multimodal cues back, which leverages the fine-grained image-text alignment capability of Diffusion models more sufficiently. In addition, we also design a Multi-Level Mutual Aggregation (MLMA) module to reciprocally fuse multi-level image and phrase features for segmentation refinement. Extensive experiments on the PNG benchmark show that our method achieves new state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2409.08251)