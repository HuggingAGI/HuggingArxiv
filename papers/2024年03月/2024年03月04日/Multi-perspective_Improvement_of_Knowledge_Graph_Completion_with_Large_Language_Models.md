# [本研究探讨如何借助大型语言模型从多个视角提升知识图谱补全任务的效果。](https://arxiv.org/abs/2403.01972)

发布时间：2024年03月04日

`LLM应用`

> Multi-perspective Improvement of Knowledge Graph Completion with Large Language Models

> 面对知识图谱中缺失链接的问题，知识图谱补全（KGC）技术被广泛应用，其中基于描述的方法利用预训练语言模型根据实体名称或描述学习表达，展示出积极效果。但受限于文本质量及不完备的结构信息，特别是实体描述匮乏以及过度依赖关系名称，基于描述的KGC方法性能仍有局限性。为此，我们创新设计了MPIKGC这一通用框架，它能通过多角度查询大型语言模型（LLMs），充分利用LLMs的推理、解释与摘要功能，有效扩充实体描述、深化对关系的理解并提炼结构信息，以弥补情境知识的不足，提升KGC性能。我们基于四种基于描述的KGC模型及四个数据集，针对链路预测和三元组分类任务，对本框架的有效性和提升效果进行了深入广泛的评估。

> Knowledge graph completion (KGC) is a widely used method to tackle incompleteness in knowledge graphs (KGs) by making predictions for missing links. Description-based KGC leverages pre-trained language models to learn entity and relation representations with their names or descriptions, which shows promising results. However, the performance of description-based KGC is still limited by the quality of text and the incomplete structure, as it lacks sufficient entity descriptions and relies solely on relation names, leading to sub-optimal results. To address this issue, we propose MPIKGC, a general framework to compensate for the deficiency of contextualized knowledge and improve KGC by querying large language models (LLMs) from various perspectives, which involves leveraging the reasoning, explanation, and summarization capabilities of LLMs to expand entity descriptions, understand relations, and extract structures, respectively. We conducted extensive evaluation of the effectiveness and improvement of our framework based on four description-based KGC models and four datasets, for both link prediction and triplet classification tasks.