# VisionGPT：借助 LLM 实现实时视觉异常检测，助力安全导航决策

发布时间：2024年03月18日

`LLM应用` `视觉导航`

> VisionGPT: LLM-Assisted Real-Time Anomaly Detection for Safe Visual Navigation

> 本文研究了LLMs在零样本异常检测中助力安全视觉导航的可能性，借助最新实时物体检测模型Yolo-World及精心设计的提示，新框架能够识别并用简洁的音频突出描述摄像头捕捉到的各种潜在障碍物，从而帮助在复杂环境下实现安全导航。此外，该框架整合了LLMs与开放词汇物体检测模型的优势，实现了场景间的无缝切换，突破了传统视觉导航技术的局限。同时，本文还深入剖析了各类提示元素对性能的影响，为今后视觉无障碍技术的发展提供洞见，并为LLMs在视频异常检测和视觉-语言理解领域的拓展奠定了基础。

> This paper explores the potential of Large Language Models(LLMs) in zero-shot anomaly detection for safe visual navigation. With the assistance of the state-of-the-art real-time open-world object detection model Yolo-World and specialized prompts, the proposed framework can identify anomalies within camera-captured frames that include any possible obstacles, then generate concise, audio-delivered descriptions emphasizing abnormalities, assist in safe visual navigation in complex circumstances. Moreover, our proposed framework leverages the advantages of LLMs and the open-vocabulary object detection model to achieve the dynamic scenario switch, which allows users to transition smoothly from scene to scene, which addresses the limitation of traditional visual navigation. Furthermore, this paper explored the performance contribution of different prompt components, provided the vision for future improvement in visual accessibility, and paved the way for LLMs in video anomaly detection and vision-language understanding.

![VisionGPT：借助 LLM 实现实时视觉异常检测，助力安全导航决策](../../../paper_images/2403.12415/frame.png)

![VisionGPT：借助 LLM 实现实时视觉异常检测，助力安全导航决策](../../../paper_images/2403.12415/H_2.jpg)

![VisionGPT：借助 LLM 实现实时视觉异常检测，助力安全导航决策](../../../paper_images/2403.12415/ROC_2.png)

![VisionGPT：借助 LLM 实现实时视觉异常检测，助力安全导航决策](../../../paper_images/2403.12415/confusion.png)

![VisionGPT：借助 LLM 实现实时视觉异常检测，助力安全导航决策](../../../paper_images/2403.12415/heatmap_4.png)

[Arxiv](https://arxiv.org/abs/2403.12415)