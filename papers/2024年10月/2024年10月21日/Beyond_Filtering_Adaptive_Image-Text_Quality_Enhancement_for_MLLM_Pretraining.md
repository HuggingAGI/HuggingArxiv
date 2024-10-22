# 不仅仅是过滤：自适应图像与文本质量提升，助力多模态语言模型预训练

发布时间：2024年10月21日

`LLM应用` `人工智能` `计算机视觉`

> Beyond Filtering: Adaptive Image-Text Quality Enhancement for MLLM Pretraining

# 摘要

> 多模态大型语言模型 (MLLM) 通过融合视觉与文本模态取得了重大突破。然而，现有的数据质量增强方法因图像与文本语义对齐不足，常导致大量高质量图像数据被舍弃，影响数据利用效率。为此，我们推出了自适应图像-文本质量增强器 (AITQE)，该模型能动态评估并提升图像-文本对的质量。AITQE 通过文本重写与负样本学习策略，巧妙提升评估能力，同时最小化文本调整，确保数据量不受损。实验证明，AITQE 在多个基准测试中表现优异，能高效利用原始数据并随数据量增长而扩展。我们期待这一创新能激发更多研究。代码与模型已公开，详见：https://github.com/hanhuang22/AITQE。

> Multimodal large language models (MLLMs) have made significant strides by integrating visual and textual modalities. A critical factor in training MLLMs is the quality of image-text pairs within multimodal pretraining datasets. However, $\textit {de facto}$ filter-based data quality enhancement paradigms often discard a substantial portion of high-quality image data due to inadequate semantic alignment between images and texts, leading to inefficiencies in data utilization and scalability. In this paper, we propose the Adaptive Image-Text Quality Enhancer (AITQE), a model that dynamically assesses and enhances the quality of image-text pairs. AITQE employs a text rewriting mechanism for low-quality pairs and incorporates a negative sample learning strategy to improve evaluative capabilities by integrating deliberately selected low-quality samples during training. Unlike prior approaches that significantly alter text distributions, our method minimally adjusts text to preserve data volume while enhancing quality. Experimental results demonstrate that AITQE surpasses existing methods on various benchmark, effectively leveraging raw data and scaling efficiently with increasing data volumes. We hope our work will inspire future works. The code and model are available at: https://github.com/hanhuang22/AITQE.

[Arxiv](https://arxiv.org/abs/2410.16166)