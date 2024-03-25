# SyllabusQA——一个专注于课程运行事务问答的数据集

发布时间：2024年03月02日

`Agent` `聊天机器人`

> SyllabusQA: A Course Logistics Question Answering Dataset

> 自动化助教及聊天机器人在处理繁琐的学生常问问题（尤其是关乎课程物流的问题）方面大有可为，有助于大幅降低教师的工作量。但由于隐私保护原因，当前尚缺乏公开可用的相关数据集。为此，我们推出了SyllabusQA这一开源数据宝库，内含来自36个专业的63份真实课程大纲，包含了5078组多元化的问题与答案配对，涉及多种类型的问题和答案形式。考虑到许多物流问题往往包含如考试日期等关键信息，确保答案真实性显得尤为关键。我们在这一任务上设立了多个强大基准，从基于大规模语言模型的提示技术到融合检索增强的生成方法均有涵盖。实验结果显示，尽管自动化方法在传统文本相似度评价标准上已接近人类水平，但在事实精确度方面，与人类相比仍有明显提升空间。

> Automated teaching assistants and chatbots have significant potential to reduce the workload of human instructors, especially for logistics-related question answering, which is important to students yet repetitive for instructors. However, due to privacy concerns, there is a lack of publicly available datasets. We introduce SyllabusQA, an open-source dataset with 63 real course syllabi covering 36 majors, containing 5,078 open-ended course logistics-related question-answer pairs that are diverse in both question types and answer formats. Since many logistics-related questions contain critical information like the date of an exam, it is important to evaluate the factuality of answers. We benchmark several strong baselines on this task, from large language model prompting to retrieval-augmented generation. We find that despite performing close to humans on traditional metrics of textual similarity, there remains a significant gap between automated approaches and humans in terms of fact precision.

![SyllabusQA——一个专注于课程运行事务问答的数据集](../../../paper_images/2403.14666/x1.png)

[Arxiv](https://arxiv.org/abs/2403.14666)