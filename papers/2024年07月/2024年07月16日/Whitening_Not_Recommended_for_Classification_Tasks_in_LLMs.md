# 在LLM中，分类任务时白化处理并非良策。

发布时间：2024年07月16日

`LLM应用` `机器学习`

> Whitening Not Recommended for Classification Tasks in LLMs

# 摘要

> 句子嵌入作为 NLP 的核心，白化技术被认为能提升 LLM 的嵌入质量。但研究发现，白化的有效性因模型和任务而异，尤其在分类任务中，白化反而降低了嵌入质量。通过广泛实验验证了这一发现。此外，我们还深入研究了多种白化方法，如 PCA、ZCA 等，并开发了 LLM 嵌入评估工具 SentEval+。

> Sentence embedding is a cornerstone in NLP. Whitening has been claimed to be an effective operation to improve embedding quality obtained from Large Language Models (LLMs). However, we find that the efficacy of whitening is model-dependent and task-dependent. In particular, whitening degenerates embeddings for classification tasks. The conclusion is supported by extensive experiments. We also explored a variety of whitening operations, including PCA, ZCA, PCA-Cor, ZCA-Cor and Cholesky whitenings. A by-product of our research is embedding evaluation platform for LLMs called SentEval+.

![在LLM中，分类任务时白化处理并非良策。](../../../paper_images/2407.12886/x1.png)

![在LLM中，分类任务时白化处理并非良策。](../../../paper_images/2407.12886/x2.png)

![在LLM中，分类任务时白化处理并非良策。](../../../paper_images/2407.12886/before-after_W.png)

![在LLM中，分类任务时白化处理并非良策。](../../../paper_images/2407.12886/whitenings.png)

![在LLM中，分类任务时白化处理并非良策。](../../../paper_images/2407.12886/x3.png)

[Arxiv](https://arxiv.org/abs/2407.12886)