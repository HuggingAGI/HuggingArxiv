# 医学 OSCE 评估中的大型语言模型：转录分析的创新之道

发布时间：2024年10月11日

`LLM应用`

> Large Language Models for Medical OSCE Assessment: A Novel Approach to Transcript Analysis

# 摘要

> OSCE 评分过程耗时且昂贵，传统上依赖于人类专家的手动努力。本研究探索了大型语言模型 (LLM) 在评估医学生沟通技能方面的潜力。我们分析了 UTSW 四年来 2,027 个视频记录的 OSCE 考试，涵盖多个医学案例。重点评估学生总结患者病史的能力。通过 Whisper-v3 转录音频后，我们测试了多种 LLM 方法在评分中的表现。前沿 LLM 如 GPT-4 与人类评分者的一致性高达 0.88，显示出增强当前评分过程的潜力。开源模型也表现出色，预示着广泛、经济的部署前景。我们还分析了 LLM 评分的局限性，并提出了在医学教育中应用 LLM 的最佳实践。

> Grading Objective Structured Clinical Examinations (OSCEs) is a time-consuming and expensive process, traditionally requiring extensive manual effort from human experts. In this study, we explore the potential of Large Language Models (LLMs) to assess skills related to medical student communication. We analyzed 2,027 video-recorded OSCE examinations from the University of Texas Southwestern Medical Center (UTSW), spanning four years (2019-2022), and several different medical cases or "stations." Specifically, our focus was on evaluating students' ability to summarize patients' medical history: we targeted the rubric item 'did the student summarize the patients' medical history?' from the communication skills rubric. After transcribing speech audio captured by OSCE videos using Whisper-v3, we studied the performance of various LLM-based approaches for grading students on this summarization task based on their examination transcripts. Using various frontier-level open-source and proprietary LLMs, we evaluated different techniques such as zero-shot chain-of-thought prompting, retrieval augmented generation, and multi-model ensemble methods. Our results show that frontier LLM models like GPT-4 achieved remarkable alignment with human graders, demonstrating a Cohen's kappa agreement of 0.88 and indicating strong potential for LLM-based OSCE grading to augment the current grading process. Open-source models also showed promising results, suggesting potential for widespread, cost-effective deployment. Further, we present a failure analysis identifying conditions where LLM grading may be less reliable in this context and recommend best practices for deploying LLMs in medical education settings.

[Arxiv](https://arxiv.org/abs/2410.12858)