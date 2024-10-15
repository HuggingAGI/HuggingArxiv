# Free Video-LLM：通过提示引导的视觉感知，实现无需训练的高效视频语言模型

发布时间：2024年10月14日

`LLM应用` `视频处理` `人工智能`

> Free Video-LLM: Prompt-guided Visual Perception for Efficient Training-free Video LLMs

# 摘要

> 视觉-语言大型模型在多模态任务中表现出色，但应用于视频理解仍面临挑战，主要因为视频数据的复杂性和高计算需求。虽然基于训练的视频-LLMs 性能卓越，但其训练和推理成本高昂。相比之下，无需训练的方法通过调整预训练的图像-LLMs 模型来处理视频任务，无需额外训练，但受限于大量视觉标记的生成。为此，我们提出了一种新颖的提示引导视觉感知框架（简称 \emph{Free Video-LLM}），专门用于无需训练的视频 LLMs 的高效推理。该框架通过解耦时空维度，并根据任务特定提示分别进行时间帧采样和空间 RoI 裁剪，有效减少了视觉标记数量，同时保持了高水平的性能。实验证明，我们的方法在减少标记数量的同时，仍能与最先进的视频 LLMs 相媲美，实现了准确性与计算效率的最佳平衡。相关代码将在 \url{https://github.com/contrastive/FreeVideoLLM} 上发布。

> Vision-language large models have achieved remarkable success in various multi-modal tasks, yet applying them to video understanding remains challenging due to the inherent complexity and computational demands of video data. While training-based video-LLMs deliver high performance, they often require substantial resources for training and inference. Conversely, training-free approaches offer a more efficient alternative by adapting pre-trained image-LLMs models for video tasks without additional training, but they face inference efficiency bottlenecks due to the large number of visual tokens generated from video frames. In this work, we present a novel prompt-guided visual perception framework (abbreviated as \emph{Free Video-LLM}) for efficient inference of training-free video LLMs. The proposed framework decouples spatial-temporal dimension and performs temporal frame sampling and spatial RoI cropping respectively based on task-specific prompts. Our method effectively reduces the number of visual tokens while maintaining high performance across multiple video question-answering benchmarks. Extensive experiments demonstrate that our approach achieves competitive results with significantly fewer tokens, offering an optimal trade-off between accuracy and computational efficiency compared to state-of-the-art video LLMs. The code will be available at \url{https://github.com/contrastive/FreeVideoLLM}.

[Arxiv](https://arxiv.org/abs/2410.10441)