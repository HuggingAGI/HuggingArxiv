# 大型语言模型中的绑定表示研究

发布时间：2024年09月09日

`LLM理论` `人工智能`

> Representational Analysis of Binding in Large Language Models

# 摘要

> 实体跟踪在复杂推理中不可或缺。语言模型需将实体与其属性绑定，如将“盒子 Z”与“咖啡”关联，以便在后续推理中正确回忆。Feng 和 Steinhardt (2023) 提出的绑定 ID 机制虽解释了这一过程，但未直接捕获决定性信息。我们通过定位 BI 信息原型，揭示了隐藏状态中的低秩子空间，该子空间编码了实体与属性的顺序，并因果决定了绑定关系。我们采用主成分分析成功识别了这一子空间，并发现通过调整子空间方向，LM 能将实体与其他属性绑定，如将“盒子 Z”与“石头”或“地图”关联。

> Entity tracking is essential for complex reasoning. To perform in-context entity tracking, language models (LMs) must bind an entity to its attribute (e.g., bind a container to its content) to recall attribute for a given entity. For example, given a context mentioning ``The coffee is in Box Z, the stone is in Box M, the map is in Box H'', to infer ``Box Z contains the coffee'' later, LMs must bind ``Box Z'' to ``coffee''. To explain the binding behaviour of LMs, Feng and Steinhardt (2023) introduce a Binding ID mechanism and state that LMs use a abstract concept called Binding ID (BI) to internally mark entity-attribute pairs. However, they have not directly captured the BI determinant information from entity activations. In this work, we provide a novel view of the Binding ID mechanism by localizing the prototype of BI information. Specifically, we discover that there exists a low-rank subspace in the hidden state (or activation) of LMs, that primarily encodes the order of entity and attribute and which is used as the prototype of BI to causally determine the binding. To identify this subspace, we choose principle component analysis as our first attempt and it is empirically proven to be effective. Moreover, we also discover that when editing representations along directions in the subspace, LMs tend to bind a given entity to other attributes accordingly. For example, by patching activations along the BI encoding direction we can make the LM to infer ``Box Z contains the stone'' and ``Box Z contains the map''.

[Arxiv](https://arxiv.org/abs/2409.05448)