# RNN 仍未进化为 Transformers：揭示 In-context 检索面临的核心难题

发布时间：2024年02月29日

`RAG`

> RNNs are not Transformers (Yet): The Key Bottleneck on In-context Retrieval

> 本研究聚焦于算法问题解决中，RNNs与Transformer在表示力上的差异。我们深入探讨了以高效处理长序列著称的RNNs，在引入CoT提示后能否赶超Transformer的表现。理论分析揭示，尽管CoT有助于提升RNNs，但这并不足以拉平二者间的鸿沟；症结在于即使配合CoT，RNNs也无法完美地从上下文中提取所需信息。对涉及此类能力的任务（如关联记忆回溯、判断图形是否为树形结构），我们证实了RNNs在这方面表现力不足，难以解决，而Transformer则能应对自如。反之，通过应用如RAG及增加单个Transformer层等技术强化RNNs的上下文检索能力，可使RNNs借助CoT也能轻易解决所有能在多项式时间内解决的问题，从而有效消除与Transformer在表示力上的差距。

> This paper investigates the gap in representation powers of Recurrent Neural Networks (RNNs) and Transformers in the context of solving algorithmic problems. We focus on understanding whether RNNs, known for their memory efficiency in handling long sequences, can match the performance of Transformers, particularly when enhanced with Chain-of-Thought (CoT) prompting. Our theoretical analysis reveals that CoT improves RNNs but is insufficient to close the gap with Transformers. A key bottleneck lies in the inability of RNNs to perfectly retrieve information from the context, even with CoT: for several tasks that explicitly or implicitly require this capability, such as associative recall and determining if a graph is a tree, we prove that RNNs are not expressive enough to solve the tasks while Transformers can solve them with ease. Conversely, we prove that adopting techniques to enhance the in-context retrieval capability of RNNs, including Retrieval-Augmented Generation (RAG) and adding a single Transformer layer, can elevate RNNs to be capable of solving all polynomial-time solvable problems with CoT, hence closing the representation gap with Transformers.

[Arxiv](https://arxiv.org/abs/2402.18510)