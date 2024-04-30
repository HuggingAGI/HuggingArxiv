# 先删后加，学习图像编辑新技巧：Inpaint的智能绘画教学

发布时间：2024年04月28日

`分类：LLM应用` `图像编辑` `人工智能`

> Paint by Inpaint: Learning to Add Image Objects by Removing Them First

# 摘要

> 文本条件扩散模型的推出极大推动了图像编辑技术的发展。然而，依据文本指令在图像中无缝添加对象，且无需用户提供输入遮罩，这一任务依然充满挑战。我们通过洞察到移除对象（修复）比添加对象（绘画）更为简单，利用这一原理，结合分割掩码数据集和修复模型，实现了在掩码区域内的修复。基于这一认识，我们构建了一个自动化的流程，创建了一个精选的大规模图像数据集，包含了原始图像及其去除了对象的对应版本。利用这些图像对，我们训练了一个扩散模型，以逆转修复过程，从而在图像中有效添加对象。与其它编辑数据集相比，我们的集锦采用了更自然的图像，并且在源图像和目标图像之间通过构建保持了一致性。此外，我们还采用了一个大型视觉-语言模型来详细描述被移除的对象，并通过一个大型语言模型将这些描述转换成多样化的自然语言指令。我们证明，我们训练的模型在质量和数量上都超越了现有模型，并且我们已经将这个大规模数据集和训练好的模型公开，供社区使用。

> Image editing has advanced significantly with the introduction of text-conditioned diffusion models. Despite this progress, seamlessly adding objects to images based on textual instructions without requiring user-provided input masks remains a challenge. We address this by leveraging the insight that removing objects (Inpaint) is significantly simpler than its inverse process of adding them (Paint), attributed to the utilization of segmentation mask datasets alongside inpainting models that inpaint within these masks. Capitalizing on this realization, by implementing an automated and extensive pipeline, we curate a filtered large-scale image dataset containing pairs of images and their corresponding object-removed versions. Using these pairs, we train a diffusion model to inverse the inpainting process, effectively adding objects into images. Unlike other editing datasets, ours features natural target images instead of synthetic ones; moreover, it maintains consistency between source and target by construction. Additionally, we utilize a large Vision-Language Model to provide detailed descriptions of the removed objects and a Large Language Model to convert these descriptions into diverse, natural-language instructions. We show that the trained model surpasses existing ones both qualitatively and quantitatively, and release the large-scale dataset alongside the trained models for the community.

[Arxiv](https://arxiv.org/abs/2404.18212)