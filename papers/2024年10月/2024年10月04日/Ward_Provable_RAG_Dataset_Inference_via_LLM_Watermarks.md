# Ward：利用 LLM 水印技术，实现 RAG 数据集的可靠推断

发布时间：2024年10月04日

`RAG` `数据隐私` `人工智能`

> Ward: Provable RAG Dataset Inference via LLM Watermarks

# 摘要

> RAG 通过整合外部数据提升 LLM 性能，但也引发了数据所有者对其内容未经授权使用的担忧。尽管重要，检测这种使用的方法仍未充分探索。为此，我们首先将问题定义为 RAG 数据集推断 (RAG-DI)，并引入了一个新数据集和基线方法。基于此，我们提出了 Ward，一种基于 LLM 水印的 RAG-DI 方法，为数据所有者提供严格的统计保证。实验表明，Ward 在多种挑战性场景中表现优异，为未来研究奠定了基础，并展示了 LLM 水印的潜力。

> Retrieval-Augmented Generation (RAG) improves LLMs by enabling them to incorporate external data during generation. This raises concerns for data owners regarding unauthorized use of their content in RAG systems. Despite its importance, the challenge of detecting such unauthorized usage remains underexplored, with existing datasets and methodologies from adjacent fields being ill-suited for its study. In this work, we take several steps to bridge this gap. First, we formalize this problem as (black-box) RAG Dataset Inference (RAG-DI). To facilitate research on this challenge, we further introduce a novel dataset specifically designed for benchmarking RAG-DI methods under realistic conditions, and propose a set of baseline approaches. Building on this foundation, we introduce Ward, a RAG-DI method based on LLM watermarks that enables data owners to obtain rigorous statistical guarantees regarding the usage of their dataset in a RAG system. In our experimental evaluation, we show that Ward consistently outperforms all baselines across many challenging settings, achieving higher accuracy, superior query efficiency and robustness. Our work provides a foundation for future studies of RAG-DI and highlights LLM watermarks as a promising approach to this problem.

[Arxiv](https://arxiv.org/abs/2410.03537)