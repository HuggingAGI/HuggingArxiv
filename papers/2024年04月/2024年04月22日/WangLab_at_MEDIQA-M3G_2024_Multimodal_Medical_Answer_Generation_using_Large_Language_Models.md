# 在 2024 年的 MEDIQA-M3G 大会上，WangLab 展示了一项创新成果：运用先进的大型语言模型，实现了多模态医学问题的智能答案生成。

发布时间：2024年04月22日

`分类：LLM应用

这篇论文摘要介绍了两个独立的方法，它们在MEDIQA2024多语言多模态医学答案生成任务的英语部分中表现出色。第一个方法涉及连续两次调用Claude 3 Opus API，而第二个方法则采用CLIP技术来训练图像与疾病标签的联合嵌入模型。这两种方法在竞赛中获得了第一名和第二名，表明了大型语言模型（LLM）在实际应用中的潜力。此外，论文还提到了对赛后实验的深入见解，以及对未来研究方向的展望。因此，这篇论文可以归类为LLM应用。` `图像识别`

> WangLab at MEDIQA-M3G 2024: Multimodal Medical Answer Generation using Large Language Models

# 摘要

> 本文介绍了我们为 MEDIQA2024 多语言多模态医学答案生成（M3G）任务所提交的研究成果。在该任务的英语部分，我们提出了两种独立方法：第一种方法是连续两次调用 Claude 3 Opus API，第二种方法是采用 CLIP 技术训练图像与疾病标签的联合嵌入模型以进行图像分类。这两种方法在竞赛排行榜上分别荣获第一和第二名，大幅领先于其他解决方案。文章还分享了赛后实验的深刻见解。尽管面对任务的复杂性和医学视觉问答的普遍挑战，这两种解决方案的表现尚有提升空间，但我们看好多阶段大型语言模型（LLM）方法和 CLIP 图像分类方法，认为它们是未来研究的有前景方向。

> This paper outlines our submission to the MEDIQA2024 Multilingual and Multimodal Medical Answer Generation (M3G) shared task. We report results for two standalone solutions under the English category of the task, the first involving two consecutive API calls to the Claude 3 Opus API and the second involving training an image-disease label joint embedding in the style of CLIP for image classification. These two solutions scored 1st and 2nd place respectively on the competition leaderboard, substantially outperforming the next best solution. Additionally, we discuss insights gained from post-competition experiments. While the performance of these two solutions have significant room for improvement due to the difficulty of the shared task and the challenging nature of medical visual question answering in general, we identify the multi-stage LLM approach and the CLIP image classification approach as promising avenues for further investigation.

[Arxiv](https://arxiv.org/abs/2404.14567)