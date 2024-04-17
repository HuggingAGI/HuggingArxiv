# 通过层级上下文融合，我们能够提升预训练大型语言模型对长篇幅上下文的把握与理解能力。

发布时间：2024年04月16日

`LLM理论` `内存优化`

> Hierarchical Context Merging: Better Long Context Understanding for Pre-trained LLMs

# 摘要

> 大型语言模型（LLMs）在自然语言处理的多个任务中展现出了非凡的能力。但它们最大的挑战在于处理能力的限制，也就是一次能处理的标记数有限。以往的研究尝试通过改变架构和调整位置编码来扩展这一能力，但这些方法往往成本高昂，或者无法满足自注意力机制的计算需求。本文介绍了一种名为层次化上下文合并（HOMER）的新方法，它无需额外训练即可突破这些局限。HOMER通过分治算法将长文本切分成易于处理的小段，然后逐层合并，采用层层递进的策略。在合并前，还会采用减少标记数的技巧，以提高内存效率。此外，我们还提出了一种优化的计算顺序，使得内存需求与输入长度成对数增长，特别适合内存资源受限的场景。实验证明，HOMER在性能和内存使用效率上都表现出色，极大地扩展了LLMs在需要处理大量上下文的场合的应用范围。相关代码已在 https://github.com/alinlab/HOMER 上发布。

> Large language models (LLMs) have shown remarkable performance in various natural language processing tasks. However, a primary constraint they face is the context limit, i.e., the maximum number of tokens they can process. Previous works have explored architectural changes and modifications in positional encoding to relax the constraint, but they often require expensive training or do not address the computational demands of self-attention. In this paper, we present Hierarchical cOntext MERging (HOMER), a new training-free scheme designed to overcome the limitations. HOMER uses a divide-and-conquer algorithm, dividing long inputs into manageable chunks. Each chunk is then processed collectively, employing a hierarchical strategy that merges adjacent chunks at progressive transformer layers. A token reduction technique precedes each merging, ensuring memory usage efficiency. We also propose an optimized computational order reducing the memory requirement to logarithmically scale with respect to input length, making it especially favorable for environments with tight memory restrictions. Our experiments demonstrate the proposed method's superior performance and memory efficiency, enabling the broader use of LLMs in contexts requiring extended context. Code is available at https://github.com/alinlab/HOMER.

[Arxiv](https://arxiv.org/abs/2404.10308)