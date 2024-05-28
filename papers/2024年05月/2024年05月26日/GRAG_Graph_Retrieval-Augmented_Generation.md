# GRAG：图检索赋能生成

发布时间：2024年05月26日

`RAG

该论文摘要描述了一种名为图检索增强生成（GRAG）的新方法，该方法专注于改进检索增强生成（RAG）在处理文本与拓扑信息并重的图场景中的表现。GRAG通过重视子图结构来提升检索与生成的效率，这与传统的RAG方法不同，后者忽视了文本图的结构细节。GRAG的流程包括特定的阶段，如$k$-跳自我图索引、图检索、软修剪以及利用修剪后的文本子图进行生成。这种方法的核心在于检索后的软修剪，以及一种创新的提示策略，用于将文本子图转换为分层文本描述。论文中提到的GRAG在多跳推理基准测试中的表现超越了现有技术，特别是在需要复杂推理的文本图场景中。因此，根据论文内容，它应被分类为RAG。` `图数据处理`

> GRAG: Graph Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）虽提升了生成语言模型的响应准确性和相关性，但在文本与拓扑信息并重的图场景中表现欠佳。传统的RAG方法忽视了文本图的结构细节，导致生成过程中的关键缺失。为此，我们提出了图检索增强生成（GRAG），它通过重视子图结构，大幅提升了检索与生成的效率。与仅关注文本实体的RAG不同，GRAG对图的拓扑结构保持敏感，这对于生成连贯的上下文和事实至关重要。GRAG流程包括四个阶段：$k$-跳自我图索引、图检索、软修剪以排除无关实体，以及利用修剪后的文本子图进行生成。其核心在于检索后进行软修剪，有效识别相关子图，避免了NP难问题的计算负担。我们还创新了一种提示策略，实现了文本子图到分层文本描述的无损转换。在多跳推理基准测试中，GRAG在需要复杂推理的文本图场景中显著超越了现有技术，同时有效减少了幻觉现象。

> While Retrieval-Augmented Generation (RAG) enhances the accuracy and relevance of responses by generative language models, it falls short in graph-based contexts where both textual and topological information are important. Naive RAG approaches inherently neglect the structural intricacies of textual graphs, resulting in a critical gap in the generation process. To address this challenge, we introduce $\textbf{Graph Retrieval-Augmented Generation (GRAG)}$, which significantly enhances both the retrieval and generation processes by emphasizing the importance of subgraph structures. Unlike RAG approaches that focus solely on text-based entity retrieval, GRAG maintains an acute awareness of graph topology, which is crucial for generating contextually and factually coherent responses. Our GRAG approach consists of four main stages: indexing of $k$-hop ego-graphs, graph retrieval, soft pruning to mitigate the impact of irrelevant entities, and generation with pruned textual subgraphs. GRAG's core workflow-retrieving textual subgraphs followed by soft pruning-efficiently identifies relevant subgraph structures while avoiding the computational infeasibility typical of exhaustive subgraph searches, which are NP-hard. Moreover, we propose a novel prompting strategy that achieves lossless conversion from textual subgraphs to hierarchical text descriptions. Extensive experiments on graph multi-hop reasoning benchmarks demonstrate that in scenarios requiring multi-hop reasoning on textual graphs, our GRAG approach significantly outperforms current state-of-the-art RAG methods while effectively mitigating hallucinations.

![GRAG：图检索赋能生成](../../../paper_images/2405.16506/intro_3.png)

![GRAG：图检索赋能生成](../../../paper_images/2405.16506/flow_4.png)

![GRAG：图检索赋能生成](../../../paper_images/2405.16506/subgraph.png)

![GRAG：图检索赋能生成](../../../paper_images/2405.16506/webqsp.png)

[Arxiv](https://arxiv.org/abs/2405.16506)