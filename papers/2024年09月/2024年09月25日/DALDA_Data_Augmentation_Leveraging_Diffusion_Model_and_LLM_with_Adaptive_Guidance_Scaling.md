# DALDA：结合扩散模型与自适应指导缩放的 LLM，实现数据增强

发布时间：2024年09月25日

`LLM应用` `计算机视觉` `数据增强`

> DALDA: Data Augmentation Leveraging Diffusion Model and LLM with Adaptive Guidance Scaling

# 摘要

> 本文介绍了一种利用大型语言模型 (LLM) 和扩散模型 (DM) 的数据增强框架，旨在应对数据稀缺的挑战。DM 近期已能生成合成图像以补充少量训练数据，但增加多样性也带来了偏离目标分布的风险。我们通过 LLM 嵌入新语义信息，并结合真实图像生成语义丰富的合成图像，同时根据 CLIPScore 动态调整指导权重，确保图像符合目标分布。实验显示，该方法在保持目标分布的同时提升了多样性，在少样本设置下表现更佳。代码已公开在 https://github.com/kkyuhun94/dalda。

> In this paper, we present an effective data augmentation framework leveraging the Large Language Model (LLM) and Diffusion Model (DM) to tackle the challenges inherent in data-scarce scenarios. Recently, DMs have opened up the possibility of generating synthetic images to complement a few training images. However, increasing the diversity of synthetic images also raises the risk of generating samples outside the target distribution. Our approach addresses this issue by embedding novel semantic information into text prompts via LLM and utilizing real images as visual prompts, thus generating semantically rich images. To ensure that the generated images remain within the target distribution, we dynamically adjust the guidance weight based on each image's CLIPScore to control the diversity. Experimental results show that our method produces synthetic images with enhanced diversity while maintaining adherence to the target distribution. Consequently, our approach proves to be more efficient in the few-shot setting on several benchmarks. Our code is available at https://github.com/kkyuhun94/dalda .

[Arxiv](https://arxiv.org/abs/2409.16949)