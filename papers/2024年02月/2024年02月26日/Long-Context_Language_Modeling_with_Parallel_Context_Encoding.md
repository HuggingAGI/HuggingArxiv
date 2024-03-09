# [通过并行上下文编码技术实现长文本上下文的语言模型构建](https://arxiv.org/abs/2402.16617)

发布时间：2024年02月26日

`LLM应用`

> Long-Context Language Modeling with Parallel Context Encoding

> 为满足多种应用需求，拓展大型语言模型（LLMs）处理更长输入的能力显得尤为重要。但Transformer高昂的计算开销，加之位置编码的局限性，使得其上下文窗口难以扩大。为此，我们创新提出“并行编码上下文扩展”（CEPE）框架，它可无缝应用于所有现存仅解码器架构的 LLMs，实现其上下文窗口的有效扩展。此框架运用小巧的编码器分段处理长输入，通过跨注意力机制让冻结的解码器能够汲取更多上下文信息。CEPE 框架高效实用，具有优良泛化性和广泛适应性：经8K标记文档训练后，成功将 LLAMA-2 的上下文窗口扩展至128K标记，不仅吞吐量提升10倍，内存占用仅为原来的六分之一。无论是在语言建模还是上下文学习任务上，CEPE 都展现出强劲性能。尤其值得一提的是，在检索增强型应用中，当其他长上下文模型面对检索到的上下文出现性能衰退时，CEPE 却能保持优秀表现。此外，我们还推出 CEPE 的一种变体，仅需借助无标注数据就能扩展指令调优模型的上下文窗口，并在 LLAMA-2-CHAT 上验证了其实用有效性，最终构建出一款能在下游任务中充分利用超长上下文的强大指令执行模型。

> Extending large language models (LLMs) to process longer inputs is crucial for numerous applications. However, the considerable computational cost of transformers, coupled with limited generalization of positional encoding, restricts the size of their context window. We introduce Context Expansion with Parallel Encoding (CEPE), a framework that can be applied to any existing decoder-only LLMs to extend their context window. CEPE adopts a small encoder to process long inputs chunk by chunk and enables the frozen decoder to leverage additional contexts via cross-attention. CEPE is efficient, generalizable, and versatile: trained with 8K-token documents, CEPE extends the context window of LLAMA-2 to 128K tokens, offering 10x the throughput with only 1/6 of the memory. CEPE yields strong performance on language modeling and in-context learning. CEPE also excels in retrieval-augmented applications, while existing long-context models degenerate with retrieved contexts. We further introduce a CEPE variant that can extend the context window of instruction-tuned models with only unlabeled data, and showcase its effectiveness on LLAMA-2-CHAT, leading to a strong instruction-following model that can leverage very long context on downstream tasks.