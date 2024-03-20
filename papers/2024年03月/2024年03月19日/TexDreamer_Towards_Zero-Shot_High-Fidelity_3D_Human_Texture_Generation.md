# TexDreamer，旨在实现无需预先训练、高保真度的三维人体纹理生成技术，直指零样本场景下的高品质表现。

发布时间：2024年03月19日

`Agent` `三维建模` `计算机视觉`

> TexDreamer: Towards Zero-Shot High-Fidelity 3D Human Texture Generation

> 赋予三维人体语义UV贴图是一项挑战，主要难点在于获取合理的UV展开。尽管最近有研究运用大型T2I模型监督多视图渲染取得文本到3D方面的进展，但生成速度慢、文本连贯性差及纹理质量不足等问题依然存在，导致当前数据集普遍存在资源稀少的问题。为此，我们创新推出了首款零样本、高保真、多模态的三维人体纹理生成模型——TexDreamer。它巧妙地采用了高效的纹理适应微调技术，使大型T2I模型既能适应语义UV结构，又能保持其原有的强大泛化性能。同时，凭借独特的特征翻译模块，该训练后的模型能在短短几秒钟内根据文本或图像生成逼真的三维人体纹理。不仅如此，我们还构建了迄今为止最大规模的高分辨率（1024 X 1024）三维人体纹理数据集——ArTicuLated humAn textureS (ATLAS)，该数据集包含5万份附带详细文本描述的高质量纹理资源。

> Texturing 3D humans with semantic UV maps remains a challenge due to the difficulty of acquiring reasonably unfolded UV. Despite recent text-to-3D advancements in supervising multi-view renderings using large text-to-image (T2I) models, issues persist with generation speed, text consistency, and texture quality, resulting in data scarcity among existing datasets. We present TexDreamer, the first zero-shot multimodal high-fidelity 3D human texture generation model. Utilizing an efficient texture adaptation finetuning strategy, we adapt large T2I model to a semantic UV structure while preserving its original generalization capability. Leveraging a novel feature translator module, the trained model is capable of generating high-fidelity 3D human textures from either text or image within seconds. Furthermore, we introduce ArTicuLated humAn textureS (ATLAS), the largest high-resolution (1024 X 1024) 3D human texture dataset which contains 50k high-fidelity textures with text descriptions.

[Arxiv](https://arxiv.org/abs/2403.12906)