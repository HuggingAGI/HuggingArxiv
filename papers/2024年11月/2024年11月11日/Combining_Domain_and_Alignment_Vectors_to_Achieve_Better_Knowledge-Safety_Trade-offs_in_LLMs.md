# 将领域向量和对齐向量相结合，以在大型语言模型（LLM）中实现更好的知识-安全权衡。

发布时间：2024年11月11日

`LLM应用`

> Combining Domain and Alignment Vectors to Achieve Better Knowledge-Safety Trade-offs in LLMs

# 摘要

> 与通用的指令调整型模型相比，在特定技术领域训练表现出色的领域专家型大型语言模型（LLM）的兴趣日益浓厚。然而，这些专家模型在这个过程中往往会丧失其安全能力，使它们能够生成有害内容。作为一种解决方案，我们引入了一种高效且有效的基于合并的对齐方法，称为 	extsc{MergeAlign}，它对领域和对齐向量进行插值，在保留其效用的同时创建更安全的特定领域模型。我们将 	extsc{MergeAlign} 应用于医学和金融领域的 Llama3 变体专家模型，在特定领域基准测试中获得了显著的对齐改进，且几乎没有或没有性能下降。我们通过模型相似性指标研究模型合并的影响以及被合并的单个模型的贡献。我们希望我们的发现能开辟新的研究途径，并激发更高效地开发安全的专家型 LLM。

> There is a growing interest in training domain-expert LLMs that excel in specific technical fields compared to their general-purpose instruction-tuned counterparts. However, these expert models often experience a loss in their safety abilities in the process, making them capable of generating harmful content. As a solution, we introduce an efficient and effective merging-based alignment method called \textsc{MergeAlign} that interpolates the domain and alignment vectors, creating safer domain-specific models while preserving their utility. We apply \textsc{MergeAlign} on Llama3 variants that are experts in medicine and finance, obtaining substantial alignment improvements with minimal to no degradation on domain-specific benchmarks. We study the impact of model merging through model similarity metrics and contributions of individual models being merged. We hope our findings open new research avenues and inspire more efficient development of safe expert LLMs.

[Arxiv](https://arxiv.org/abs/2411.06824)