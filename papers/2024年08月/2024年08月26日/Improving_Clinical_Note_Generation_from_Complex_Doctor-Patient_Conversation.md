# 优化临床笔记生成：从复杂医患对话中提炼精华

发布时间：2024年08月26日

`LLM应用` `人工智能`

> Improving Clinical Note Generation from Complex Doctor-Patient Conversation

# 摘要

> 医疗专业人员撰写临床笔记和记录医疗检查是一项关键任务，但手动操作耗时且影响直接患者互动。为此，我们通过LLM在临床笔记生成领域做出了三项贡献：首先，推出了CliniKnote数据集，包含1,200个医患对话及其完整笔记；其次，创新了K-SOAP笔记格式，优化信息检索；最后，开发了自动生成K-SOAP笔记的流程，并测试了多种LLM，结果显示效率和性能大幅提升。

> Writing clinical notes and documenting medical exams is a critical task for healthcare professionals, serving as a vital component of patient care documentation. However, manually writing these notes is time-consuming and can impact the amount of time clinicians can spend on direct patient interaction and other tasks. Consequently, the development of automated clinical note generation systems has emerged as a clinically meaningful area of research within AI for health. In this paper, we present three key contributions to the field of clinical note generation using large language models (LLMs). First, we introduce CliniKnote, a comprehensive dataset consisting of 1,200 complex doctor-patient conversations paired with their full clinical notes. This dataset, created and curated by medical experts with the help of modern neural networks, provides a valuable resource for training and evaluating models in clinical note generation tasks. Second, we propose the K-SOAP (Keyword, Subjective, Objective, Assessment, and Plan) note format, which enhances traditional SOAP~\cite{podder2023soap} (Subjective, Objective, Assessment, and Plan) notes by adding a keyword section at the top, allowing for quick identification of essential information. Third, we develop an automatic pipeline to generate K-SOAP notes from doctor-patient conversations and benchmark various modern LLMs using various metrics. Our results demonstrate significant improvements in efficiency and performance compared to standard LLM finetuning methods.

[Arxiv](https://arxiv.org/abs/2408.14568)