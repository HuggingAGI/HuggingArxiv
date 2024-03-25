# SyllabusQA——面向课程后勤问题回答的全新数据集

发布时间：2024年03月02日

`Agent` `聊天机器人`

> SyllabusQA: A Course Logistics Question Answering Dataset

> 自动化助教及聊天机器人在处理学生关心但教师需反复解答的物流类问题时，能够有效减轻教师的工作压力，但由于隐私顾虑，公开可用的相关数据集较为稀缺。为此，我们推出了SyllabusQA——一个开源数据集，它涵盖了36个专业的63份真实课程大纲，包含了5078对多样化问题类型和答案格式的开放式课程物流问题及其答案。鉴于不少物流问题涉及如考试日期等重要信息，验证答案的真实性显得尤为重要。我们在该任务上对比了几种强有力的基准方法，包括基于大型语言模型的提示技术和检索增强生成技术。结果显示，尽管自动化方法在传统文本相似性评价标准上逼近人类水平，但在事实精确度这一维度上，其与人类仍存在较大差距。

> Automated teaching assistants and chatbots have significant potential to reduce the workload of human instructors, especially for logistics-related question answering, which is important to students yet repetitive for instructors. However, due to privacy concerns, there is a lack of publicly available datasets. We introduce SyllabusQA, an open-source dataset with 63 real course syllabi covering 36 majors, containing 5,078 open-ended course logistics-related question-answer pairs that are diverse in both question types and answer formats. Since many logistics-related questions contain critical information like the date of an exam, it is important to evaluate the factuality of answers. We benchmark several strong baselines on this task, from large language model prompting to retrieval-augmented generation. We find that despite performing close to humans on traditional metrics of textual similarity, there remains a significant gap between automated approaches and humans in terms of fact precision.

![SyllabusQA——面向课程后勤问题回答的全新数据集](../../../paper_images/2403.14666/x1.png)

[Arxiv](https://arxiv.org/abs/2403.14666)