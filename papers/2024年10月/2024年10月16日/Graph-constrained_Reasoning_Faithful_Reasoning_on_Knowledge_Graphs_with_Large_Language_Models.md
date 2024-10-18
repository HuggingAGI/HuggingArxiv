# 图约束推理：利用大型语言模型在知识图谱上实现可信推理

发布时间：2024年10月16日

`LLM应用` `人工智能` `知识图谱`

> Graph-constrained Reasoning: Faithful Reasoning on Knowledge Graphs with Large Language Models

# 摘要

> 尽管大型语言模型 (LLM) 展示了卓越的推理能力，但由于知识缺口和幻觉问题，它们在忠实推理上仍显不足。为此，知识图谱 (KG) 被引入，以结构化知识增强 LLM 的推理能力。然而，现有的 KG 增强方法在知识检索和大规模 KG 遍历方面存在局限。我们提出了图约束推理 (GCR)，一种结合 KG 结构化知识与 LLM 非结构化推理的新框架。通过 KG-Trie，GCR 将 KG 结构融入 LLM 解码过程，确保推理的忠实性。KG-Trie 限制解码过程，使 LLM 能在图上直接推理，生成基于 KG 的忠实路径。此外，GCR 结合轻量级 KG 专用 LLM 和强大通用 LLM，实现零幻觉的准确推理。实验证明，GCR 在 KGQA 基准上表现卓越，且具备强大的零样本泛化能力，无需额外训练即可适应未见过的 KG。

> Large language models (LLMs) have demonstrated impressive reasoning abilities, but they still struggle with faithful reasoning due to knowledge gaps and hallucinations. To address these issues, knowledge graphs (KGs) have been utilized to enhance LLM reasoning through their structured knowledge. However, existing KG-enhanced methods, either retrieval-based or agent-based, encounter difficulties in accurately retrieving knowledge and efficiently traversing KGs at scale. In this work, we introduce graph-constrained reasoning (GCR), a novel framework that bridges structured knowledge in KGs with unstructured reasoning in LLMs. To eliminate hallucinations, GCR ensures faithful KG-grounded reasoning by integrating KG structure into the LLM decoding process through KG-Trie, a trie-based index that encodes KG reasoning paths. KG-Trie constrains the decoding process, allowing LLMs to directly reason on graphs and generate faithful reasoning paths grounded in KGs. Additionally, GCR leverages a lightweight KG-specialized LLM for graph-constrained reasoning alongside a powerful general LLM for inductive reasoning over multiple reasoning paths, resulting in accurate reasoning with zero reasoning hallucination. Extensive experiments on several KGQA benchmarks demonstrate that GCR achieves state-of-the-art performance and exhibits strong zero-shot generalizability to unseen KGs without additional training.

[Arxiv](https://arxiv.org/abs/2410.13080)