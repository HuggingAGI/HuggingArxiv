# 用自然语言整理无序的图像集

发布时间：2024年10月07日

`LLM应用` `计算机视觉` `社交媒体分析`

> Organizing Unstructured Image Collections using Natural Language

# 摘要

> 将非结构化视觉数据转化为语义簇是计算机视觉的核心难题。传统深度聚类方法局限于单一划分，而多重聚类方法则通过揭示不同聚类方案来突破这一局限。随着大型语言模型（LLM）和多模态LLM（MLLM）的崛起，用户现在能用自然语言定义聚类标准，进一步提升了多重聚类的能力。然而，手动为庞大数据集设定标准显然不切实际。为此，我们提出了语义多重聚类（SMC）任务，旨在自动从海量图像中发掘聚类标准，揭示出无需人工干预的可解释子结构。我们的文本驱动语义多重聚类框架（TeDeSC）利用文本作为桥梁，同时处理大量图像，自动生成自然语言描述的分区标准，并揭示深层次的语义结构。为验证TeDeSC的效能，我们创建了COCO-4c和Food-4c基准测试，每个基准包含四个分组标准及其实际标注。通过在发现偏见、分析社交媒体图像热度等应用中的实践，TeDeSC展现了其作为自动整理图像集合并带来新颖洞察的强大工具潜力。

> Organizing unstructured visual data into semantic clusters is a key challenge in computer vision. Traditional deep clustering (DC) approaches focus on a single partition of data, while multiple clustering (MC) methods address this limitation by uncovering distinct clustering solutions. The rise of large language models (LLMs) and multimodal LLMs (MLLMs) has enhanced MC by allowing users to define clustering criteria in natural language. However, manually specifying criteria for large datasets is impractical. In this work, we introduce the task Semantic Multiple Clustering (SMC) that aims to automatically discover clustering criteria from large image collections, uncovering interpretable substructures without requiring human input. Our framework, Text Driven Semantic Multiple Clustering (TeDeSC), uses text as a proxy to concurrently reason over large image collections, discover partitioning criteria, expressed in natural language, and reveal semantic substructures. To evaluate TeDeSC, we introduce the COCO-4c and Food-4c benchmarks, each containing four grouping criteria and ground-truth annotations. We apply TeDeSC to various applications, such as discovering biases and analyzing social media image popularity, demonstrating its utility as a tool for automatically organizing image collections and revealing novel insights.

[Arxiv](https://arxiv.org/abs/2410.05217)