# PEDAL：借助多样化示例，提升大型语言模型的贪婪解码效率

发布时间：2024年08月16日

`LLM应用` `人工智能`

> PEDAL: Enhancing Greedy Decoding with Large Language Models using Diverse Exemplars

# 摘要

> 自集成技术如Self-Consistency通过多样的推理路径显著提升了大语言模型（LLM）的准确性，但依赖于精确的答案提取来汇总多重输出，且推理成本较高。研究显示，Self-Consistency的自由文本输出可由LLM可靠地整合为最终结果。最新进展表明，多样化的提示示例能增加LLM输出的多样性。本文提出的PEDAL方法，融合了多样化示例提示与LLM聚合的优势，有效提升了性能。实验证明，PEDAL在SVAMP和ARC数据集上，以低于Self Consistency的成本，实现了超越贪婪解码策略的准确性。

> Self-ensembling techniques with diverse reasoning paths such as Self-Consistency have demonstrated remarkable gains in accuracy for Large Language Models (LLMs). However, such techniques depend on the availability of an accurate answer extraction process to aggregate across multiple outputs. Moreover, they acquire higher inference cost, in comparison to Greedy Decoding, due to generation of relatively higher number of output tokens. Research has shown that the free form text outputs from Self-Consistency can be aggregated reliably using LLMs to produce the final output. Additionally, recent advancements in LLM inference have demonstrated that usage of diverse exemplars in prompts have the ability to induce diversity in the LLM outputs. Such proven techniques can be easily extended to self-ensembling based approaches to achieve enhanced results in text generation. In this paper, we introduce PEDAL (Prompts based on Exemplar Diversity Aggregated using LLMs), a hybrid self-ensembling approach, that combines the strengths of diverse exemplar based prompts and LLM based aggregation to achieve improvement in overall performance. On the publicly available SVAMP and ARC datasets, our experiments reveal that PEDAL can achieve better accuracy than Greedy Decoding based strategies with lower inference cost compared to Self Consistency based approaches.

![PEDAL：借助多样化示例，提升大型语言模型的贪婪解码效率](../../../paper_images/2408.08869/x1.png)

[Arxiv](https://arxiv.org/abs/2408.08869)