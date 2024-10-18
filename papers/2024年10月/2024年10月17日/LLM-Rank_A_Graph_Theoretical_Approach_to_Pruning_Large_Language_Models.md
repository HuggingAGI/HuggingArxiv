# LLM-Rank：利用图论技术优化大语言模型剪枝的新思路

发布时间：2024年10月17日

`LLM理论` `人工智能` `计算机科学`

> LLM-Rank: A Graph Theoretical Approach to Pruning Large Language Models

# 摘要

> 随着大型语言模型能力的不断提升，其规模和部署成本也在增加，因此需要高效的推理优化技术。我们提出了一种创新的剪枝方法，利用图论中的中心性度量，有效减少了模型的计算需求和内存占用。具体而言，我们设计了一种加权有向无环图表示多层感知器的方法，并应用改进的加权PageRank算法来计算节点重要性。结合均匀剪枝，这种方法实现了结构化稀疏性，我们称之为MLPRank。此外，我们还为仅解码器变压器模型引入了LLMRank。实验结果显示，MLPRank和LLMRank均表现出色，分别比基线方法提高了6.09%和13.42%的准确性保留率。

> The evolving capabilities of large language models are accompanied by growing sizes and deployment costs, necessitating effective inference optimisation techniques. We propose a novel pruning method utilising centrality measures from graph theory, reducing both the computational requirements and the memory footprint of these models. Specifically, we devise a method for creating a weighted directed acyclical graph representation of multilayer perceptrons to which we apply a modified version of the weighted PageRank centrality measure to compute node importance scores. In combination with uniform pruning this leads to structured sparsity. We call this pruning method MLPRank. Furthermore we introduce an extension to decoder-only transformer models and call it LLMRank. For both variants we demonstrate a strong performance. With MLPRank on average leading to 6.09 % higher accuracy retention than three popular baselines and 13.42 % with LLMRank compared to two popular baselines.

[Arxiv](https://arxiv.org/abs/2410.13299)