# 自适应问答：借助来源引用，提升语言模型应对知识冲突的熟练度

发布时间：2024年10月05日

`RAG` `问答系统` `数据集构建`

> Adaptive Question Answering: Enhancing Language Model Proficiency for Addressing Knowledge Conflicts with Source Citations

# 摘要

> 知识冲突是问答任务中的关键难题，因为互联网充斥着相互矛盾的事实和观点。尽管一些研究在处理多答案的模糊情境方面有所进展，但往往忽略了提供答案来源，让用户自行判断真伪。而现有的引用生成研究则主要集中在单一答案的明确情境中，未能应对现实世界的复杂性。本研究填补了这一空白，提出了在多答案模糊情境中进行带有来源引用的问答新任务。我们构建了一个包含五个新数据集、首个现实世界模糊多跳QA数据集、两个新评估指标和多个强基线的综合框架，旨在推动问答研究，开发更可靠和可解释的系统。

> Resolving knowledge conflicts is a crucial challenge in Question Answering (QA) tasks, as the internet contains numerous conflicting facts and opinions. While some research has made progress in tackling ambiguous settings where multiple valid answers exist, these approaches often neglect to provide source citations, leaving users to evaluate the factuality of each answer. On the other hand, existing work on citation generation has focused on unambiguous settings with single answers, failing to address the complexity of real-world scenarios. Despite the importance of both aspects, no prior research has combined them, leaving a significant gap in the development of QA systems. In this work, we bridge this gap by proposing the novel task of QA with source citation in ambiguous settings, where multiple valid answers exist. To facilitate research in this area, we create a comprehensive framework consisting of: (1) five novel datasets, obtained by augmenting three existing reading comprehension datasets with citation meta-data across various ambiguous settings, such as distractors and paraphrasing; (2) the first ambiguous multi-hop QA dataset featuring real-world, naturally occurring contexts; (3) two new metrics to evaluate models' performances; and (4) several strong baselines using rule-based, prompting, and finetuning approaches over five large language models. We hope that this new task, datasets, metrics, and baselines will inspire the community to push the boundaries of QA research and develop more trustworthy and interpretable systems.

[Arxiv](https://arxiv.org/abs/2410.04241)