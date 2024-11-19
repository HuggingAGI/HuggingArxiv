# TS-LLaVA：借助缩略图和采样来构建视觉标记，以用于无需训练的视频大型语言模型

发布时间：2024年11月17日

`LLM应用` `多模态`

> TS-LLaVA: Constructing Visual Tokens through Thumbnail-and-Sampling for Training-Free Video Large Language Models

# 摘要

> 近期，多模态大型语言模型（LLMs）的发展在多模态内容的理解上大获成功。就视频理解任务而言，由于高质量且精心整理的视频-文本配对数据稀缺，基于训练的视频LLMs构建难度大。相较而言，配对的图像-文本数据更易获取，且图像和视频有诸多相似之处。所以，把图像LLMs拓展用于视频理解任务是颇具吸引力的选择。开发压缩多个帧的视觉标记的有效策略，是利用强大的预训练图像LLM的可行途径。在本项工作中，我们探究了现有压缩策略在构建无需训练的视频LLM时的局限性。这些发现促成了我们的TS-LLaVA方法，它通过缩略图和采样策略构建视觉标记。对于给定视频，我们从所有输入帧中选取几个等距帧来构建作为详细视觉提示的缩略图图像，并结合来自所有输入帧的采样视觉标记。我们的方法在各类基准上的无需训练的视频LLMs中达到了新的领先水平。特别要指出的是，我们的34B模型在MVBench基准上胜过GPT-4V，在颇具挑战的MLVU基准上，其性能与72B基于训练的视频LLM Video-LLaMA2相当。代码可在https://github.com/tingyu215/TS-LLaVA获取。

> Recent advances in multimodal Large Language Models (LLMs) have shown great success in understanding multi-modal contents. For video understanding tasks, training-based video LLMs are difficult to build due to the scarcity of high-quality, curated video-text paired data. In contrast, paired image-text data are much easier to obtain, and there is substantial similarity between images and videos. Consequently, extending image LLMs for video understanding tasks presents an appealing alternative. Developing effective strategies for compressing visual tokens from multiple frames is a promising way to leverage the powerful pre-trained image LLM. In this work, we explore the limitations of the existing compression strategies for building a training-free video LLM. The findings lead to our method TS-LLaVA, which constructs visual tokens through a Thumbnail-and-Sampling strategy. Given a video, we select few equidistant frames from all input frames to construct a Thumbnail image as a detailed visual cue, complemented by Sampled visual tokens from all input frames. Our method establishes the new state-of-the-art performance among training-free video LLMs on various benchmarks. Notably, our 34B model outperforms GPT-4V on the MVBench benchmark, and achieves performance comparable to the 72B training-based video LLM, Video-LLaMA2, on the challenging MLVU benchmark. Code is available at https://github.com/tingyu215/TS-LLaVA.

[Arxiv](https://arxiv.org/abs/2411.11066)