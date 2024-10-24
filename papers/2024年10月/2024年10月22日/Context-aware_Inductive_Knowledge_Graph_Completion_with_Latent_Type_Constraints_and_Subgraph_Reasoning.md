# 具有潜在类型约束和子图推理的上下文感知归纳知识图谱补全

发布时间：2024年10月22日

`LLM应用` `知识图谱` `人工智能`

> Context-aware Inductive Knowledge Graph Completion with Latent Type Constraints and Subgraph Reasoning

# 摘要

> 归纳知识图谱补全（KGC）旨在预测具有未见过的实体的缺失三元组。最近的工作侧重于将头实体和尾实体之间的推理路径建模为直接支持证据。然而，这些方法严重依赖于推理路径的存在和质量，这限制了它们在不同场景中的普遍适用性。此外，我们观察到知识图谱中固有的潜在类型约束和相邻事实在推断缺失三元组时也至关重要。为了有效地利用知识图谱中的所有有用信息，我们引入了 CATS，一种新颖的上下文感知归纳 KGC 解决方案。在适当的提示和监督微调的充分指导下，CATS 激活了大型语言模型强大的语义理解和推理能力，以评估由两个模块组成的查询三元组的存在。首先，类型感知推理模块评估候选实体是否与查询关系所要求的潜在实体类型匹配。然后，子图推理模块选择相关的推理路径和相邻事实，并评估它们与查询三元组的相关性。在三个广泛使用的数据集上的实验结果表明，CATS 在 18 个转导、归纳和少样本设置中的 16 个中显著优于最先进的方法，平均绝对 MRR 提高了 7.2％。

> Inductive knowledge graph completion (KGC) aims to predict missing triples with unseen entities. Recent works focus on modeling reasoning paths between the head and tail entity as direct supporting evidence. However, these methods depend heavily on the existence and quality of reasoning paths, which limits their general applicability in different scenarios. In addition, we observe that latent type constraints and neighboring facts inherent in KGs are also vital in inferring missing triples. To effectively utilize all useful information in KGs, we introduce CATS, a novel context-aware inductive KGC solution. With sufficient guidance from proper prompts and supervised fine-tuning, CATS activates the strong semantic understanding and reasoning capabilities of large language models to assess the existence of query triples, which consist of two modules. First, the type-aware reasoning module evaluates whether the candidate entity matches the latent entity type as required by the query relation. Then, the subgraph reasoning module selects relevant reasoning paths and neighboring facts, and evaluates their correlation to the query triple. Experiment results on three widely used datasets demonstrate that CATS significantly outperforms state-of-the-art methods in 16 out of 18 transductive, inductive, and few-shot settings with an average absolute MRR improvement of 7.2%.

[Arxiv](https://arxiv.org/abs/2410.16803)