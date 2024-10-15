# 大型语言模型能否超越图表，理解超图的奥秘？

发布时间：2024年10月13日

`LLM应用` `人工智能` `数据科学`

> Beyond Graphs: Can Large Language Models Comprehend Hypergraphs?

# 摘要

> 现有的基准测试如 NLGraph 和 GraphQA 主要关注成对关系，忽略了现实数据中的高阶相关性。超图能建模复杂关系，但尚未在 LLM 中充分探索。为此，我们推出了 LLM4Hypergraph，首个综合基准，包含 21,500 个问题，涵盖低阶、高阶及同构任务，利用合成与现实超图。我们评估了六个知名 LLM，包括 GPT-4o，验证了基准的有效性。我们的提示框架结合七种超图语言，并引入 Hyper-BAG 和 Hyper-COT 技术，提升高阶推理，平均性能提升 4%（最高 9%）。这项工作为 LLM 整合超图计算能力奠定了基础，推动了其理解。

> Existing benchmarks like NLGraph and GraphQA evaluate LLMs on graphs by focusing mainly on pairwise relationships, overlooking the high-order correlations found in real-world data. Hypergraphs, which can model complex beyond-pairwise relationships, offer a more robust framework but are still underexplored in the context of LLMs. To address this gap, we introduce LLM4Hypergraph, the first comprehensive benchmark comprising 21,500 problems across eight low-order, five high-order, and two isomorphism tasks, utilizing both synthetic and real-world hypergraphs from citation networks and protein structures. We evaluate six prominent LLMs, including GPT-4o, demonstrating our benchmark's effectiveness in identifying model strengths and weaknesses. Our specialized prompting framework incorporates seven hypergraph languages and introduces two novel techniques, Hyper-BAG and Hyper-COT, which enhance high-order reasoning and achieve an average 4% (up to 9%) performance improvement on structure classification tasks. This work establishes a foundational testbed for integrating hypergraph computational capabilities into LLMs, advancing their comprehension.

[Arxiv](https://arxiv.org/abs/2410.10083)