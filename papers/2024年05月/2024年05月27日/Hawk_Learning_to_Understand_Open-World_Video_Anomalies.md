# Hawk：洞察开放世界视频中的异常现象

发布时间：2024年05月27日

`Agent

理由：这篇论文介绍了一个名为 Hawk 的框架，它通过交互式大型视觉语言模型（VLM）来精准识别视频异常。这个框架特别关注于异常与正常视频间的运动信息差异，并通过整合运动模态来提升异常检测。此外，Hawk 框架还设计了运动与视频空间的一致性损失，以及建立了运动与其语言描述间的监督关系，这些都是为了优化运动信息的语言表达。这些特性表明 Hawk 框架是一个自主监控并识别干扰的系统，具有代理（Agent）的特性，能够在开放世界场景中自主运作，减少人工干预。因此，这篇论文更适合归类到Agent分类中。` `视频监控` `异常检测`

> Hawk: Learning to Understand Open-World Video Anomalies

# 摘要

> 视频异常检测系统（VAD）能自主监控并识别干扰，从而减少人工干预和相关成本。但现有VAD系统因对场景语义理解的肤浅和用户交互的不足而受限，加之数据集的数据稀缺，使其在开放世界场景中的应用受限。为此，我们推出了Hawk框架，它通过交互式大型视觉语言模型（VLM）精准识别视频异常。Hawk特别关注异常与正常视频间的运动信息差异，并整合运动模态以提升异常检测。为增强对运动的注意力，我们设计了运动与视频空间的一致性损失，引导模型聚焦于运动模态。同时，我们建立了运动与其语言描述间的监督关系，以优化运动信息的语言表达。此外，我们为8,000多个异常视频添加了语言描述，并创建了8,000对问答，以适应开放世界场景的多样化需求。实验结果表明，Hawk在视频描述生成和问答任务上均超越了现有技术水平。相关代码、数据集和演示将在https://github.com/jqtangust/hawk公开。

> Video Anomaly Detection (VAD) systems can autonomously monitor and identify disturbances, reducing the need for manual labor and associated costs. However, current VAD systems are often limited by their superficial semantic understanding of scenes and minimal user interaction. Additionally, the prevalent data scarcity in existing datasets restricts their applicability in open-world scenarios. In this paper, we introduce Hawk, a novel framework that leverages interactive large Visual Language Models (VLM) to interpret video anomalies precisely. Recognizing the difference in motion information between abnormal and normal videos, Hawk explicitly integrates motion modality to enhance anomaly identification. To reinforce motion attention, we construct an auxiliary consistency loss within the motion and video space, guiding the video branch to focus on the motion modality. Moreover, to improve the interpretation of motion-to-language, we establish a clear supervisory relationship between motion and its linguistic representation. Furthermore, we have annotated over 8,000 anomaly videos with language descriptions, enabling effective training across diverse open-world scenarios, and also created 8,000 question-answering pairs for users' open-world questions. The final results demonstrate that Hawk achieves SOTA performance, surpassing existing baselines in both video description generation and question-answering. Our codes/dataset/demo will be released at https://github.com/jqtangust/hawk.

[Arxiv](https://arxiv.org/abs/2405.16886)