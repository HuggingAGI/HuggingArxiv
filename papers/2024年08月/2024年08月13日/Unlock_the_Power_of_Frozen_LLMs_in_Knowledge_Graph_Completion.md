# 释放冻结 LLM 在知识图谱完成中的潜能

发布时间：2024年08月13日

`LLM应用` `知识图谱` `人工智能`

> Unlock the Power of Frozen LLMs in Knowledge Graph Completion

# 摘要

> 传统KGC方法受限于知识图谱的稀疏性，而大型语言模型（LLMs）凭借其强大的上下文建模能力，为解决这一难题提供了新思路。然而，直接微调LLMs成本高昂，而使用冻结模型效果欠佳。本研究巧妙利用LLMs，通过提示激活中间层，捕获三元组的上下文隐藏状态，进而训练高效分类器，充分发挥冻结LLMs在KGC中的潜力。同时，通过子图采样生成实体描述，减少三元组歧义，丰富知识表达。实验表明，我们的方法在效率和效果上均表现出色，不仅超越传统KGC方法，更在GPU内存效率和训练推理速度上取得显著提升。

> Classical knowledge graph completion (KGC) methods rely solely on structural information, struggling with the inherent sparsity of knowledge graphs (KGs). Large Language Models (LLMs) learn extensive knowledge from large corpora with powerful context modeling, which is ideal for mitigating the limitations of previous methods. Directly fine-tuning LLMs offers great capability but comes at the cost of huge time and memory consumption, while utilizing frozen LLMs yields suboptimal results. In this work, we aim to leverage LLMs for KGC effectively and efficiently. We capture the context-aware hidden states of knowledge triples by employing prompts to stimulate the intermediate layers of LLMs. We then train a data-efficient classifier on these hidden states to harness the inherent capabilities of frozen LLMs in KGC. We also generate entity descriptions with subgraph sampling on KGs, reducing the ambiguity of triplets and enriching the knowledge representation. Extensive experiments on standard benchmarks showcase the efficiency and effectiveness of our approach. We outperform classical KGC methods on most datasets and match the performance of fine-tuned LLMs. Additionally, compared to fine-tuned LLMs, we boost GPU memory efficiency by \textbf{$188\times$} and speed up training+inference by \textbf{$13.48\times$}.

[Arxiv](https://arxiv.org/abs/2408.06787)