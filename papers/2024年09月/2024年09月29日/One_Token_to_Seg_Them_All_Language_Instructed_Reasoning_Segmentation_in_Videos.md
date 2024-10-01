# 一词分割万物：语言引导的视频推理分割

发布时间：2024年09月29日

`LLM应用` `视频处理` `计算机视觉`

> One Token to Seg Them All: Language Instructed Reasoning Segmentation in Videos

# 摘要

> 我们推出了 VideoLISA，这是一个专为视频语言指导推理分割设计的多模态大型语言模型。通过结合大型语言模型的推理能力和世界知识，并借助 Segment Anything Model 的增强，VideoLISA 能够根据语言指令在视频中生成时间一致的分割掩码。与现有的图像方法不同，VideoLISA 通过集成稀疏密集采样策略，有效应对了视频任务中的时间动态和空间细节挑战。此外，我们创新的 One-Token-Seg-All 方法，利用 <TRK> 令牌，使模型能够跨帧分割和跟踪对象。在多个基准测试中，包括新推出的 ReasonVOS 基准，VideoLISA 展示了其在复杂推理、时间理解和对象跟踪方面的卓越性能。尽管专为视频设计，VideoLISA 在图像分割上也表现出色，显示出其作为统一基础模型的潜力。代码和模型即将在 https://github.com/showlab/VideoLISA 发布。

> We introduce VideoLISA, a video-based multimodal large language model designed to tackle the problem of language-instructed reasoning segmentation in videos. Leveraging the reasoning capabilities and world knowledge of large language models, and augmented by the Segment Anything Model, VideoLISA generates temporally consistent segmentation masks in videos based on language instructions. Existing image-based methods, such as LISA, struggle with video tasks due to the additional temporal dimension, which requires temporal dynamic understanding and consistent segmentation across frames. VideoLISA addresses these challenges by integrating a Sparse Dense Sampling strategy into the video-LLM, which balances temporal context and spatial detail within computational constraints. Additionally, we propose a One-Token-Seg-All approach using a specially designed <TRK> token, enabling the model to segment and track objects across multiple frames. Extensive evaluations on diverse benchmarks, including our newly introduced ReasonVOS benchmark, demonstrate VideoLISA's superior performance in video object segmentation tasks involving complex reasoning, temporal understanding, and object tracking. While optimized for videos, VideoLISA also shows promising generalization to image segmentation, revealing its potential as a unified foundation model for language-instructed object segmentation. Code and model will be available at: https://github.com/showlab/VideoLISA.

[Arxiv](https://arxiv.org/abs/2409.19603)