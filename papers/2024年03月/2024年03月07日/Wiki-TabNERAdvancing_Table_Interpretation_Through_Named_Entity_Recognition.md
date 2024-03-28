# Wiki-TabNER项目致力于借助命名实体识别技术提升表格理解能力，从而推动表格信息的有效解读。

发布时间：2024年03月07日

`LLM应用`

> Wiki-TabNER:Advancing Table Interpretation Through Named Entity Recognition

# 摘要

> 网络表格富含宝贵知识，由此催生了一系列致力于解决TI任务的表格语言模型。本文聚焦于一个广泛应用的TI任务基准数据集，尤其关注其实体链接子任务，却发现其设计过于简化，可能导致评估效果打折扣，且无法如实反映真实场景下的表格特点。为此，我们精心构造并标注了一个更具挑战性的新数据集。同时，我们创新性地提出了单元格内命名实体识别问题，以深化对实体链接任务的研究。进一步地，我们设计了一个提示框架，用以评测新开发的LLMs在此新型TI任务上的性能。通过在多种设置下对LLMs进行提示实验，我们采用随机及基于相似度的方法挑选样本展示给模型，并通过消融研究揭示少量示例的重要影响。此外，我们通过定性分析揭示模型遇到的难题，并探讨了所提数据集的局限性。

> Web tables contain a large amount of valuable knowledge and have inspired tabular language models aimed at tackling table interpretation (TI) tasks. In this paper, we analyse a widely used benchmark dataset for evaluation of TI tasks, particularly focusing on the entity linking task. Our analysis reveals that this dataset is overly simplified, potentially reducing its effectiveness for thorough evaluation and failing to accurately represent tables as they appear in the real-world. To overcome this drawback, we construct and annotate a new more challenging dataset. In addition to introducing the new dataset, we also introduce a novel problem aimed at addressing the entity linking task: named entity recognition within cells. Finally, we propose a prompting framework for evaluating the newly developed large language models (LLMs) on this novel TI task. We conduct experiments on prompting LLMs under various settings, where we use both random and similarity-based selection to choose the examples presented to the models. Our ablation study helps us gain insights into the impact of the few-shot examples. Additionally, we perform qualitative analysis to gain insights into the challenges encountered by the models and to understand the limitations of the proposed dataset.

[Arxiv](https://arxiv.org/abs/2403.04577)