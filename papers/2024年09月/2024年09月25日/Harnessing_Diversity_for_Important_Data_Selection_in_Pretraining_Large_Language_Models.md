# 借助多样性，精准挑选预训练大型语言模型中的关键数据

发布时间：2024年09月25日

`LLM理论` `人工智能` `数据科学`

> Harnessing Diversity for Important Data Selection in Pretraining Large Language Models

# 摘要

> 在大规模语言模型预训练中，数据选择至关重要，因为训练语料库的质量参差不齐。研究人员正探索利用数据影响来衡量数据实例的重要性，高影响分数意味着将该实例纳入训练集可能提升模型性能。然而，这种方法存在两大局限：一是计算所有数据的影响耗时，二是所选数据不够多样化，可能影响模型对下游任务的泛化能力。为此，我们提出了\texttt{Quad}数据选择方法，通过结合数据影响和多样性，实现最先进的预训练效果。我们特别改进了注意力层的$iHVP$计算方法，以更准确评估数据质量。同时，\texttt{Quad}通过聚类确保数据多样性，并采用多臂赌博机方法，动态选择高质量或较少被选中的聚类，从而在质量和多样性之间取得平衡。

> Data selection is of great significance in pre-training large language models, given the variation in quality within the large-scale available training corpora. To achieve this, researchers are currently investigating the use of data influence to measure the importance of data instances, $i.e.,$ a high influence score indicates that incorporating this instance to the training set is likely to enhance the model performance. Consequently, they select the top-$k$ instances with the highest scores. However, this approach has several limitations. (1) Computing the influence of all available data is time-consuming. (2) The selected data instances are not diverse enough, which may hinder the pre-trained model's ability to generalize effectively to various downstream tasks. In this paper, we introduce \texttt{Quad}, a data selection approach that considers both quality and diversity by using data influence to achieve state-of-the-art pre-training results. In particular, noting that attention layers capture extensive semantic details, we have adapted the accelerated $iHVP$ computation methods for attention layers, enhancing our ability to evaluate the influence of data, $i.e.,$ its quality. For the diversity, \texttt{Quad} clusters the dataset into similar data instances within each cluster and diverse instances across different clusters. For each cluster, if we opt to select data from it, we take some samples to evaluate the influence to prevent processing all instances. To determine which clusters to select, we utilize the classic Multi-Armed Bandit method, treating each cluster as an arm. This approach favors clusters with highly influential instances (ensuring high quality) or clusters that have been selected less frequently (ensuring diversity), thereby well balancing between quality and diversity.

[Arxiv](https://arxiv.org/abs/2409.16986)