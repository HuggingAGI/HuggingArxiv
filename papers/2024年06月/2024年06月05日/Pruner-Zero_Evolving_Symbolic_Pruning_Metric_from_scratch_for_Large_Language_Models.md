# Pruner-Zero：为大型语言模型量身定制，从零开始演化符号剪枝指标

发布时间：2024年06月05日

`LLM应用

这篇论文主要讨论了大型语言模型（LLMs）的剪枝技术，特别是开发了一个自动化框架来探索和创造新的剪枝度量标准，以提高模型的效率和性能。这种方法直接应用于现有的LLMs，如LLaMA和LLaMA-2，以改进它们的部署和运行效率。因此，这项工作属于LLM应用类别，因为它关注的是如何实际应用技术来优化现有的LLM模型。` `人工智能` `机器学习`

> Pruner-Zero: Evolving Symbolic Pruning Metric from scratch for Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）功能强大，但其庞大的体积却给部署带来了难题。剪枝技术通过剔除部分权重来提速，但多数方法需重新训练，成本高昂且计算密集。近期，无需重新训练的后训练剪枝技术崭露头角，但仍需依赖专家的介入和反复试验。为此，我们开发了一个自动化框架，运用遗传编程来探索符号化的剪枝度量标准。我们精心设计了一个搜索空间，旨在挖掘新的剪枝度量标准，并提出了对立操作简化策略以增强种群多样性。Pruner-Zero因此能够自动创造剪枝度量标准。通过分析，我们揭示了剪枝度量与性能之间的关系，并归纳了一些规律。在LLaMA和LLaMA-2上进行的广泛实验证明，Pruner-Zero在性能上超越了现有的后训练剪枝技术。代码已公开：\url{https://github.com/pprp/Pruner-Zero}。

> Despite the remarkable capabilities, Large Language Models (LLMs) face deployment challenges due to their extensive size. Pruning methods drop a subset of weights to accelerate, but many of them require retraining, which is prohibitively expensive and computationally demanding. Recently, post-training pruning approaches introduced novel metrics, enabling the pruning of LLMs without retraining. However, these metrics require the involvement of human experts and tedious trial and error. To efficiently identify superior pruning metrics, we develop an automatic framework for searching symbolic pruning metrics using genetic programming. In particular, we devise an elaborate search space encompassing the existing pruning metrics to discover the potential symbolic pruning metric. We propose an opposing operation simplification strategy to increase the diversity of the population. In this way, Pruner-Zero allows auto-generation of symbolic pruning metrics. Based on the searched results, we explore the correlation between pruning metrics and performance after pruning and summarize some principles. Extensive experiments on LLaMA and LLaMA-2 on language modeling and zero-shot tasks demonstrate that our Pruner-Zero obtains superior performance than SOTA post-training pruning methods. Code at: \url{https://github.com/pprp/Pruner-Zero}.

![Pruner-Zero：为大型语言模型量身定制，从零开始演化符号剪枝指标](../../../paper_images/2406.02924/main_figure.png)

![Pruner-Zero：为大型语言模型量身定制，从零开始演化符号剪枝指标](../../../paper_images/2406.02924/evolution_search.png)

![Pruner-Zero：为大型语言模型量身定制，从零开始演化符号剪枝指标](../../../paper_images/2406.02924/random_search.png)

![Pruner-Zero：为大型语言模型量身定制，从零开始演化符号剪枝指标](../../../paper_images/2406.02924/line_plot.png)

![Pruner-Zero：为大型语言模型量身定制，从零开始演化符号剪枝指标](../../../paper_images/2406.02924/calibration_samples.png)

![Pruner-Zero：为大型语言模型量身定制，从零开始演化符号剪枝指标](../../../paper_images/2406.02924/correlation.png)

[Arxiv](https://arxiv.org/abs/2406.02924)