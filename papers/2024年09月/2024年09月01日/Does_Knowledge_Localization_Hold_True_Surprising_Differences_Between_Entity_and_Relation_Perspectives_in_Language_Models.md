# 语言模型中的知识定位是否成立？实体与关系视角间存在令人惊讶的差异。

发布时间：2024年09月01日

`LLM理论` `人工智能`

> Does Knowledge Localization Hold True? Surprising Differences Between Entity and Relation Perspectives in Language Models

# 摘要

> 大型语言模型不仅封装了知识，还在多项自然语言处理任务中表现卓越。最新研究指出，这些知识具体体现在模型参数如中间层的MLP权重中。本研究通过知识编辑深入探讨了实体与关系知识的差异，发现两者无法直接转换或映射，这一发现颇具颠覆性，因为理论上，修改同一知识三元组中的实体或关系应产生相同效果。为深入理解这一差异，我们运用因果分析，揭示了关系知识不仅存储于MLP权重，还显著编码于注意力模块中。这一发现不仅凸显了语言模型知识存储的复杂性，也为未来在这些模型中精准操作特定类型知识提供了新的视角。

> Large language models encapsulate knowledge and have demonstrated superior performance on various natural language processing tasks. Recent studies have localized this knowledge to specific model parameters, such as the MLP weights in intermediate layers. This study investigates the differences between entity and relational knowledge through knowledge editing. Our findings reveal that entity and relational knowledge cannot be directly transferred or mapped to each other. This result is unexpected, as logically, modifying the entity or the relation within the same knowledge triplet should yield equivalent outcomes. To further elucidate the differences between entity and relational knowledge, we employ causal analysis to investigate how relational knowledge is stored in pre-trained models. Contrary to prior research suggesting that knowledge is stored in MLP weights, our experiments demonstrate that relational knowledge is also significantly encoded in attention modules. This insight highlights the multifaceted nature of knowledge storage in language models, underscoring the complexity of manipulating specific types of knowledge within these models.

[Arxiv](https://arxiv.org/abs/2409.00617)