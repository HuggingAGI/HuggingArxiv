# VideoGameBunny：致力于打造视频游戏的视觉助手

发布时间：2024年07月21日

`LLM应用` `视频游戏` `人工智能`

> VideoGameBunny: Towards vision assistants for video games

# 摘要

> 大型多模态模型 (LMMs) 在多个领域展现出巨大潜力，但其在视频游戏领域的应用受限于场景理解、幻觉和内容描述不准确等问题，尤其是在开源模型中。本文介绍了专门针对视频游戏图像理解的 LLaVA 风格模型 VideoGameBunny 的开发。我们公开了中间检查点、训练日志及一个包含 185,259 张游戏图像和 389,565 个图像-指令对的大型数据集。实验显示，我们高质量的游戏数据能使小型模型超越当前最先进的 LLaVa-1.6-34b 模型。此研究为未来游戏理解任务的研究奠定了基础。相关代码和数据已公开。

> Large multimodal models (LMMs) hold substantial promise across various domains, from personal assistance in daily tasks to sophisticated applications like medical diagnostics. However, their capabilities have limitations in the video game domain, such as challenges with scene understanding, hallucinations, and inaccurate descriptions of video game content, especially in open-source models. This paper describes the development of VideoGameBunny, a LLaVA-style model based on Bunny, specifically tailored for understanding images from video games. We release intermediate checkpoints, training logs, and an extensive dataset comprising 185,259 video game images from 413 titles, along with 389,565 image-instruction pairs that include image captions, question-answer pairs, and a JSON representation of 16 elements of 136,974 images. Our experiments show that our high quality game-related data has the potential to make a relatively small model outperform the much larger state-of-the-art model LLaVa-1.6-34b (which has more than 4x the number of parameters). Our study paves the way for future research in video game understanding on tasks such as playing, commentary, and debugging. Code and data are available at https://videogamebunny.github.io/

[Arxiv](https://arxiv.org/abs/2407.15295)