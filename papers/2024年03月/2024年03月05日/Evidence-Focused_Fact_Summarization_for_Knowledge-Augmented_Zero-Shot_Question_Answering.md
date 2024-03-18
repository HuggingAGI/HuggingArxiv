# 为了解决知识增强型零样本问题回答的挑战，我们提出了一种聚焦于证据的事实摘要方法，旨在提炼关键事实信息以辅助解答未曾见过的问题。

发布时间：2024年03月05日

`LLM应用`

> Evidence-Focused Fact Summarization for Knowledge-Augmented Zero-Shot Question Answering

> 近期研究致力于利用知识图谱强化LLMs在QA任务中的表现，但结构化的KG信息转化为自然语言表述颇具难度。现存技术如将三元组形式事实转化为标准三元组文本或自由文本时，常面临证据稀疏（由实体和关系重复引起）和关键证据不突出导致证据模糊等问题。为此，我们创新提出了EFSum——一个针对知识增强LLMs的问题回答增强型证据聚焦事实摘要框架。我们通过对开源LLM进行蒸馏和偏好校准优化，使其成为高效的事实摘要工具。大量实验表明，EFSum能够有效提升LLMs在零样本QA任务上的表现，并且有望确保生成的摘要既具指导意义又忠于原义。

> Recent studies have investigated utilizing Knowledge Graphs (KGs) to enhance Quesetion Answering (QA) performance of Large Language Models (LLMs), yet structured KG verbalization remains challengin. Existing methods, such as triple-form or free-form textual conversion of triple-form facts, encounter several issues. These include reduced evidence density due to duplicated entities or relationships, and reduced evidence clarity due to an inability to emphasize crucial evidence. To address these issues, we propose EFSum, an Evidence-focused Fact Summarization framework for enhanced QA with knowledge-augmented LLMs. We optimize an open-source LLM as a fact summarizer through distillation and preference alignment. Our extensive experiments show that EFSum improves LLM's zero-shot QA performance, and it is possible to ensure both the helpfulness and faithfulness of the summary.

[Arxiv](https://arxiv.org/abs/2403.02966)