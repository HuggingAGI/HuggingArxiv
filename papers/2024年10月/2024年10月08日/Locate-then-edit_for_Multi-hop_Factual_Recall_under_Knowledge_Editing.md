# 知识编辑中的多跳事实回忆：先定位，再编辑

发布时间：2024年10月08日

`LLM理论` `人工智能` `知识编辑`

> Locate-then-edit for Multi-hop Factual Recall under Knowledge Editing

# 摘要

> locate-then-edit 范式在 LLM 的知识编辑中展现出巨大潜力。尽管现有方法在单跳任务中表现出色，但在涉及新知识的多跳任务中却屡屡受挫。本文通过机制可解释性工具发现，多跳任务中 LLM 更依赖深层 MLP 层，这与单跳任务的浅层依赖形成鲜明对比。这解释了现有方法在多跳查询中的不足，因其仅编辑浅层。为此，我们提出 IFMET，一种能同时编辑浅层和深层 MLP 层的新方法。IFMET 通过多跳编辑提示和补充集，精准定位并修改各推理阶段的知识。实验证明，IFMET 在多跳任务中显著提升性能，成功突破了现有方法的瓶颈。

> The locate-then-edit paradigm has shown significant promise for knowledge editing (KE) in Large Language Models (LLMs). While previous methods perform well on single-hop fact recall tasks, they consistently struggle with multi-hop factual recall tasks involving newly edited knowledge. In this paper, leveraging tools in mechanistic interpretability, we first identify that in multi-hop tasks, LLMs tend to retrieve implicit subject knowledge from deeper MLP layers, unlike single-hop tasks, which rely on earlier layers. This distinction explains the poor performance of current methods in multi-hop queries, as they primarily focus on editing shallow layers, leaving deeper layers unchanged. To address this, we propose IFMET, a novel locate-then-edit KE approach designed to edit both shallow and deep MLP layers. IFMET employs multi-hop editing prompts and supplementary sets to locate and modify knowledge across different reasoning stages. Experimental results demonstrate that IFMET significantly improves performance on multi-hop factual recall tasks, effectively overcoming the limitations of previous locate-then-edit methods.

[Arxiv](https://arxiv.org/abs/2410.06331)