# WikiFactDiff 是专为探究因果语言模型中原子事实知识更新而设计的大型、真实且随时间动态适应的数据集。

发布时间：2024年03月21日

`LLM应用` `事实更新`

> WikiFactDiff: A Large, Realistic, and Temporally Adaptable Dataset for Atomic Factual Knowledge Update in Causal Language Models

# 摘要

> 随着时代变迁，LLMs处理新信息的能力逐渐减弱，因为它们无法认知训练后的事件。为了让模型保持最新，一种方法是进行事实更新，即将新增、替换或删除的简单事实整合进模型中。为此，我们推出了WikiFactDiff数据集，该数据集记录了从特定两个时间点间，以新出现、过时及不变三种类型划分的简单事实变化情况。通过对这三种基本更新类型的灵活组合，我们模拟出多种实际更新场景。WikiFactDiff中的事实信息采用主谓宾结构展示，并配备有相应的表述模板和完型测试题目，便于运行和评估各种更新算法。相较于zsRE和CounterFact等其他数据集，WikiFactDiff更真实地反映了包含替换、归档和新增实体插入在内的多元更新情境。此外，我们还在WikiFactDiff上对现有的一些更新算法进行了实证评估。

> The factuality of large language model (LLMs) tends to decay over time since events posterior to their training are "unknown" to them. One way to keep models up-to-date could be factual update: the task of inserting, replacing, or removing certain simple (atomic) facts within the model. To study this task, we present WikiFactDiff, a dataset that describes the evolution of factual knowledge between two dates as a collection of simple facts divided into three categories: new, obsolete, and static. We describe several update scenarios arising from various combinations of these three types of basic update. The facts are represented by subject-relation-object triples; indeed, WikiFactDiff was constructed by comparing the state of the Wikidata knowledge base at 4 January 2021 and 27 February 2023. Those fact are accompanied by verbalization templates and cloze tests that enable running update algorithms and their evaluation metrics. Contrary to other datasets, such as zsRE and CounterFact, WikiFactDiff constitutes a realistic update setting that involves various update scenarios, including replacements, archival, and new entity insertions. We also present an evaluation of existing update algorithms on WikiFactDiff.

[Arxiv](https://arxiv.org/abs/2403.14364)