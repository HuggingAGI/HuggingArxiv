# TOPA：借助文本预对齐技术，扩展大型语言模型以增强视频理解能力

发布时间：2024年05月22日

`LLM应用

这篇论文主要探讨了如何扩展大型语言模型（LLMs）以理解视频内容，通过创新的“仅文本预对齐”（TOPA）方法，无需真实视频数据预训练即可实现。这种方法涉及生成模拟真实视频-文本数据的文本视频，并使用CLIP模型作为特征提取器来对齐文本与图像模态。论文通过实验证明了TOPA方法在视频理解任务上的有效性和效率，这表明了LLM在视频理解领域的应用潜力。因此，这篇论文应归类为LLM应用。` `视频理解`

> TOPA: Extend Large Language Models for Video Understanding via Text-Only Pre-Alignment

# 摘要

> 得益于网络图像-文本对的广泛应用，图像理解技术近期取得了显著进展。然而，视频理解领域仍面临挑战，尽管网络上的视频-文本数据丰富。这一难题主要源自视频本身的复杂性以及网络收集的视频-文本数据集中语言监督的低效性。为此，本文提出了一种名为“仅文本预对齐”（TOPA）的创新方法，旨在无需真实视频数据预训练的情况下，扩展大型语言模型（LLMs）以理解视频。具体而言，我们首先利用高级LLM生成包含连续文本帧的文本视频，并附带相应注释，模拟真实视频-文本数据。接着，这些注释的文本视频用于将仅语言的LLM与视频模态进行预对齐。为弥合文本与真实视频间的差距，我们采用CLIP模型作为特征提取器，对齐图像与文本模态。在仅文本预对齐过程中，连续文本帧被编码为一系列CLIP文本特征，与连续的CLIP图像特征相似，从而使LLM与真实视频表示对齐。通过包括零样本评估和在多种视频理解任务上微调的广泛实验，我们证明了TOPA是一个既有效又高效的框架，用于将视频内容与LLMs对齐。特别地，未使用任何视频数据训练的TOPA-Llama2-13B模型，在具有挑战性的长格式视频理解基准Egoschema上达到了51.0%的Top-1准确率，超越了以往的视频-文本预训练方法，并与近期基于GPT-3.5的视频代理表现相当。

> Recent advancements in image understanding have benefited from the extensive use of web image-text pairs. However, video understanding remains a challenge despite the availability of substantial web video-text data. This difficulty primarily arises from the inherent complexity of videos and the inefficient language supervision in recent web-collected video-text datasets. In this paper, we introduce Text-Only Pre-Alignment (TOPA), a novel approach to extend large language models (LLMs) for video understanding, without the need for pre-training on real video data. Specifically, we first employ an advanced LLM to automatically generate Textual Videos comprising continuous textual frames, along with corresponding annotations to simulate real video-text data. Then, these annotated textual videos are used to pre-align a language-only LLM with the video modality. To bridge the gap between textual and real videos, we employ the CLIP model as the feature extractor to align image and text modalities. During text-only pre-alignment, the continuous textual frames, encoded as a sequence of CLIP text features, are analogous to continuous CLIP image features, thus aligning the LLM with real video representation. Extensive experiments, including zero-shot evaluation and finetuning on various video understanding tasks, demonstrate that TOPA is an effective and efficient framework for aligning video content with LLMs. In particular, without training on any video data, the TOPA-Llama2-13B model achieves a Top-1 accuracy of 51.0% on the challenging long-form video understanding benchmark, Egoschema. This performance surpasses previous video-text pre-training approaches and proves competitive with recent GPT-3.5-based video agents.

[Arxiv](https://arxiv.org/abs/2405.13911)