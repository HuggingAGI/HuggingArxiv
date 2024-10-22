# 超越简单过滤：为 MLLM 预训练量身定制的图像与文本质量提升

发布时间：2024年10月21日

`LLM应用` `人工智能` `数据增强`

> Beyond Filtering: Adaptive Image-Text Quality Enhancement for MLLM Pretraining

# 摘要

> 多模态大型语言模型 (MLLM) 通过融合视觉与文本模态取得了重大进展。然而，现有的数据质量增强方法因图像与文本语义对齐不足，常导致大量高质量图像数据被舍弃，影响数据利用效率。为此，我们提出了自适应图像-文本质量增强器 (AITQE)，通过动态评估与提升图像-文本对质量，采用文本重写与负样本学习策略，在最小化文本调整的同时，显著提升数据质量。实验证明，AITQE 在多个基准测试中表现优异，有效利用并扩展了原始数据。我们期待这一创新能激发更多研究。代码与模型已公开，详见：https://github.com/hanhuang22/AITQE。

> Multimodal large language models (MLLMs) have made significant strides by integrating visual and textual modalities. A critical factor in training MLLMs is the quality of image-text pairs within multimodal pretraining datasets. However, $\textit {de facto}$ filter-based data quality enhancement paradigms often discard a substantial portion of high-quality image data due to inadequate semantic alignment between images and texts, leading to inefficiencies in data utilization and scalability. In this paper, we propose the Adaptive Image-Text Quality Enhancer (AITQE), a model that dynamically assesses and enhances the quality of image-text pairs. AITQE employs a text rewriting mechanism for low-quality pairs and incorporates a negative sample learning strategy to improve evaluative capabilities by integrating deliberately selected low-quality samples during training. Unlike prior approaches that significantly alter text distributions, our method minimally adjusts text to preserve data volume while enhancing quality. Experimental results demonstrate that AITQE surpasses existing methods on various benchmark, effectively leveraging raw data and scaling efficiently with increasing data volumes. We hope our work will inspire future works. The code and model are available at: https://github.com/hanhuang22/AITQE.

[Arxiv](https://arxiv.org/abs/2410.16166)