# DreamClear：通过隐私安全的数据集策划实现高容量的真实世界图像恢复

发布时间：2024年10月24日

`其他` `图像恢复` `数据管理`

> DreamClear: High-Capacity Real-World Image Restoration with Privacy-Safe Dataset Curation

# 摘要

> 在现实场景中的图像恢复（IR）由于缺乏高容量模型和综合数据集而面临重大挑战。为了解决这些问题，我们提出了双重策略：GenIR，一种创新的数据管理管道，和 DreamClear，一个基于前沿扩散变压器（DiT）的图像恢复模型。GenIR，我们开创性的贡献，是一个双提示学习管道，克服了现有数据集的局限性，这些数据集通常仅包含几千张图像，因此对于较大的模型可推广性有限。GenIR 将流程简化为三个阶段：图像 - 文本对构建、基于双提示的微调以及数据生成和过滤。这种方法避免了繁琐的数据抓取过程，确保版权合规，并为 IR 数据集构建提供了一种经济高效、隐私安全的解决方案。结果是一个包含一百万个高质量图像的大规模数据集。我们的第二个贡献，DreamClear，是一个基于 DiT 的图像恢复模型。它利用了文本到图像（T2I）扩散模型的生成先验和多模态大型语言模型（MLLMs）强大的感知能力来实现逼真的恢复。为了提高模型对各种现实世界退化的适应性，我们引入了自适应调制器的混合物（MoAM）。它采用基于标记的退化先验来动态集成各种恢复专家，从而扩大了模型可以处理的退化范围。我们详尽的实验证实了 DreamClear 的卓越性能，强调了我们的双重策略在现实世界图像恢复中的有效性。代码和预训练模型将在：https://github.com/shallowdream204/DreamClear 提供。

> Image restoration (IR) in real-world scenarios presents significant challenges due to the lack of high-capacity models and comprehensive datasets. To tackle these issues, we present a dual strategy: GenIR, an innovative data curation pipeline, and DreamClear, a cutting-edge Diffusion Transformer (DiT)-based image restoration model. GenIR, our pioneering contribution, is a dual-prompt learning pipeline that overcomes the limitations of existing datasets, which typically comprise only a few thousand images and thus offer limited generalizability for larger models. GenIR streamlines the process into three stages: image-text pair construction, dual-prompt based fine-tuning, and data generation & filtering. This approach circumvents the laborious data crawling process, ensuring copyright compliance and providing a cost-effective, privacy-safe solution for IR dataset construction. The result is a large-scale dataset of one million high-quality images. Our second contribution, DreamClear, is a DiT-based image restoration model. It utilizes the generative priors of text-to-image (T2I) diffusion models and the robust perceptual capabilities of multi-modal large language models (MLLMs) to achieve photorealistic restoration. To boost the model's adaptability to diverse real-world degradations, we introduce the Mixture of Adaptive Modulator (MoAM). It employs token-wise degradation priors to dynamically integrate various restoration experts, thereby expanding the range of degradations the model can address. Our exhaustive experiments confirm DreamClear's superior performance, underlining the efficacy of our dual strategy for real-world image restoration. Code and pre-trained models will be available at: https://github.com/shallowdream204/DreamClear.

[Arxiv](https://arxiv.org/abs/2410.18666)