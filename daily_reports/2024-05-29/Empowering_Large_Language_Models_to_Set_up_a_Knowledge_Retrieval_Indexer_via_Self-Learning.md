# 借助自我学习，大型语言模型得以自主构建知识检索的索引器，这一过程不仅提升了模型的自主性，也增强了其知识处理的能力。
发布时间：2024年05月27日

`RAG`
> Empowering Large Language Models to Set up a Knowledge Retrieval Indexer via Self-Learning
>
> Retrieval-Augmented Generation (RAG) 为大型语言模型 (LLMs) 注入实时知识提供了一种经济高效的方法。然而，构建和验证高质量知识库的过程颇为繁琐。我们提出的 Pseudo-Graph Retrieval-Augmented Generation (PG-RAG) 框架，将 LLMs 比作学生，通过提供大量原始阅读材料，鼓励其自主阅读并用自己的语言记录事实信息，形成一个简洁有序的伪图数据库。在检索时，PG-RAG 模仿人类翻阅笔记的行为，寻找事实路径并深入相关上下文。遵循“多数人选择的路径最佳”的原则，PG-RAG 整合了高度证实的事实路径，为 LLMs 提供了一个结构化和精炼的子图。我们在三个专业问答数据集上验证了 PG-RAG 的效果，其在单文档任务中显著优于当前最佳基线 KGP-LLaMA，平均性能提升达 11.6%，特别是在 BLEU 分数和 QE-F1 指标上分别提升了约 14.3% 和 23.7%。在多文档场景中，PG-RAG 的平均指标至少比最佳基线高 2.35%，BLEU 分数和 QE-F1 指标分别稳定提升了约 7.55% 和 12.75%。我们的代码已开源：https://github.com/IAAR-Shanghai/PGRAG。
>
> https://arxiv.org/abs/2405.16933

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16933/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16933/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16933/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16933/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16933/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16933/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.16933/x7.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.16933](https://arxiv.org/abs/2405.16933)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886