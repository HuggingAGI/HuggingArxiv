# LR-SQL：低资源场景下 Text2SQL 任务的监督微调新方法
发布时间：2024年10月15日

`代码编写`
> LR-SQL: A Supervised Fine-Tuning Method for Text2SQL Tasks under Low-Resource Scenarios
>
> 大型语言模型通过监督微调革新了 Text2SQL，但数据库的复杂性导致上下文长度增加，进而提高了 GPU 内存需求。为此，我们推出了 LR-SQL，它包含两个微调模型：schema_link 和 SQL_generation，其中 schema_link 模型是简化流程的关键。在微调过程中，LR-SQL 将数据库分解为灵活的表组合，使模型能从分散片段中学习整体关系。此外，LR-SQL 还训练了模型的 Chain-of-Thought 能力，以增强推理时对片段间关系的感知。实验显示，LR-SQL 能减少 40% 的 GPU 内存使用，且在 schema_link 任务中仅损失 2% 的准确性，整体 Text2SQL 任务的执行准确性仅下降 0.6%。项目现已上线 https://github.com/hongWin/LR-SQL。
>
> https://arxiv.org/abs/2410.11457

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.11457](https://arxiv.org/abs/2410.11457)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)