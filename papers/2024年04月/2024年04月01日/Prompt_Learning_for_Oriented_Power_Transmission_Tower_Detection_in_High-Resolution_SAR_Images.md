# 针对高分辨率SAR图像中的定向输电塔检测，本研究采用提示学习方法进行探索。

发布时间：2024年04月01日

`RAG` `目标检测`

> Prompt Learning for Oriented Power Transmission Tower Detection in High-Resolution SAR Images

# 摘要

> 在合成孔径雷达（SAR）图像中识别输电塔是一项挑战，因为塔的尺寸较小，且图像的侧视特性以及背景杂波会干扰识别。众多干扰信号会混入塔的回波中。我们的研究表明，通过定位或提示输电塔的位置，可以有效克服这一难题。据此，本文创新性地将提示学习融入面向目标检测器（P2Det），以实现多模态信息的高效学习。P2Det采用了稀疏提示编码和多模态数据间的交叉注意力机制。其中，特别设计了稀疏提示编码器（SPE）来精确表示点位，将提示转换为稀疏嵌入形式。图像特征则通过Transformer层生成。接着，引入双向融合模块（TWFM）计算两种嵌入的特征交互。通过结合图像级和提示级的特征，有效应对了杂波干扰问题。此外，提出的形状自适应细化模块（SARM）有助于减小宽高比对识别的影响。经过大量实验验证，该模型在处理高分辨率SAR图像时表现出色。P2Det在多模态目标检测领域开辟了新的视角，其卓越的性能表现令人瞩目。

> Detecting transmission towers from synthetic aperture radar (SAR) images remains a challenging task due to the comparatively small size and side-looking geometry, with background clutter interference frequently hindering tower identification. A large number of interfering signals superimposes the return signal from the tower. We found that localizing or prompting positions of power transmission towers is beneficial to address this obstacle. Based on this revelation, this paper introduces prompt learning into the oriented object detector (P2Det) for multimodal information learning. P2Det contains the sparse prompt coding and cross-attention between the multimodal data. Specifically, the sparse prompt encoder (SPE) is proposed to represent point locations, converting prompts into sparse embeddings. The image embeddings are generated through the Transformer layers. Then a two-way fusion module (TWFM) is proposed to calculate the cross-attention of the two different embeddings. The interaction of image-level and prompt-level features is utilized to address the clutter interference. A shape-adaptive refinement module (SARM) is proposed to reduce the effect of aspect ratio. Extensive experiments demonstrated the effectiveness of the proposed model on high-resolution SAR images. P2Det provides a novel insight for multimodal object detection due to its competitive performance.

[Arxiv](https://arxiv.org/abs/2404.01074)