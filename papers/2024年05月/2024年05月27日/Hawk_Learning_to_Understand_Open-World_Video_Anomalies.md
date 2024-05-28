# 鹰眼探秘：解锁开放世界视频异常的洞察力

发布时间：2024年05月27日

`Agent

这篇论文介绍了一个名为 Hawk 的框架，它通过交互式大型视觉语言模型来精准解读视频异常。这个框架特别整合了运动信息，并通过构建运动与视频空间的一致性损失来强化对运动的关注。此外，它还建立了运动与语言描述的直接联系，并创建了问答对以适应开放世界场景。这个框架在视频描述与问答任务中均超越了现有技术，并且相关资源将在GitHub上公开。因此，这个框架可以被视为一个Agent，因为它能够自主监控并识别干扰，减少人工成本，并且通过交互式大型视觉语言模型来实现这一目标。` `视频监控` `异常检测`

> Hawk: Learning to Understand Open-World Video Anomalies

# 摘要

> 视频异常检测系统（VAD）能自主监控并识别干扰，大幅减少人工成本。但现有系统因对场景理解浅显及用户互动不足而受限，且数据稀缺性限制了其在开放世界的应用。本文推出的Hawk框架，通过交互式大型视觉语言模型精准解读视频异常。Hawk特别整合运动信息，区分异常与正常视频，并通过构建运动与视频空间的一致性损失，强化对运动的关注。同时，我们建立了运动与语言描述的直接联系，并标注了8,000多个异常视频，创建了问答对，以适应开放世界场景。Hawk在视频描述与问答任务中均超越了现有技术，相关资源将在GitHub上公开。

> Video Anomaly Detection (VAD) systems can autonomously monitor and identify disturbances, reducing the need for manual labor and associated costs. However, current VAD systems are often limited by their superficial semantic understanding of scenes and minimal user interaction. Additionally, the prevalent data scarcity in existing datasets restricts their applicability in open-world scenarios. In this paper, we introduce Hawk, a novel framework that leverages interactive large Visual Language Models (VLM) to interpret video anomalies precisely. Recognizing the difference in motion information between abnormal and normal videos, Hawk explicitly integrates motion modality to enhance anomaly identification. To reinforce motion attention, we construct an auxiliary consistency loss within the motion and video space, guiding the video branch to focus on the motion modality. Moreover, to improve the interpretation of motion-to-language, we establish a clear supervisory relationship between motion and its linguistic representation. Furthermore, we have annotated over 8,000 anomaly videos with language descriptions, enabling effective training across diverse open-world scenarios, and also created 8,000 question-answering pairs for users' open-world questions. The final results demonstrate that Hawk achieves SOTA performance, surpassing existing baselines in both video description generation and question-answering. Our codes/dataset/demo will be released at https://github.com/jqtangust/hawk.

[Arxiv](https://arxiv.org/abs/2405.16886)