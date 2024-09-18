# Phidias：一款结合文本、图像和 3D 条件，通过参考增强扩散技术生成 3D 内容的创新模型。

发布时间：2024年09月17日

`LLM应用` `3D建模`

> Phidias: A Generative Model for Creating 3D Content from Text, Image, and 3D Conditions with Reference-Augmented Diffusion

# 摘要

> 在3D建模领域，设计师常以现有模型为蓝本创造新作。这一实践催生了Phidias——一种利用扩散技术进行参考增强的3D生成模型。通过一张图像，我们的方法借助检索或用户提供的3D参考模型，精准引导生成过程，大幅提升生成质量、泛化性与操控性。模型内含三大核心组件：动态调节条件强度的元控制网络、校正输入图像与3D参考错位的动态路由机制，以及支持渐进式自监督训练的自参考增强功能。这些创新设计使得Phidias在众多现有方法中脱颖而出。Phidias构建了一个融合文本、图像与3D条件的3D生成统一框架，应用前景广阔。

> In 3D modeling, designers often use an existing 3D model as a reference to create new ones. This practice has inspired the development of Phidias, a novel generative model that uses diffusion for reference-augmented 3D generation. Given an image, our method leverages a retrieved or user-provided 3D reference model to guide the generation process, thereby enhancing the generation quality, generalization ability, and controllability. Our model integrates three key components: 1) meta-ControlNet that dynamically modulates the conditioning strength, 2) dynamic reference routing that mitigates misalignment between the input image and 3D reference, and 3) self-reference augmentations that enable self-supervised training with a progressive curriculum. Collectively, these designs result in a clear improvement over existing methods. Phidias establishes a unified framework for 3D generation using text, image, and 3D conditions with versatile applications.

[Arxiv](https://arxiv.org/abs/2409.11406)