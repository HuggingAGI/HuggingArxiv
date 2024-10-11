# 知识图谱能否提升大型语言模型的可信度？本研究通过开放式问答任务进行了实证探索。

发布时间：2024年10月10日

`LLM应用` `人工智能` `知识图谱`

> Can Knowledge Graphs Make Large Language Models More Trustworthy? An Empirical Study over Open-ended Question Answering

# 摘要

> 最近，将知识图谱 (KGs) 融入大型语言模型 (LLMs) 的研究显示了提升推理准确性的潜力。然而，现有基准主要针对封闭任务，忽略了更复杂、现实场景的评估，也未充分考察 KGs 减少 LLMs 幻觉的能力。为此，我们推出了 OKGQA，一个专为开放式、现实问答场景设计的基准，旨在通过多样问题反映实际应用的复杂性，并量化幻觉减少与推理增强。此外，针对 KGs 可能存在的错误，我们设计了 OKGQA-P 实验，模拟 KGs 语义和结构的扰动。OKGQA 的目标是：(1) 验证 KGs 在开放环境中提升 LLMs 可信度的效果；(2) 通过比较分析，探索利用 KGs 减少 LLMs 幻觉的未来方向。我们期待这项研究能推动更全面的性能评估，并促进 KGs 与 LLMs 整合的不断进步。

> Recent works integrating Knowledge Graphs (KGs) have led to promising improvements in enhancing reasoning accuracy of Large Language Models (LLMs). However, current benchmarks mainly focus on closed tasks, leaving a gap in the assessment of more complex, real-world scenarios. This gap has also obscured the evaluation of KGs' potential to mitigate the problem of hallucination in LLMs. To fill the gap, we introduce OKGQA, a new benchmark specifically designed to assess LLMs enhanced with KGs under open-ended, real-world question answering scenarios. OKGQA is designed to closely reflect the complexities of practical applications using questions from different types, and incorporates specific metrics to measure both the reduction in hallucinations and the enhancement in reasoning capabilities. To consider the scenario in which KGs may have varying levels of mistakes, we further propose another experiment setting OKGQA-P to assess model performance when the semantics and structure of KGs are deliberately perturbed and contaminated. OKGQA aims to (1) explore whether KGs can make LLMs more trustworthy in an open-ended setting, and (2) conduct a comparative analysis to shed light on methods and future directions for leveraging KGs to reduce LLMs' hallucination. We believe that this study can facilitate a more complete performance comparison and encourage continuous improvement in integrating KGs with LLMs.

[Arxiv](https://arxiv.org/abs/2410.08085)