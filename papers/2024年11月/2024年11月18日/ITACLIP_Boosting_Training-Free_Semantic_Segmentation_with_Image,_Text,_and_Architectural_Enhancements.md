# ITACLIP：借助图像、文本和架构方面的增强来促进无训练语义分割

发布时间：2024年11月18日

`LLM应用` `计算机视觉` `语义分割`

> ITACLIP: Boosting Training-Free Semantic Segmentation with Image, Text, and Architectural Enhancements

# 摘要

> 近期基础视觉语言模型（VLMs）的进步重塑了计算机视觉任务的评估范式。其中，尤其是 CLIP 这类基础模型，加速了开放词汇计算机视觉任务的研究，像开放词汇语义分割（OVSS）。虽说初步成果不错，但 VLMs 的密集预测能力仍有待提升。本研究通过引入新模块和做出修改来增强 CLIP 的语义分割性能：1）对 ViT 最后一层进行架构调整，并将中间层的注意力图与最后一层相结合；2）图像工程：运用数据增强丰富输入图像的表示；3）利用大型语言模型（LLMs）为每个类别名称生成定义和同义词，以发挥 CLIP 的开放词汇能力。我们的无训练方法 ITACLIP 在 COCO-Stuff、COCO-Object、Pascal Context 和 Pascal VOC 等分割基准上的表现优于当前的先进方法。我们的代码可在 https://github.com/m-arda-aydn/ITACLIP 获取。

> Recent advances in foundational Vision Language Models (VLMs) have reshaped the evaluation paradigm in computer vision tasks. These foundational models, especially CLIP, have accelerated research in open-vocabulary computer vision tasks, including Open-Vocabulary Semantic Segmentation (OVSS). Although the initial results are promising, the dense prediction capabilities of VLMs still require further improvement. In this study, we enhance the semantic segmentation performance of CLIP by introducing new modules and modifications: 1) architectural changes in the last layer of ViT and the incorporation of attention maps from the middle layers with the last layer, 2) Image Engineering: applying data augmentations to enrich input image representations, and 3) using Large Language Models (LLMs) to generate definitions and synonyms for each class name to leverage CLIP's open-vocabulary capabilities. Our training-free method, ITACLIP, outperforms current state-of-the-art approaches on segmentation benchmarks such as COCO-Stuff, COCO-Object, Pascal Context, and Pascal VOC. Our code is available at https://github.com/m-arda-aydn/ITACLIP.

[Arxiv](https://arxiv.org/abs/2411.12044)