# Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据

发布时间：2024年06月04日

`LLM理论

理由：这篇论文主要介绍了Zyda数据集的创建和其在提升大型语言模型（LLMs）性能方面的应用。虽然数据集的创建和使用可以被视为一种应用，但论文的核心贡献在于数据集的构建方法和对其性能的评估，这更多地涉及到了LLM的理论层面，特别是在数据处理和模型训练方面。因此，将其归类为LLM理论更为合适。` `数据集`

> Zyda: A 1.3T Dataset for Open Language Modeling

# 摘要

> 近年来，大型语言模型（LLMs）的规模急剧增长，其计算和数据需求也随之大幅上升。即使是规模较小的最先进语言模型，也通常需要在至少一万亿个令牌上进行训练。这一快速发展已经超过了可用于大规模LLM预训练的开源数据集的增长。本文中，我们推出了Zyda（Zyphra数据集），这是一个包含1.3万亿个令牌的高质量数据集，通过整合多个知名开源数据集而成，并采用了宽松的许可证。我们通过严格的过滤和去重过程，确保了数据集的质量，并提升了原始数据集的性能。评估结果表明，Zyda不仅与Dolma、FineWeb和RefinedWeb等其他开源数据集相比表现出色，还显著提升了Pythia套件中类似模型的性能。我们的严格数据处理显著提升了Zyda的效能，使其在独立使用时甚至超越了其组成数据集中的最佳性能。

> The size of large language models (LLMs) has scaled dramatically in recent years and their computational and data requirements have surged correspondingly. State-of-the-art language models, even at relatively smaller sizes, typically require training on at least a trillion tokens. This rapid advancement has eclipsed the growth of open-source datasets available for large-scale LLM pretraining. In this paper, we introduce Zyda (Zyphra Dataset), a dataset under a permissive license comprising 1.3 trillion tokens, assembled by integrating several major respected open-source datasets into a single, high-quality corpus. We apply rigorous filtering and deduplication processes, both within and across datasets, to maintain and enhance the quality derived from the original datasets. Our evaluations show that Zyda not only competes favorably with other open datasets like Dolma, FineWeb, and RefinedWeb, but also substantially improves the performance of comparable models from the Pythia suite. Our rigorous data processing methods significantly enhance Zyda's effectiveness, outperforming even the best of its constituent datasets when used independently.

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/pie_zyda.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/lsh_0_4_dist_ES.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/lsh_0.4_dist_JS.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/scores_across_time_smoothed.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/zyda-vs-pile-across-scale.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/zyda-vs-pile-across-evals.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_plots_acc_norm_v2.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/deduplication_threshold_ablations.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Arc_Challenge.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Arc_Easy.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Boolq.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Hellaswag.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Openbookqa.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Piqa.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Sciq.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/ablations_evals_Winogrande.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/x1.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/lsh_0.4_dupes_len_dist_words.png)

![Zyda：开放语言建模的巨型数据集，容量高达1.3万亿条数据](../../../paper_images/2406.01981/lsh_0.4_FP_vs_words.png)

[Arxiv](https://arxiv.org/abs/2406.01981)