# Konstruktor：简单知识图谱问答的坚实起点

发布时间：2024年09月24日

`LLM应用` `知识图谱` `问答系统`

> Konstruktor: A Strong Baseline for Simple Knowledge Graph Question Answering

# 摘要

> 尽管“谁是灰姑娘的作者？”这类简单问题广受欢迎，但仍未完全解决。令人惊讶的是，即使是最先进的语言模型在处理这类问题时也容易出错，尤其是涉及罕见实体时。为此，我们提出了一种结合知识图谱的方法，将问题分解为实体提取、关系预测和知识图谱查询三个步骤。通过实验，我们发现关系分类与排名的结合在关系检测中表现尤为出色。Konstruktor 在多个数据集上展现了强大的性能。

> While being one of the most popular question types, simple questions such as "Who is the author of Cinderella?", are still not completely solved. Surprisingly, even the most powerful modern Large Language Models are prone to errors when dealing with such questions, especially when dealing with rare entities. At the same time, as an answer may be one hop away from the question entity, one can try to develop a method that uses structured knowledge graphs (KGs) to answer such questions. In this paper, we introduce Konstruktor - an efficient and robust approach that breaks down the problem into three steps: (i) entity extraction and entity linking, (ii) relation prediction, and (iii) querying the knowledge graph. Our approach integrates language models and knowledge graphs, exploiting the power of the former and the interpretability of the latter. We experiment with two named entity recognition and entity linking methods and several relation detection techniques. We show that for relation detection, the most challenging step of the workflow, a combination of relation classification/generation and ranking outperforms other methods. We report Konstruktor's strong results on four datasets.

[Arxiv](https://arxiv.org/abs/2409.15902)