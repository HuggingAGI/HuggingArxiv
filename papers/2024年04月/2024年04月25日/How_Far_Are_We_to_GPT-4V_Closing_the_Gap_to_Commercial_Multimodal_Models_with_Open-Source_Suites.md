# 我们距离 GPT-4V 还有多远？通过开源工具集，我们正逐步缩小与商业多模态模型之间的差距。

发布时间：2024年04月25日

`分类：LLM应用` `人工智能` `多模态理解`

> How Far Are We to GPT-4V? Closing the Gap to Commercial Multimodal Models with Open-Source Suites

# 摘要

> 本报告向您展示了InternVL 1.5，这是一款开源的多模态大型语言模型（MLLM），致力于缩小开源与商业专有模型在多模态理解领域的能力差距。我们带来了三项创新：（1）强化视觉编码器，通过持续学习策略优化了大规模视觉基础模型InternViT-6B，提升了视觉理解力，并便于在各类大型语言模型中迁移与复用。（2）动态高分辨率处理，根据输入图像的比例和分辨率，将图像分割成448×448像素的1至40块，支持最高4K分辨率的输入。（3）精心构建的高质量双语数据集，覆盖了日常生活场景和文档图像，并配有中英文问答对，显著提升了OCR及中文任务的处理能力。在一系列基准测试和对比研究中，InternVL 1.5与开源及商业模型相比，展现出了竞争力，在18个基准测试中的8个上达到了领先水平。相关代码已在GitHub上发布。

> In this report, we introduce InternVL 1.5, an open-source multimodal large language model (MLLM) to bridge the capability gap between open-source and proprietary commercial models in multimodal understanding. We introduce three simple improvements: (1) Strong Vision Encoder: we explored a continuous learning strategy for the large-scale vision foundation model -- InternViT-6B, boosting its visual understanding capabilities, and making it can be transferred and reused in different LLMs. (2) Dynamic High-Resolution: we divide images into tiles ranging from 1 to 40 of 448$\times$448 pixels according to the aspect ratio and resolution of the input images, which supports up to 4K resolution input. (3) High-Quality Bilingual Dataset: we carefully collected a high-quality bilingual dataset that covers common scenes, document images, and annotated them with English and Chinese question-answer pairs, significantly enhancing performance in OCR- and Chinese-related tasks. We evaluate InternVL 1.5 through a series of benchmarks and comparative studies. Compared to both open-source and proprietary models, InternVL 1.5 shows competitive performance, achieving state-of-the-art results in 8 of 18 benchmarks. Code has been released at https://github.com/OpenGVLab/InternVL.

[Arxiv](https://arxiv.org/abs/2404.16821)