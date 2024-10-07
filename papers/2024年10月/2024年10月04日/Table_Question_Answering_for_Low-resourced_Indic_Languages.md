# 低资源印度语言的表格问答技术

发布时间：2024年10月04日

`LLM应用` `低资源语言` `数据生成`

> Table Question Answering for Low-resourced Indic Languages

# 摘要

> TableQA 任务涉及在结构化表格上回答问题，输出可以是单个单元格或整个表格。当前研究多集中于高资源语言，而中低资源语言因缺乏标注数据和神经模型而进展缓慢。为此，我们开发了一种全自动的大规模低资源语言 TableQA 数据生成方法，并将其应用于孟加拉语和印地语，这两种语言此前无 TableQA 数据集或模型。实验表明，基于我们数据集训练的 TableQA 模型性能超越了现有最先进的 LLM。此外，我们还探讨了这些模型在数学推理和零-shot 跨语言迁移方面的表现。本研究首次聚焦于低资源语言 TableQA 的可扩展数据生成与评估，并提出了一种通用的数据生成方法，适用于任何有网络存在的低资源语言。相关数据集、模型和代码已公开发布（https://github.com/kolk/Low-Resource-TableQA-Indic-languages）。

> TableQA is the task of answering questions over tables of structured information, returning individual cells or tables as output. TableQA research has focused primarily on high-resource languages, leaving medium- and low-resource languages with little progress due to scarcity of annotated data and neural models. We address this gap by introducing a fully automatic large-scale tableQA data generation process for low-resource languages with limited budget. We incorporate our data generation method on two Indic languages, Bengali and Hindi, which have no tableQA datasets or models. TableQA models trained on our large-scale datasets outperform state-of-the-art LLMs. We further study the trained models on different aspects, including mathematical reasoning capabilities and zero-shot cross-lingual transfer. Our work is the first on low-resource tableQA focusing on scalable data generation and evaluation procedures. Our proposed data generation method can be applied to any low-resource language with a web presence. We release datasets, models, and code (https://github.com/kolk/Low-Resource-TableQA-Indic-languages).

[Arxiv](https://arxiv.org/abs/2410.03576)