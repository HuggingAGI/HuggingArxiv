# 多模态大型语言模型助力逆向分子设计与逆合成规划

发布时间：2024年10月05日

`LLM应用` `材料科学` `药物设计`

> Multimodal Large Language Models for Inverse Molecular Design with Retrosynthetic Planning

# 摘要

> 尽管 LLM 已能处理图像，但适应图结构仍具挑战，限制了其在材料和药物设计中的应用。为此，我们推出了 Llamole，首个能交错生成文本和图的多模态 LLM，助力分子逆设计与逆合成规划。Llamole 结合了基础 LLM、Graph Diffusion Transformer 和 Graph Neural Networks，实现多条件分子生成与文本内反应推断，并通过增强的分子理解灵活调控各图模块。此外，Llamole 还集成了 A* 搜索与基于 LLM 的成本函数，提升逆合成规划效率。我们通过基准数据集和广泛实验，验证了 Llamole 在上下文学习和监督微调中的卓越表现，其在 12 项指标上显著超越了 14 个适应的 LLM。

> While large language models (LLMs) have integrated images, adapting them to graphs remains challenging, limiting their applications in materials and drug design. This difficulty stems from the need for coherent autoregressive generation across texts and graphs. To address this, we introduce Llamole, the first multimodal LLM capable of interleaved text and graph generation, enabling molecular inverse design with retrosynthetic planning. Llamole integrates a base LLM with the Graph Diffusion Transformer and Graph Neural Networks for multi-conditional molecular generation and reaction inference within texts, while the LLM, with enhanced molecular understanding, flexibly controls activation among the different graph modules. Additionally, Llamole integrates A* search with LLM-based cost functions for efficient retrosynthetic planning. We create benchmarking datasets and conduct extensive experiments to evaluate Llamole against in-context learning and supervised fine-tuning. Llamole significantly outperforms 14 adapted LLMs across 12 metrics for controllable molecular design and retrosynthetic planning.

[Arxiv](https://arxiv.org/abs/2410.04223)