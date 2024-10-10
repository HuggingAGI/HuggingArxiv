# 以眼还耳：通过视听分布对齐，利用图像描述器实现零-shot 音频描述

发布时间：2024年10月08日

`LLM应用` `多媒体` `人工智能`

> An Eye for an Ear: Zero-shot Audio Description Leveraging an Image Captioner using Audiovisual Distribution Alignment

# 摘要

> 多模态大型语言模型在图像描述领域取得了显著进展。这些模型通过在海量图像数据集上的微调，展现了深刻的语义理解能力。我们发现，这种能力同样适用于音频描述任务，通过联合图像-语言解码器，可以描述视频中图像序列相关的听觉内容。然而，由于现实视频中听觉与视觉元素的固有差异，多模态对齐并非易事。此外，多模态表示学习常依赖对比学习，面临模态差距的挑战。为此，我们提出了一种新方法，通过匹配音频与图像标记的分布，弥合视听模态差距。这种方法使模型能在不改变初始图像描述组件的前提下，无监督地进行零样本音频描述。通过结合或替换图像编码器与对齐的音频编码器，我们的方法显著提升了零样本音频描述的性能。

> Multimodal large language models have fueled progress in image captioning. These models, fine-tuned on vast image datasets, exhibit a deep understanding of semantic concepts. In this work, we show that this ability can be re-purposed for audio captioning, where the joint image-language decoder can be leveraged to describe auditory content associated with image sequences within videos featuring audiovisual content. This can be achieved via multimodal alignment. Yet, this multimodal alignment task is non-trivial due to the inherent disparity between audible and visible elements in real-world videos. Moreover, multimodal representation learning often relies on contrastive learning, facing the challenge of the so-called modality gap which hinders smooth integration between modalities. In this work, we introduce a novel methodology for bridging the audiovisual modality gap by matching the distributions of tokens produced by an audio backbone and those of an image captioner. Our approach aligns the audio token distribution with that of the image tokens, enabling the model to perform zero-shot audio captioning in an unsupervised fashion while keeping the initial image captioning component unaltered. This alignment allows for the use of either audio or audiovisual input by combining or substituting the image encoder with the aligned audio encoder. Our method achieves significantly improved performances in zero-shot audio captioning, compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2410.05997)