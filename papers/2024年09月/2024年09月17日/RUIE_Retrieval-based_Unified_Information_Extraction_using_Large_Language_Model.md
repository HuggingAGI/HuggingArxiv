# RUIE：利用大型语言模型实现基于检索的统一信息提取

发布时间：2024年09月17日

`RAG` `信息提取`

> RUIE: Retrieval-based Unified Information Extraction using Large Language Model

# 摘要

> 统一信息提取 (UIE) 的目标是使用单一模型或框架完成所有信息提取任务。然而，以往的方法主要依赖于构建数据集对大型语言模型 (LLM) 进行指令调优，这不仅耗费大量计算资源，还难以泛化到新任务。为此，我们提出了 RUIE (基于检索的统一信息提取)，通过利用上下文学习实现快速泛化并降低计算成本。RUIE 的核心挑战在于为 LLM 选择最有效的演示，以应对多样化的信息提取任务。我们通过整合 LLM 的排序偏好和设计关键词增强的奖励模型，捕捉查询与演示间的细微关系。随后，我们通过对比学习和知识蒸馏训练了一个双编码器检索器。据我们所知，RUIE 是首个可训练的 UIE 检索框架。实验结果显示，RUIE 在泛化到新任务方面表现优异，平均 F1 分数分别比指令调优方法和其他检索器高出 19.22 和 3.13。进一步分析表明，RUIE 能适应不同大小的 LLM，并凸显其关键组件的重要性。

> Unified information extraction (UIE) aims to complete all information extraction tasks using a single model or framework. While previous work has primarily focused on instruction-tuning large language models (LLMs) with constructed datasets, these methods require significant computational resources and struggle to generalize to unseen tasks. To address these limitations, we propose RUIE (Retrieval-based Unified Information Extraction), a framework that leverages in-context learning to enable rapid generalization while reducing computational costs. The key challenge in RUIE is selecting the most beneficial demonstrations for LLMs to effectively handle diverse IE tasks. To achieve this, we integrate LLM preferences for ranking candidate demonstrations and design a keyword-enhanced reward model to capture fine-grained relationships between queries and demonstrations. We then train a bi-encoder retriever for UIE through contrastive learning and knowledge distillation. To the best of our knowledge, RUIE is the first trainable retrieval framework for UIE. Experimental results on 8 held-out datasets demonstrate RUIE's effectiveness in generalizing to unseen tasks, with average F1-score improvements of 19.22 and 3.13 compared to instruction-tuning methods and other retrievers, respectively. Further analysis confirms RUIE's adaptability to LLMs of varying sizes and the importance of its key components.

[Arxiv](https://arxiv.org/abs/2409.11673)