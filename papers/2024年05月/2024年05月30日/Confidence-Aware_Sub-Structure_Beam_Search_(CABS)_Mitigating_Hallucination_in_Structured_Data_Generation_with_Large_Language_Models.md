# 信心感知子结构束搜索（CABS）：大型语言模型在结构化数据生成中减少幻觉的有效策略

发布时间：2024年05月30日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在生成结构化数据时的置信度评估问题，并提出了一种新的评估方法和解码策略。这些内容直接关联到LLM在实际应用中的性能和可靠性，特别是在处理结构化数据生成任务时。因此，这篇论文属于LLM应用分类。` `数据管理` `人工智能`

> Confidence-Aware Sub-Structure Beam Search (CABS): Mitigating Hallucination in Structured Data Generation with Large Language Models

# 摘要

> 大型语言模型（LLMs）在结构化数据生成方面展现出巨大潜力，广泛应用于表格数据、文档数据库及产品目录等领域。然而，生成的数据真实性因错误引用或幻觉而受到质疑，亟需模型置信度的引入以缓解这一问题。目前，LLMs生成置信度的评估方法多聚焦于单个令牌或整个输出序列，这在处理结构化数据生成时显得力不从心，因为这类数据在子结构级别上包含了独立与相关条目的复杂交织。本文首次探讨了针对生成子结构级别数据的置信度评估方法，并提出了基于LLM变压器隐藏状态的置信度网络，这一方法相较于传统的令牌条件概率提供了更为精准的置信度估计。此外，我们还创新性地提出了置信度感知子结构束搜索（CABS），一种在结构化数据生成中针对子结构级别操作的新型解码策略。CABS通过综合考虑置信度网络提供的每个子结构级别数据的置信度，并迭代优化提示，显著提升了结构化数据生成的可靠性。实验结果表明，在产品属性生成任务中，CABS在90%的精度下，平均召回率较传统令牌级别束搜索提高了16.7%。

> Large Language Models (LLMs) have facilitated structured data generation, with applications in domains like tabular data, document databases, product catalogs, etc. However, concerns persist about generation veracity due to incorrect references or hallucinations, necessitating the incorporation of some form of model confidence for mitigation. Existing confidence estimation methods on LLM generations primarily focus on the confidence at the individual token level or the entire output sequence level, limiting their applicability to structured data generation, which consists of an intricate mix of both independent and correlated entries at the sub-structure level. In this paper, we first investigate confidence estimation methods for generated sub-structure-level data. We introduce the concept of Confidence Network that applies on the hidden state of the LLM transformer, as a more targeted estimate than the traditional token conditional probability. We further propose Confidence-Aware sub-structure Beam Search (CABS), a novel decoding method operating at the sub-structure level in structured data generation. CABS enhances the faithfulness of structured data generation by considering confidence scores from the Confidence Network for each sub-structure-level data and iteratively refining the prompts. Results show that CABS outperforms traditional token-level beam search for structured data generation by 16.7% Recall at 90% precision averagely on the problem of product attribute generation.

![信心感知子结构束搜索（CABS）：大型语言模型在结构化数据生成中减少幻觉的有效策略](../../../paper_images/2406.00069/cabs_fig_1.png)

![信心感知子结构束搜索（CABS）：大型语言模型在结构化数据生成中减少幻觉的有效策略](../../../paper_images/2406.00069/cabs_fig_2.png)

![信心感知子结构束搜索（CABS）：大型语言模型在结构化数据生成中减少幻觉的有效策略](../../../paper_images/2406.00069/cabs_fig_3_2.png)

![信心感知子结构束搜索（CABS）：大型语言模型在结构化数据生成中减少幻觉的有效策略](../../../paper_images/2406.00069/cabs_fig_4_3.png)

![信心感知子结构束搜索（CABS）：大型语言模型在结构化数据生成中减少幻觉的有效策略](../../../paper_images/2406.00069/fig_conf_result.png)

[Arxiv](https://arxiv.org/abs/2406.00069)