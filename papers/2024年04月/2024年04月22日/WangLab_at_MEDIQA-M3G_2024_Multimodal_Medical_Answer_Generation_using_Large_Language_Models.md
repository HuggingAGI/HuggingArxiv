# 2024年MEDIQA-M3G竞赛中的WangLab团队：运用大型语言模型打造多模态医学回答生成系统。

发布时间：2024年04月22日

`LLM应用` `图像分类`

> WangLab at MEDIQA-M3G 2024: Multimodal Medical Answer Generation using Large Language Models

# 摘要

> 本论文介绍了我们为 MEDIQA2024 多语言多模态医学答案生成（M3G）挑战赛所提交的研究成果。在该任务的英语领域中，我们展示了两种独立方法的成果：第一种方法是连续调用 Claude 3 Opus API 两次；第二种方法是模仿 CLIP 技术，训练图像与疾病标签的联合嵌入模型以用于图像分类。这两种方法在竞赛排行榜上分别荣获冠亚军，表现远超其他参赛方案。文章还分享了赛后实验带来的深刻见解。鉴于共享任务本身的复杂性以及医学视觉问答的普遍挑战，尽管这两种解决方案尚有提升空间，我们仍将多阶段大型语言模型（LLM）方法和 CLIP 图像分类方法视为未来研究的有前景方向。

> This paper outlines our submission to the MEDIQA2024 Multilingual and Multimodal Medical Answer Generation (M3G) shared task. We report results for two standalone solutions under the English category of the task, the first involving two consecutive API calls to the Claude 3 Opus API and the second involving training an image-disease label joint embedding in the style of CLIP for image classification. These two solutions scored 1st and 2nd place respectively on the competition leaderboard, substantially outperforming the next best solution. Additionally, we discuss insights gained from post-competition experiments. While the performance of these two solutions have significant room for improvement due to the difficulty of the shared task and the challenging nature of medical visual question answering in general, we identify the multi-stage LLM approach and the CLIP image classification approach as promising avenues for further investigation.

[Arxiv](https://arxiv.org/abs/2404.14567)