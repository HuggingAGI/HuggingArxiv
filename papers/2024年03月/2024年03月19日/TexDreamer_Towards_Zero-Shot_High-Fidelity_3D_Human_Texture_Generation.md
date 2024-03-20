# TexDreamer——面向零样本高保真三维人体纹理生成技术，旨在无需训练样本的情况下实现逼真生动的三维人体纹理创作。

发布时间：2024年03月19日

`Agent` `3D建模` `计算机图形学`

> TexDreamer: Towards Zero-Shot High-Fidelity 3D Human Texture Generation

> 面对合理UV贴图获取之难，给3D人体添加语义UV贴图仍是一大难题。尽管最近运用大规模文本到图像（T2I）模型来指导多视角渲染的技术有所突破，但在生成速率、文本连贯性及纹理品质等方面的问题依然存在，这也限制了现有数据集的数据丰富度。现在，我们推出了首款零样本、高品质多模态3D人体纹理生成模型——TexDreamer。它采用了高效纹理适应精调技术，既能让大型T2I模型适应语义UV结构，又能保持其原有的广泛适用性。另外，我们创新性地应用特征翻译模块，使得经过训练的模型能够迅速（数秒内）从文本或图像中生成逼真的3D人体纹理。同时，我们还发布了迄今最大分辨率（1024x1024）的3D人体纹理数据集——ArTicuLated humAn textureS (ATLAS)，该数据集包含5万份附有文本描述的高质量纹理资源。

> Texturing 3D humans with semantic UV maps remains a challenge due to the difficulty of acquiring reasonably unfolded UV. Despite recent text-to-3D advancements in supervising multi-view renderings using large text-to-image (T2I) models, issues persist with generation speed, text consistency, and texture quality, resulting in data scarcity among existing datasets. We present TexDreamer, the first zero-shot multimodal high-fidelity 3D human texture generation model. Utilizing an efficient texture adaptation finetuning strategy, we adapt large T2I model to a semantic UV structure while preserving its original generalization capability. Leveraging a novel feature translator module, the trained model is capable of generating high-fidelity 3D human textures from either text or image within seconds. Furthermore, we introduce ArTicuLated humAn textureS (ATLAS), the largest high-resolution (1024 X 1024) 3D human texture dataset which contains 50k high-fidelity textures with text descriptions.

[Arxiv](https://arxiv.org/abs/2403.12906)