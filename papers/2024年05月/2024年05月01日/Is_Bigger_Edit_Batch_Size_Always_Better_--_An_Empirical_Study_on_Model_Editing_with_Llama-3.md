# 编辑批量大小越大，效果一定越佳吗？一项基于 Llama-3 模型编辑的实证探索。

发布时间：2024年05月01日

`LLM应用` `人工智能` `模型优化`

> Is Bigger Edit Batch Size Always Better? -- An Empirical Study on Model Editing with Llama-3

# 摘要

> 本研究针对最新的大型语言模型 Llama-3，进行了一项精准的模型编辑策略分析。我们评估了几种流行的编辑技术——ROME、MEMIT 和 EMMET，它们专为精细的层次化编辑而设计。通过对比多达 4096 次的编辑，我们发现了最有效的编辑层次，这些编辑策略包括顺序编辑、批量编辑，以及我们提出的顺序-批量混合编辑方法。研究结果显示，相比于顺序进行较小批量的编辑，增大编辑批量可能会对模型性能产生更明显的负面影响。因此，我们认为顺序化的模型编辑对于提升编辑效率至关重要，未来研究应更多关注如何融合批量与顺序编辑的策略。这一发现也指出了当前模型编辑方法的一个潜在限制，即追求更大的编辑批量，我们期待这能激发未来对编辑批量大小和模型编辑效能优化的进一步探索。

> This study presents a targeted model editing analysis focused on the latest large language model, Llama-3. We explore the efficacy of popular model editing techniques - ROME, MEMIT, and EMMET, which are designed for precise layer interventions. We identify the most effective layers for targeted edits through an evaluation that encompasses up to 4096 edits across three distinct strategies: sequential editing, batch editing, and a hybrid approach we call as sequential-batch editing. Our findings indicate that increasing edit batch-sizes may degrade model performance more significantly than using smaller edit batches sequentially for equal number of edits. With this, we argue that sequential model editing is an important component for scaling model editing methods and future research should focus on methods that combine both batched and sequential editing. This observation suggests a potential limitation in current model editing methods which push towards bigger edit batch sizes, and we hope it paves way for future investigations into optimizing batch sizes and model editing performance.

[Arxiv](https://arxiv.org/abs/2405.00664)