# 借助语言家族专家的混合策略，我们高效地将医学大型语言模型扩展至50种语言，实现真正的语言民主化。

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Efficiently Democratizing Medical LLMs for 50 Languages via a Mixture of Language Family Experts

# 摘要

> 将医疗大型语言模型本地化可降低医疗服务的门槛，但数据稀缺仍是低资源语言的难题。为此，我们构建了高质量医疗数据集并进行分析。为利用多语言LLMs的泛化能力，我们采用MoE模块化从多语言视角探索LLMs的内部信息流。我们提出了一种新的MoE路由方法，结合特定语言专家和跨语言路由。受电路理论启发，我们发现早期层集中跨语言信息流，后期层则呈现语言特定发散。这一发现催生了Post-MoE架构，仅在后期层应用稀疏路由。实验表明，此方法提升了多语言模型的泛化能力并保持了解释性。为高效扩展至50种语言，我们引入语言家族专家概念，借鉴语言学先验知识，实现无额外参数的语言扩展。

> Adapting medical Large Language Models to local languages can reduce barriers to accessing healthcare services, but data scarcity remains a significant challenge, particularly for low-resource languages. To address this, we first construct a high-quality medical dataset and conduct analysis to ensure its quality. In order to leverage the generalization capability of multilingual LLMs to efficiently scale to more resource-constrained languages, we explore the internal information flow of LLMs from a multilingual perspective using Mixture of Experts (MoE) modularity. Technically, we propose a novel MoE routing method that employs language-specific experts and cross-lingual routing. Inspired by circuit theory, our routing analysis revealed a Spread Out in the End information flow mechanism: while earlier layers concentrate cross-lingual information flow, the later layers exhibit language-specific divergence. This insight directly led to the development of the Post-MoE architecture, which applies sparse routing only in the later layers while maintaining dense others. Experimental results demonstrate that this approach enhances the generalization of multilingual models to other languages while preserving interpretability. Finally, to efficiently scale the model to 50 languages, we introduce the concept of language family experts, drawing on linguistic priors, which enables scaling the number of languages without adding additional parameters.

[Arxiv](https://arxiv.org/abs/2410.10626)