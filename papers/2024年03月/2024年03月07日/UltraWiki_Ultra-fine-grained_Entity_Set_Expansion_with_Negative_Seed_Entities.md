# UltraWiki项目致力于通过引入负向种子实体，实现对实体集进行超精细的扩展探索。

发布时间：2024年03月07日

`Agent`

> UltraWiki: Ultra-fine-grained Entity Set Expansion with Negative Seed Entities

# 摘要

> ESE技术致力于发现与特定种子实体集合同属语义类的新实体，然而在面对超细粒度语义类时，传统方法因过度依赖积极种子实体而遭遇难题。超细粒度语义类因其严格的具体属性约束，在单一积极种子实体描述下会引发两类问题：一是不同超细粒度语义类间的模糊不清；二是难以界定“非目标”语义。为此，我们创新性地将负向种子实体引入输入中，它们虽与积极种子实体同属一细粒度语义类，但在特定属性上有所差异。这种正负属性对比有效消除了语义混淆，并能直观地表述出“排除项”。为了衡量模型在处理Ultra-ESE任务的表现，我们创建了首个专门针对此任务的大规模数据集UltraWiki，涵盖了236个超细粒度语义类，每个查询都包含3-5个积极和负向种子实体。我们分别提出基于检索的RetExpan框架和基于生成的GenExpan框架，从不同角度全面检验大型语言模型在此领域的实力。同时，我们还设计了三种策略——对比学习、检索增强以及链式思维推理，以提升模型对超细粒度实体语义的深入理解。大量的实验证明了这些策略的有效性，并显示出Ultra-ESE领域仍有巨大的优化潜力。

> Entity Set Expansion (ESE) aims to identify new entities belonging to the same semantic class as a given set of seed entities. Traditional methods primarily relied on positive seed entities to represent a target semantic class, which poses challenge for the representation of ultra-fine-grained semantic classes. Ultra-fine-grained semantic classes are defined based on fine-grained semantic classes with more specific attribute constraints. Describing it with positive seed entities alone cause two issues: (i) Ambiguity among ultra-fine-grained semantic classes. (ii) Inability to define "unwanted" semantic. Due to these inherent shortcomings, previous methods struggle to address the ultra-fine-grained ESE (Ultra-ESE). To solve this issue, we first introduce negative seed entities in the inputs, which belong to the same fine-grained semantic class as the positive seed entities but differ in certain attributes. Negative seed entities eliminate the semantic ambiguity by contrast between positive and negative attributes. Meanwhile, it provide a straightforward way to express "unwanted". To assess model performance in Ultra-ESE, we constructed UltraWiki, the first large-scale dataset tailored for Ultra-ESE. UltraWiki encompasses 236 ultra-fine-grained semantic classes, where each query of them is represented with 3-5 positive and negative seed entities. A retrieval-based framework RetExpan and a generation-based framework GenExpan are proposed to comprehensively assess the efficacy of large language models from two different paradigms in Ultra-ESE. Moreover, we devised three strategies to enhance models' comprehension of ultra-fine-grained entities semantics: contrastive learning, retrieval augmentation, and chain-of-thought reasoning. Extensive experiments confirm the effectiveness of our proposed strategies and also reveal that there remains a large space for improvement in Ultra-ESE.

[Arxiv](https://arxiv.org/abs/2403.04247)