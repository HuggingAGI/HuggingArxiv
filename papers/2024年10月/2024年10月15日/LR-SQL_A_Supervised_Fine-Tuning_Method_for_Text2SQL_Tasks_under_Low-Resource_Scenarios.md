# LR-SQL：低资源场景下 Text2SQL 任务的监督微调新方法

发布时间：2024年10月15日

`LLM应用` `数据库` `人工智能`

> LR-SQL: A Supervised Fine-Tuning Method for Text2SQL Tasks under Low-Resource Scenarios

# 摘要

> 大型语言模型通过监督微调革新了 Text2SQL，但数据库的复杂性导致上下文长度增加，进而提高了 GPU 内存需求。为此，我们推出了 LR-SQL，它包含两个微调模型：schema_link 和 SQL_generation，其中 schema_link 模型是简化流程的关键。在微调过程中，LR-SQL 将数据库分解为灵活的表组合，使模型能从分散片段中学习整体关系。此外，LR-SQL 还训练了模型的 Chain-of-Thought 能力，以增强推理时对片段间关系的感知。实验显示，LR-SQL 能减少 40% 的 GPU 内存使用，且在 schema_link 任务中仅损失 2% 的准确性，整体 Text2SQL 任务的执行准确性仅下降 0.6%。项目现已上线 https://github.com/hongWin/LR-SQL。

> Large language models revolutionize Text2SQL through supervised fine-tuning, yet a crucial limitation is overlooked: the complexity of databases leads to an increased context length, consequently resulting in higher GPU memory demands for model fine-tuning. To address this issue, we propose LR-SQL. LR-SQL comprises two supervised fine-tuning models: the schema\_link model and the SQL\_generation model, with the schema\_link model serving as the focal point for streamlining the overall process. During the fine-tuning of the schema\_link model, LR-SQL breaks down the complete database into flexible combinations of tables with adjustable quantities, enabling the model to learn the relationships within the entire database from these dispersed slices. Furthermore, to enhance the model's ability to perceive the relationships among various discrete slices during inference, LR-SQL trains the model's Chain-of-Thought capability for this task. Experimental results demonstrate that LR-SQL can reduce the total GPU memory usage by 40\% compared to existing fine-tuning methods, while only losing 2\% of table prediction accuracy in schema\_link task. For the overall Text2SQL task, the Execution Accuracy decrease by 0.6\%.Our project is now available on https://github.com/hongWin/LR-SQL

[Arxiv](https://arxiv.org/abs/2410.11457)