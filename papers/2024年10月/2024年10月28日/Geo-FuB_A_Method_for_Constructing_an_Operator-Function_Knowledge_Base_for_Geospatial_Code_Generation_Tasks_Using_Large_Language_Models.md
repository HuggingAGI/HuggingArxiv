# Geo-FuB：一种借助大型语言模型为地理空间代码生成任务构建运算符 - 函数知识库的办法

发布时间：2024年10月28日

`RAG` `地理空间` `代码生成`

> Geo-FuB: A Method for Constructing an Operator-Function Knowledge Base for Geospatial Code Generation Tasks Using Large Language Models

# 摘要

> 时空数据的兴起以及对高效地理空间建模的需求，促使人们热衷于借助大型语言模型（LLMs）来实现这些任务的自动化。然而，一般的LLMs由于缺乏特定领域中关于函数和运算符的知识，在生成地理空间代码时常常出错。为此，提出了一种借助外部地理空间函数和运算符知识库的检索增强生成（RAG）方法。本研究引入了一个基于地理空间脚本语义构建此类知识库的框架，其中涵盖：函数语义框架构建（Geo-FuSE）、频繁运算符组合统计（Geo-FuST）和语义映射（Geo-FuM）。像思维链、TF-IDF和APRIORI算法等技术被用于推导和对齐地理空间函数。一个由154,075个谷歌地球引擎脚本构建而成的示例知识库Geo-FuB可在GitHub上获取。评估指标表明准确率颇高，总体达88.89%，结构准确率和语义准确率分别为92.03%和86.79%。突出了Geo-FuB通过RAG和微调范式优化地理空间代码生成的潜力。

> The rise of spatiotemporal data and the need for efficient geospatial modeling have spurred interest in automating these tasks with large language models (LLMs). However, general LLMs often generate errors in geospatial code due to a lack of domain-specific knowledge on functions and operators. To address this, a retrieval-augmented generation (RAG) approach, utilizing an external knowledge base of geospatial functions and operators, is proposed. This study introduces a framework to construct such a knowledge base, leveraging geospatial script semantics. The framework includes: Function Semantic Framework Construction (Geo-FuSE), Frequent Operator Combination Statistics (Geo-FuST), and Semantic Mapping (Geo-FuM). Techniques like Chain-of-Thought, TF-IDF, and the APRIORI algorithm are utilized to derive and align geospatial functions. An example knowledge base, Geo-FuB, built from 154,075 Google Earth Engine scripts, is available on GitHub. Evaluation metrics show a high accuracy, reaching 88.89% overall, with structural and semantic accuracies of 92.03% and 86.79% respectively. Geo-FuB's potential to optimize geospatial code generation through the RAG and fine-tuning paradigms is highlighted.

[Arxiv](https://arxiv.org/abs/2410.20975)