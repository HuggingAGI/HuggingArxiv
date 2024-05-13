# 语言模型中低秩分解的精效平衡探析

发布时间：2024年05月10日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）的内存优化问题，特别是通过秩剪枝和Tucker分解等模型压缩技术来减少模型大小，同时研究了准确性和效率之间的权衡。这些研究内容属于对LLMs理论层面的优化和改进，因此归类为LLM理论。虽然论文中提到了这些优化技术在实际应用中的潜在用途，如AI辅助代理和实时编码助手，但核心内容仍然是关于LLMs的理论优化方法，而不是具体的应用案例或Agent的设计。` `人工智能` `模型优化`

> Characterizing the Accuracy - Efficiency Trade-off of Low-rank Decomposition in Language Models

# 摘要

> 大型语言模型（LLMs）以其单一模型解决问题的能力崭露头角，但这也伴随着模型规模的激增，参数数量达到数十亿。由于LLMs中矩阵运算的主导地位，其计算效率远不如CNNs，导致LLMs从计算密集型转向内存密集型。因此，优化内存使用和数据流量成为LLMs优化的关键。模型压缩技术，如量化和参数剪枝，已被广泛研究以优化LLMs的内存占用。然而，对于LLMs的秩剪枝在准确性和效率之间的权衡仍不明确。我们针对Tucker分解这一低秩分解技术，在包括开源模型Llama 2在内的最新语言模型上进行了研究。我们定义了低秩分解的设计空间，并发现其空间巨大（例如，对于Llama2-7B，可达O($2^{37}$)）。为了探索这一广阔空间，我们制定了设计策略，并在BERT和Llama 2模型上基于六个LLM基准进行了深入的准确性-效率权衡研究。结果显示，我们可以在不显著牺牲准确性的情况下，将模型大小减少9%，准确性下降幅度在4%p至10%p之间，具体取决于基准的难度，且无需重新训练以恢复准确性。这表明，低秩分解对于需要大规模实时服务的LLM应用（如AI辅助代理和实时编码助手）是一个有前景的方向，其中延迟与模型准确性同等重要。

> Large language models (LLMs) have emerged and presented their general problem-solving capabilities with one model. However, the model size has increased dramatically with billions of parameters to enable such broad problem-solving capabilities. In addition, due to the dominance of matrix-matrix and matrix-vector multiplications in LLMs, the compute-to-model size ratio is significantly lower than that of CNNs. This shift pushes LLMs from a computation-bound regime to a memory-bound regime. Therefore, optimizing the memory footprint and traffic is an important optimization direction for LLMs today.
  Model compression methods such as quantization and parameter pruning have been actively explored for achieving the memory footprint and traffic optimization. However, the accuracy-efficiency trade-off of rank pruning for LLMs is not well-understood yet. Therefore, we characterize the accuracy-efficiency trade-off of a low-rank decomposition method, specifically Tucker decomposition, on recent language models, including an open-source LLM, Llama 2.
  We formalize the low-rank decomposition design space and show that the decomposition design space is enormous (e.g., O($2^{37}$) for Llama2-7B). To navigate such a vast design space, we formulate the design space and perform thorough case studies of accuracy-efficiency trade-offs using six widely used LLM benchmarks on BERT and Llama 2 models. Our results show that we can achieve a 9\% model size reduction with minimal accuracy drops, which range from 4\%p to 10\%p, depending on the difficulty of the benchmark, without any retraining to recover accuracy after decomposition. The results show that low-rank decomposition can be a promising direction for LLM-based applications that require real-time service in scale (e.g., AI agent assist and real-time coding assistant), where the latency is as important as the model accuracy.

[Arxiv](https://arxiv.org/abs/2405.06626)