# TokenFormer：以令牌化模型参数重新审视 Transformer 的缩放

发布时间：2024年10月30日

`LLM理论` `计算机视觉`

> TokenFormer: Rethinking Transformer Scaling with Tokenized Model Parameters

# 摘要

> 摘要：Transformers 因其在各领域的卓越表现，已成为基础模型的主流架构。然而，扩展此类模型的高昂成本是个关键问题。这主要源于其在线性投影中对固定数量参数的依赖。一旦进行架构修改（如通道维度调整），整个模型往往得从头重训。随着模型规模持续增大，这种策略致使计算成本愈发高昂，难以为继。为解决此难题，我们推出 TokenFormer，这是一种天然可扩展的架构，它不仅将注意力机制用于输入标记的计算，还用于标记与模型参数的交互，进而增强架构的灵活性。把模型参数视作标记，我们用标记 - 参数注意力层取代了 Transformers 中的所有线性投影，其中输入标记充当查询，模型参数作为键和值。这种重新设计实现了逐步高效的扩展，无需从头重训。我们的模型通过逐步添加新的键值参数对，从 124M 扩展至 1.4B 参数，性能与从头训练的 Transformers 相当，同时大幅降低了训练成本。代码和模型可在该网址获取。

> 
Abstract:Transformers have become the predominant architecture in foundation models due to their excellent performance across various domains. However, the substantial cost of scaling these models remains a significant concern. This problem arises primarily from their dependence on a fixed number of parameters within linear projections. When architectural modifications (e.g., channel dimensions) are introduced, the entire model typically requires retraining from scratch. As model sizes continue growing, this strategy results in increasingly high computational costs and becomes unsustainable. To overcome this problem, we introduce TokenFormer, a natively scalable architecture that leverages the attention mechanism not only for computations among input tokens but also for interactions between tokens and model parameters, thereby enhancing architectural flexibility. By treating model parameters as tokens, we replace all the linear projections in Transformers with our token-parameter attention layer, where input tokens act as queries and model parameters as keys and values. This reformulation allows for progressive and efficient scaling without necessitating retraining from scratch. Our model scales from 124M to 1.4B parameters by incrementally adding new key-value parameter pairs, achieving performance comparable to Transformers trained from scratch while greatly reducing training costs. Code and models are available at this url.
    

[Arxiv](https://arxiv.org/pdf/2410.23168)