# 探索视觉-语言地理基础模型：一份综述

发布时间：2024年06月13日

`LLM应用

这篇论文主要探讨了视觉-语言基础模型（VLFMs）在地理空间任务中的应用，特别是在地球观测任务上的改进。论文详细介绍了如何通过构建地理空间图像-文本对数据集并微调VLFMs来创建具有强大地理感知能力的视觉-语言地理基础模型（VLGFMs）。这一研究方向直接关联到大型语言模型（LLM）的应用层面，尤其是在多模态数据处理和特定领域（如地理空间分析）的应用。因此，将其归类为LLM应用是合适的。` `地球观测` `地理信息系统`

> Towards Vision-Language Geo-Foundation Model: A Survey

# 摘要

> 视觉-语言基础模型（VLFMs）在图像描述、图文检索、视觉问答等任务上取得了显著成就，但因缺乏地理空间数据，其在地球观测任务上的表现不尽人意。近期，针对这一问题，研究者们提出了多个地理空间图像-文本对数据集，并在此基础上微调了VLFMs，旨在打造具有强大地理感知能力的视觉-语言地理基础模型（VLGFMs）。本文深入探讨了VLGFMs的发展，详细阐述了其背景、动机及核心技术，包括数据构建、模型架构和多模态地理空间任务的应用，并对未来研究方向进行了展望。这是首次对VLGFMs进行全面综述，相关研究动态可访问https://github.com/zytx121/Awesome-VLGFM。

> Vision-Language Foundation Models (VLFMs) have made remarkable progress on various multimodal tasks, such as image captioning, image-text retrieval, visual question answering, and visual grounding. However, most methods rely on training with general image datasets, and the lack of geospatial data leads to poor performance on earth observation. Numerous geospatial image-text pair datasets and VLFMs fine-tuned on them have been proposed recently. These new approaches aim to leverage large-scale, multimodal geospatial data to build versatile intelligent models with diverse geo-perceptive capabilities, which we refer to as Vision-Language Geo-Foundation Models (VLGFMs). This paper thoroughly reviews VLGFMs, summarizing and analyzing recent developments in the field. In particular, we introduce the background and motivation behind the rise of VLGFMs, highlighting their unique research significance. Then, we systematically summarize the core technologies employed in VLGFMs, including data construction, model architectures, and applications of various multimodal geospatial tasks. Finally, we conclude with insights, issues, and discussions regarding future research directions. To the best of our knowledge, this is the first comprehensive literature review of VLGFMs. We keep tracing related works at https://github.com/zytx121/Awesome-VLGFM.

![探索视觉-语言地理基础模型：一份综述](../../../paper_images/2406.09385/history.png)

![探索视觉-语言地理基础模型：一份综述](../../../paper_images/2406.09385/vlgfm-arch.png)

![探索视觉-语言地理基础模型：一份综述](../../../paper_images/2406.09385/capabilities.png)

![探索视觉-语言地理基础模型：一份综述](../../../paper_images/2406.09385/x1.png)

[Arxiv](https://arxiv.org/abs/2406.09385)