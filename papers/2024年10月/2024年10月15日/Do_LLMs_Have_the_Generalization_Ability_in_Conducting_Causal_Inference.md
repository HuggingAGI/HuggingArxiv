# 大型语言模型是否具备进行因果推理的泛化能力？

发布时间：2024年10月15日

`LLM理论` `因果推断` `人工智能`

> Do LLMs Have the Generalization Ability in Conducting Causal Inference?

# 摘要

> 在因果推断领域，泛化能力至关重要，它帮助我们在新数据上估算未知现象间的因果关系，从而拓展知识边界。尽管已有研究评估了大型语言模型 (LLM) 在已知现象上的因果推断能力，但其在未见现象上的泛化能力仍是一个未解之谜。本文选取了因果路径发现 (CP)、后门调整 (BA)、事实推断 (FI) 和反事实推断 (CI) 四个任务，作为因果推断的代表。我们设计了一个基准生成框架，通过随机图和节点名称，模拟新因果场景中的问题。基于此，我们构建了一个复杂度各异的基准数据集。实验显示，LLM 在简单 CP、FI 和复杂 CI 问题上表现出色，但在 BA 问题上表现不佳，且性能随问题复杂度波动明显。此外，即使现象名称新颖，若包含现有术语，泛化性能仍可能受其干扰。

> In causal inference, generalization capability refers to the ability to conduct causal inference methods on new data to estimate the causal-effect between unknown phenomenon, which is crucial for expanding the boundaries of knowledge. Studies have evaluated the causal inference capabilities of Large Language Models (LLMs) concerning known phenomena, yet the generalization capabilities of LLMs concerning unseen phenomena remain unexplored. In this paper, we selected four tasks: Causal Path Discovery (CP), Backdoor Adjustment (BA), Factual Inference (FI), and Counterfactual Inference (CI) as representatives of causal inference tasks. To generate evaluation questions about previously unseen phenomena in new data on the four tasks, we propose a benchmark generation framework, which employs randomly generated graphs and node names to formulate questions within hypothetical new causal scenarios. Based on this framework, we compile a benchmark dataset of varying levels of question complexity. We extensively tested the generalization capabilities of five leading LLMs across four tasks. Experiment results reveal that while LLMs exhibit good generalization performance in solving simple CP, FI, and complex CI questions, they encounter difficulties when tackling BA questions and face obvious performance fluctuations as the problem complexity changes. Furthermore, when the names of phenomena incorporate existing terms, even if these names are entirely novel, their generalization performance can still be hindered by interference from familiar terms.

[Arxiv](https://arxiv.org/abs/2410.11385)