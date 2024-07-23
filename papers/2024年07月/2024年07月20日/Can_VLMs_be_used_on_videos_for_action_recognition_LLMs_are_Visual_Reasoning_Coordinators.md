# VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。

发布时间：2024年07月20日

`LLM应用` `视频分析`

> Can VLMs be used on videos for action recognition? LLMs are Visual Reasoning Coordinators

# 摘要

> 近期，多种视觉-语言模型 (VLM) 在跨领域常识推理上表现卓越，但它们协同作用的潜力尚待深入挖掘。Cola 框架揭示了大型语言模型 (LLM) 如何通过自然语言沟通，高效整合多个 VLM 的优势。我们在 A-OKVQA 数据集上的验证证实了这种协同的有效性。进一步地，我们研究了这一方法是否适用于监控视频中的动作识别，特别是在仅提供关键帧和有限时间信息的情况下。实验显示，LLM 在协调 VLM 时，即便时间线索薄弱，也能准确识别并推断动作。为提升这一方法的实用性，我们建议增强时间信号并增加模型接触的帧数。

> Recent advancements have introduced multiple vision-language models (VLMs) demonstrating impressive commonsense reasoning across various domains. Despite their individual capabilities, the potential of synergizing these complementary VLMs remains underexplored. The Cola Framework addresses this by showcasing how a large language model (LLM) can efficiently coordinate multiple VLMs through natural language communication, leveraging their distinct strengths. We have verified this claim on the challenging A-OKVQA dataset, confirming the effectiveness of such coordination. Building on this, our study investigates whether the same methodology can be applied to surveillance videos for action recognition. Specifically, we explore if leveraging the combined knowledge base of VLMs and LLM can effectively deduce actions from a video when presented with only a few selectively important frames and minimal temporal information. Our experiments demonstrate that LLM, when coordinating different VLMs, can successfully recognize patterns and deduce actions in various scenarios despite the weak temporal signals. However, our findings suggest that to enhance this approach as a viable alternative solution, integrating a stronger temporal signal and exposing the models to slightly more frames would be beneficial.

![VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。](../../../paper_images/2407.14834/Cola_overview.png)

![VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。](../../../paper_images/2407.14834/Cola_VQA_template.png)

![VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。](../../../paper_images/2407.14834/key_frame_extraction_procedure.png)

![VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。](../../../paper_images/2407.14834/custom_template_HAR.png)

![VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。](../../../paper_images/2407.14834/Ensemble_Flowchart.png)

![VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。](../../../paper_images/2407.14834/Cola_flow_chart.png)

![VLMs 能否助力视频动作识别？LLMs 担当视觉推理的协调者角色。](../../../paper_images/2407.14834/confusion_matrix.png)

[Arxiv](https://arxiv.org/abs/2407.14834)