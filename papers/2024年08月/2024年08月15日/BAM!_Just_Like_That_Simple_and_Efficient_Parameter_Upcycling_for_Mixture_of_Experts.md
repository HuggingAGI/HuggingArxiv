# BAM！简单高效：专家混合模型的参数升级新策略

发布时间：2024年08月15日

`LLM理论` `人工智能` `机器学习`

> BAM! Just Like That: Simple and Efficient Parameter Upcycling for Mixture of Experts

# 摘要

> Mixture of Experts (MoE) 框架因其超越密集模型的性能而备受青睐，但大规模从头训练 MoE 成本高昂。现有方法通过预训练密集模型并将其用于初始化 MoE 来缓解这一问题，但仅限于 FFN 层的参数复用限制了其优势。我们提出的 BAM（Branch-Attend-Mix）方法，不仅利用密集模型的 FFN 初始化 MoE，还通过将注意力参数初始化为 MoA 层的软变体，全面利用了这些模型。我们探索了两种注意力参数的升级再利用方法：一是从密集模型中初始化单独的注意力专家以优化性能；二是共享关键和值参数以提升推理效率。此外，我们采用并行注意力转换器架构，使注意力与 FFN 专家能同时计算，从而提高效率。实验结果显示，在相同的计算和数据约束下，BAM 在困惑度和下游任务性能方面均优于基线。

> The Mixture of Experts (MoE) framework has become a popular architecture for large language models due to its superior performance over dense models. However, training MoEs from scratch in a large-scale regime is prohibitively expensive. Existing methods mitigate this by pre-training multiple dense expert models independently and using them to initialize an MoE. This is done by using experts' feed-forward network (FFN) to initialize the MoE's experts while merging other parameters. However, this method limits the reuse of dense model parameters to only the FFN layers, thereby constraining the advantages when "upcycling" these models into MoEs. We propose BAM (Branch-Attend-Mix), a simple yet effective method that addresses this shortcoming. BAM makes full use of specialized dense models by not only using their FFN to initialize the MoE layers but also leveraging experts' attention parameters fully by initializing them into a soft-variant of Mixture of Attention (MoA) layers. We explore two methods for upcycling attention parameters: 1) initializing separate attention experts from dense models including all attention parameters for the best model performance; and 2) sharing key and value parameters across all experts to facilitate for better inference efficiency. To further improve efficiency, we adopt a parallel attention transformer architecture to MoEs, which allows the attention experts and FFN experts to be computed concurrently. Our experiments on seed models ranging from 590 million to 2 billion parameters demonstrate that BAM surpasses baselines in both perplexity and downstream task performance, within the same computational and data constraints.

[Arxiv](https://arxiv.org/abs/2408.08274)