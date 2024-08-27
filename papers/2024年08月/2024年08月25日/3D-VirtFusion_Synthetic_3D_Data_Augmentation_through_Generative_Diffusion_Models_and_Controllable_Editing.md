# 3D-VirtFusion：利用生成扩散模型与可控编辑技术实现合成3D数据增强

发布时间：2024年08月25日

`LLM应用` `计算机视觉`

> 3D-VirtFusion: Synthetic 3D Data Augmentation through Generative Diffusion Models and Controllable Editing

# 摘要

> 数据增强在深度学习中至关重要，提升了模型的泛化与鲁棒性。传统方法通过简单变换如旋转和翻转来扩充数据，但受限于初始数据集的多样性。近期，大型模型如语言模型和扩散模型在感知与内容生成方面表现卓越。我们提出新方法，利用预训练大型模型自动生成3D标记数据。首先，通过扩散模型和chatGPT生成多样化的2D图像。接着，我们不仅增强纹理，还自动改变对象形状，并将其转化为3D对象，构建虚拟场景。此方法无需真实数据，能大量生成3D场景数据，有效应对少样本学习挑战，缓解类别不平衡。我们的工作通过灵活增强，提升了3D数据多样性，增强了模型在场景理解任务中的能力。

> Data augmentation plays a crucial role in deep learning, enhancing the generalization and robustness of learning-based models. Standard approaches involve simple transformations like rotations and flips for generating extra data. However, these augmentations are limited by their initial dataset, lacking high-level diversity. Recently, large models such as language models and diffusion models have shown exceptional capabilities in perception and content generation. In this work, we propose a new paradigm to automatically generate 3D labeled training data by harnessing the power of pretrained large foundation models. For each target semantic class, we first generate 2D images of a single object in various structure and appearance via diffusion models and chatGPT generated text prompts. Beyond texture augmentation, we propose a method to automatically alter the shape of objects within 2D images. Subsequently, we transform these augmented images into 3D objects and construct virtual scenes by random composition. This method can automatically produce a substantial amount of 3D scene data without the need of real data, providing significant benefits in addressing few-shot learning challenges and mitigating long-tailed class imbalances. By providing a flexible augmentation approach, our work contributes to enhancing 3D data diversity and advancing model capabilities in scene understanding tasks.

[Arxiv](https://arxiv.org/abs/2408.13788)