# 借助大型语言模型，我们合成了一个无本体的通用领域知识图谱到文本生成数据集。

发布时间：2024年09月11日

`LLM应用` `知识图谱`

> Ontology-Free General-Domain Knowledge Graph-to-Text Generation Dataset Synthesis using Large Language Model

# 摘要

> 知识图谱到文本 (G2T) 生成旨在将结构化知识图谱转化为自然语言文本。尽管预训练语言模型 (PLM) 的进步提升了 G2T 性能，但其效果依赖于精确的图-文本对齐数据集。然而，高质量通用领域 G2T 数据集的稀缺阻碍了该领域的进展。为此，我们推出了 Wikipedia 无本体图-文本数据集 (WikiOFGraph)，利用大型语言模型 (LLM) 和 Data-QuestEval 生成，包含 585 万对图-文本数据，无需外部本体即可实现高一致性。实验显示，基于 WikiOFGraph 微调的 PLM 在各项评估中均优于其他数据集训练的模型。这一创新方法不仅高效且可扩展，为 G2T 生成领域带来了显著进步。

> Knowledge Graph-to-Text (G2T) generation involves verbalizing structured knowledge graphs into natural language text. Recent advancements in Pretrained Language Models (PLMs) have improved G2T performance, but their effectiveness depends on datasets with precise graph-text alignment. However, the scarcity of high-quality, general-domain G2T generation datasets restricts progress in the general-domain G2T generation research. To address this issue, we introduce Wikipedia Ontology-Free Graph-text dataset (WikiOFGraph), a new large-scale G2T dataset generated using a novel method that leverages Large Language Model (LLM) and Data-QuestEval. Our new dataset, which contains 5.85M general-domain graph-text pairs, offers high graph-text consistency without relying on external ontologies. Experimental results demonstrate that PLM fine-tuned on WikiOFGraph outperforms those trained on other datasets across various evaluation metrics. Our method proves to be a scalable and effective solution for generating high-quality G2T data, significantly advancing the field of G2T generation.

[Arxiv](https://arxiv.org/abs/2409.07088)