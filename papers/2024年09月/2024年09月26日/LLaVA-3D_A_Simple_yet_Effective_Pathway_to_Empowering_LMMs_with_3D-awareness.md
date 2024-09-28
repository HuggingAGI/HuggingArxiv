# LLaVA-3D：为大型多模态模型赋予3D感知能力的简易而高效之道

发布时间：2024年09月26日

`LLM应用` `计算机视觉` `人工智能`

> LLaVA-3D: A Simple yet Effective Pathway to Empowering LMMs with 3D-awareness

# 摘要

> 大型多模态模型 (LMM) 在 2D 视觉理解任务中的表现有了显著提升，能够高效处理和理解图像与视频。然而，由于缺乏大规模 3D 视觉语言数据集和强大 3D 编码器，LMM 在 3D 场景理解方面的发展受阻。本文提出 LLaVA-3D 框架，借助 LLaVA 的 2D 理解优势，高效适应 3D 场景理解，同时保持 2D 能力。我们引入 3D Patch，将 2D CLIP 特征与 3D 空间位置结合，通过联合 2D 和 3D 视觉语言指令调整，构建统一架构。实验显示，LLaVA-3D 在 3D 视觉语言数据集上的训练速度比现有 3D LMM 快 3.5 倍，且在 3D 任务中表现卓越，2D 图像理解和视觉语言对话能力也与 LLaVA 相当。

> Recent advancements in Large Multimodal Models (LMMs) have greatly enhanced their proficiency in 2D visual understanding tasks, enabling them to effectively process and understand images and videos. However, the development of LMMs with 3D-awareness for 3D scene understanding has been hindered by the lack of large-scale 3D vision-language datasets and powerful 3D encoders. In this paper, we introduce a simple yet effective framework called LLaVA-3D. Leveraging the strong 2D understanding priors from LLaVA, our LLaVA-3D efficiently adapts LLaVA for 3D scene understanding without compromising 2D understanding capabilities. To achieve this, we employ a simple yet effective representation, 3D Patch, which connects 2D CLIP patch features with their corresponding positions in 3D space. By integrating the 3D Patches into 2D LMMs and employing joint 2D and 3D vision-language instruction tuning, we establish a unified architecture for both 2D image understanding and 3D scene understanding. Experimental results show that LLaVA-3D converges 3.5x faster than existing 3D LMMs when trained on 3D vision-language datasets. Moreover, LLaVA-3D not only achieves state-of-the-art performance across various 3D tasks but also maintains comparable 2D image understanding and vision-language conversation capabilities with LLaVA.

[Arxiv](https://arxiv.org/abs/2409.18125)