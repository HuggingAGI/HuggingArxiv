# MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展

发布时间：2024年06月25日

`LLM应用

这篇论文主要讨论了大型语言模型（LLMs）在医疗领域的应用，特别是如何通过渐进式微调策略来提高模型在医疗任务上的性能。论文提出了一种新的方法，即通过知识聚合器和噪声聚合器来整合和筛选知识，并引入对齐模块以防止知识遗忘。这种方法被应用于开发MedCare，一种专门针对医疗任务优化的LLM。因此，这篇论文属于LLM应用类别，因为它专注于将LLM技术应用于特定的医疗领域，并提出了改进模型性能的具体方法。` `人工智能`

> MedCare: Advancing Medical LLMs through Decoupling Clinical Alignment and Knowledge Aggregation

# 摘要

> 大型语言模型（LLMs）在医疗领域的自然语言理解和生成方面取得了显著进展。然而，医疗任务的复杂性和多样性带来了挑战，这些任务分为知识密集型和需要对齐的两类。传统方法往往忽视了对齐任务或仅关注少数任务，导致泛化能力不足。为此，我们提出了一种渐进式微调策略，首先通过知识聚合器和噪声聚合器整合并筛选知识，随后移除噪声聚合器，引入对齐模块以防止知识遗忘。基于此，我们开发了MedCare，一种解耦临床对齐与知识聚合的医疗LLM，旨在在20多个医疗任务上达到顶尖性能，并在特定对齐任务上取得优异成果。MedCare的多种模型规模（1.8B, 7B, 14B）均显著优于同规模现有模型。

> Large language models (LLMs) have shown substantial progress in natural language understanding and generation, proving valuable especially in the medical field. Despite advancements, challenges persist due to the complexity and diversity inherent in medical tasks, which can be categorized as knowledge-intensive tasks and alignment-required tasks. Previous approaches either ignore the latter task or focus on a minority of tasks and hence lose generalization. To address these drawbacks, we propose a progressive fine-tuning pipeline. This pipeline employs a Knowledge Aggregator and a Noise aggregator to encode diverse knowledge in the first stage and filter out detrimental information. In the second stage, we drop the Noise Aggregator to avoid the interference of suboptimal representation and leverage an additional alignment module optimized towards an orthogonal direction to the knowledge space to mitigate knowledge forgetting. Based on this two-stage paradigm, we proposed a Medical LLM through decoupling Clinical Alignment and Knowledge Aggregation (MedCare), which is designed to achieve state-of-the-art (SOTA) performance on over 20 medical tasks, as well as SOTA results on specific medical alignment tasks. Various model sizes of MedCare (1.8B, 7B, 14B) all demonstrate significant improvements over existing models with similar model sizes.

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x1.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x2.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x3.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x4.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x5.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x6.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x7.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x8.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x9.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x10.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x11.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x12.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x13.png)

![MedCare：通过分离临床对齐与知识聚合，推动医学大型语言模型的发展](../../../paper_images/2406.17484/x14.png)

[Arxiv](https://arxiv.org/abs/2406.17484)