# SAM2 与视频伪装对象分割的相遇：全面评估与适应

发布时间：2024年09月27日

`LLM应用` `视频分析` `计算机视觉`

> When SAM2 Meets Video Camouflaged Object Segmentation: A Comprehensive Evaluation and Adaptation

# 摘要

> 本研究深入探讨了 Segment Anything Model 2 (SAM2) 在视频伪装物体分割 (VCOS) 任务中的应用与表现。VCOS 任务旨在从视频中识别出与背景完美融合的物体，这些物体因颜色和纹理相似、光线不佳等因素而难以察觉。尽管 SAM2 在多种任务中展现了潜力，但在动态伪装场景中的表现仍需进一步探索。我们首先通过不同模型和提示（如点击、框和掩码）评估了 SAM2 在伪装视频数据集上的性能。接着，我们研究了 SAM2 与多模态大语言模型 (MLLMs) 及现有 VCOS 方法的结合。最后，我们通过在视频伪装数据集上微调 SAM2，使其更适应 VCOS 任务。实验结果显示，SAM2 在检测视频伪装物体方面具有卓越的零-shot 能力，并通过参数调整，其性能还能进一步提升。相关代码将在 https://github.com/zhoustan/SAM2-VCOS 上公开。

> This study investigates the application and performance of the Segment Anything Model 2 (SAM2) in the challenging task of video camouflaged object segmentation (VCOS). VCOS involves detecting objects that blend seamlessly in the surroundings for videos, due to similar colors and textures, poor light conditions, etc. Compared to the objects in normal scenes, camouflaged objects are much more difficult to detect. SAM2, a video foundation model, has shown potential in various tasks. But its effectiveness in dynamic camouflaged scenarios remains under-explored. This study presents a comprehensive study on SAM2's ability in VCOS. First, we assess SAM2's performance on camouflaged video datasets using different models and prompts (click, box, and mask). Second, we explore the integration of SAM2 with existing multimodal large language models (MLLMs) and VCOS methods. Third, we specifically adapt SAM2 by fine-tuning it on the video camouflaged dataset. Our comprehensive experiments demonstrate that SAM2 has excellent zero-shot ability of detecting camouflaged objects in videos. We also show that this ability could be further improved by specifically adjusting SAM2's parameters for VCOS. The code will be available at https://github.com/zhoustan/SAM2-VCOS

[Arxiv](https://arxiv.org/abs/2409.18653)