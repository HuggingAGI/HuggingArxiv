# 利用密集斑点表示实现文本至图像的组合生成

发布时间：2024年05月13日

`LLM应用

这篇论文介绍了一种结合大型语言模型（LLM）的文本到图像生成方法，名为BlobGEN。该方法通过使用斑点表示（blob representations）来细化场景，并利用一种新的掩码交叉注意力机制来融合斑点表示和视觉特征。此外，论文还提出了一种上下文学习策略，以从文本提示中直接生成斑点表示，从而利用LLM的组合潜力。这种方法在组合图像生成任务中展示了高质量的生成结果和精细的布局控制，特别是在与LLMs结合使用时。因此，这篇论文属于LLM应用类别，因为它展示了如何将LLM应用于特定的NLP任务——文本到图像的生成。` `图像生成` `人工智能`

> Compositional Text-to-Image Generation with Dense Blob Representations

# 摘要

> 现有的文本到图像模型在处理复杂文本提示时显得力不从心，这促使我们寻求更精细的控制手段。本研究提出了一种创新方法，将场景细化为一系列视觉原语——密集斑点表示，这些表示不仅捕捉了场景的微妙细节，而且具有模块化、易于人类理解且便于构建的特点。我们基于此开发了 BlobGEN，一种结合斑点表示的文本到图像扩散模型，用于组合图像生成。特别地，我们设计了一种新的掩码交叉注意力机制，以确保斑点表示与视觉特征的融合更加清晰。为了充分发挥大型语言模型的组合潜力，我们采用了一种新颖的上下文学习策略，直接从文本提示中生成斑点表示。实验结果显示，BlobGEN 在 MS-COCO 数据集上不仅实现了零-shot 生成质量的飞跃，还提供了更精细的布局控制。当与 LLMs 结合使用时，我们的方法在组合图像生成任务中展现了卓越的数值和空间准确性。更多详情，请访问项目页面：https://blobgen-2d.github.io。

> Existing text-to-image models struggle to follow complex text prompts, raising the need for extra grounding inputs for better controllability. In this work, we propose to decompose a scene into visual primitives - denoted as dense blob representations - that contain fine-grained details of the scene while being modular, human-interpretable, and easy-to-construct. Based on blob representations, we develop a blob-grounded text-to-image diffusion model, termed BlobGEN, for compositional generation. Particularly, we introduce a new masked cross-attention module to disentangle the fusion between blob representations and visual features. To leverage the compositionality of large language models (LLMs), we introduce a new in-context learning approach to generate blob representations from text prompts. Our extensive experiments show that BlobGEN achieves superior zero-shot generation quality and better layout-guided controllability on MS-COCO. When augmented by LLMs, our method exhibits superior numerical and spatial correctness on compositional image generation benchmarks. Project page: https://blobgen-2d.github.io.

[Arxiv](https://arxiv.org/abs/2405.08246)