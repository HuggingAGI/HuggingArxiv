# [斩断“首因”，化解冲突：探寻语言模型中知识冲突的解读与调和机制]

发布时间：2024年02月28日

`RAG`

> Cutting Off the Head Ends the Conflict: A Mechanism for Interpreting and Mitigating Knowledge Conflicts in Language Models

> 近期研究表明，通过提供外部上下文，检索增强和工具增强技术成功拓宽了语言模型(LMs)内在记忆的边界。不过，内部记忆与外部上下文间的碰撞难以避免，会在LMs内部产生知识冲突。本论文的目标是以信息流为透视镜，深入剖析这一知识冲突的内在机制，并找准关键时刻进行精确干预以解决冲突。研究发现，在模型较深层中，存在一些作用相反而又各具特色的注意力头：记忆头负责从内部记忆中提取知识，上下文头则负责从外部环境中检索知识。进一步揭示出，LMs中知识冲突的关键触发点在于记忆头和上下文头对不一致信息流的整合过程。受此启示，我们创新性地提出了名为PH3（通过路径修补进行头部修剪）的方法，它能够在无需更新模型参数的前提下，有效削减冲突注意力头以减轻知识冲突。PH3可灵活调节八种LMs对内部记忆（提升44.0%）或外部上下文（提升38.5%）的依赖程度，并且能在开放领域的QA任务上提升LMs的表现。大量的实验也证实了我们方法在跨模型、跨关系及跨格式情况下的良好泛化能力。

> Recently, retrieval augmentation and tool augmentation have demonstrated a remarkable capability to expand the internal memory boundaries of language models (LMs) by providing external context. However, internal memory and external context inevitably clash, leading to knowledge conflicts within LMs. In this paper, we aim to interpret the mechanism of knowledge conflicts through the lens of information flow, and then mitigate conflicts by precise interventions at the pivotal point. We find there are some attention heads with opposite effects in the later layers, where memory heads can recall knowledge from internal memory, and context heads can retrieve knowledge from external context. Moreover, we reveal that the pivotal point at which knowledge conflicts emerge in LMs is the integration of inconsistent information flows by memory heads and context heads. Inspired by the insights, we propose a novel method called Pruning Head via PatH PatcHing (PH3), which can efficiently mitigate knowledge conflicts by pruning conflicting attention heads without updating model parameters. PH3 can flexibly control eight LMs to use internal memory ($\uparrow$ 44.0%) or external context ($\uparrow$ 38.5%). Moreover, PH3 can also improve the performance of LMs on open-domain QA tasks. We also conduct extensive experiments to demonstrate the cross-model, cross-relation, and cross-format generalization of our method.

[Arxiv](https://arxiv.org/abs/2402.18154)