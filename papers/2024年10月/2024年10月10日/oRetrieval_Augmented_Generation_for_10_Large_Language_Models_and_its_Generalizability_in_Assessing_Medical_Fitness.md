# 检索增强生成技术应用于10种大型语言模型，探讨其在医疗适应性评估中的普适性。

发布时间：2024年10月10日

`RAG` `人工智能`

> oRetrieval Augmented Generation for 10 Large Language Models and its Generalizability in Assessing Medical Fitness

# 摘要

> 大型语言模型（LLM）虽在医疗领域潜力巨大，但常缺乏专业临床知识。检索增强生成（RAG）通过融入特定领域信息，使其在医疗保健中表现出色。本研究评估了RAG模型在手术适应性评估和术前指导中的表现，包括准确性、一致性和安全性。我们基于35个本地和23个国际术前指南构建了LLM-RAG模型，并对比了3682个人类生成的响应。临床文件经Llamaindex处理，GPT3.5、GPT4等10个LLM参与评估。14个临床场景中，我们聚焦于术前指导的七个关键方面。正确响应依据既定指南和专家判断，与人类答案对比。LLM-RAG模型在20秒内生成响应，远快于临床医生的10分钟。GPT4模型准确率达96.4%，无幻觉，指导质量媲美临床医生。结果在本地和国际指南中均表现一致。此研究凸显了LLM-RAG模型在术前医疗任务中的高效、可扩展和可靠特性。

> Large Language Models (LLMs) show potential for medical applications but often lack specialized clinical knowledge. Retrieval Augmented Generation (RAG) allows customization with domain-specific information, making it suitable for healthcare. This study evaluates the accuracy, consistency, and safety of RAG models in determining fitness for surgery and providing preoperative instructions. We developed LLM-RAG models using 35 local and 23 international preoperative guidelines and tested them against human-generated responses. A total of 3,682 responses were evaluated. Clinical documents were processed using Llamaindex, and 10 LLMs, including GPT3.5, GPT4, and Claude-3, were assessed. Fourteen clinical scenarios were analyzed, focusing on seven aspects of preoperative instructions. Established guidelines and expert judgment were used to determine correct responses, with human-generated answers serving as comparisons. The LLM-RAG models generated responses within 20 seconds, significantly faster than clinicians (10 minutes). The GPT4 LLM-RAG model achieved the highest accuracy (96.4% vs. 86.6%, p=0.016), with no hallucinations and producing correct instructions comparable to clinicians. Results were consistent across both local and international guidelines. This study demonstrates the potential of LLM-RAG models for preoperative healthcare tasks, highlighting their efficiency, scalability, and reliability.

[Arxiv](https://arxiv.org/abs/2410.08431)