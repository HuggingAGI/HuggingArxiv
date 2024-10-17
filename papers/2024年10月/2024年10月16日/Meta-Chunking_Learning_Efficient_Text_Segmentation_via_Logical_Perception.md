# 元块化：借助逻辑感知实现高效文本分割的学习方法

发布时间：2024年10月16日

`RAG` `问答系统`

> Meta-Chunking: Learning Efficient Text Segmentation via Logical Perception

# 摘要

> RAG 作为 LLM 的补充，虽有效但常忽略文本分块的关键环节，影响知识密集任务的质量。本文提出 Meta-Chunking，介于句子和段落间的粒度，由段落内深层语言逻辑相连的句子组成。我们设计了两种基于 LLM 的策略：Margin Sampling Chunking 和 Perplexity Chunking，分别通过概率差异和困惑度分布特征来分段和识别边界。考虑到文本复杂性，我们还提出结合 Meta-Chunking 和动态合并的策略，平衡细粒度和粗粒度分块。实验显示，Meta-Chunking 能更高效提升 RAG 的单跳和多跳问答性能，如在 2WikiMultihopQA 数据集上，性能提升 1.32，时间仅耗 45.8%。代码已开源，详见 https://github.com/IAAR-Shanghai/Meta-Chunking。

> Retrieval-Augmented Generation (RAG), while serving as a viable complement to large language models (LLMs), often overlooks the crucial aspect of text chunking within its pipeline, which impacts the quality of knowledge-intensive tasks. This paper introduces the concept of Meta-Chunking, which refers to a granularity between sentences and paragraphs, consisting of a collection of sentences within a paragraph that have deep linguistic logical connections. To implement Meta-Chunking, we designed two strategies based on LLMs: Margin Sampling Chunking and Perplexity Chunking. The former employs LLMs to perform binary classification on whether consecutive sentences need to be segmented, making decisions based on the probability difference obtained from margin sampling. The latter precisely identifies text chunk boundaries by analyzing the characteristics of perplexity distribution. Additionally, considering the inherent complexity of different texts, we propose a strategy that combines Meta-Chunking with dynamic merging to achieve a balance between fine-grained and coarse-grained text chunking. Experiments conducted on eleven datasets demonstrate that Meta-Chunking can more efficiently improve the performance of single-hop and multi-hop question answering based on RAG. For instance, on the 2WikiMultihopQA dataset, it outperforms similarity chunking by 1.32 while only consuming 45.8% of the time. Our code is available at https://github.com/IAAR-Shanghai/Meta-Chunking.

[Arxiv](https://arxiv.org/abs/2410.12788)