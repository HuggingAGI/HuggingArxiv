# 借助大型语言模型代理，我们能够生成资产管理壳，实现数字孪生中带有语义节点的无缝互操作性。

发布时间：2024年03月25日

`LLM应用` `工业4.0` `数字孪生`

> Generation of Asset Administration Shell with Large Language Model Agents: Interoperability in Digital Twins with Semantic Node

# 摘要

> 本研究创新性地提出了一种辅助方法，用于在工业4.0环境下为数字孪生建模打造资产行政壳（AAS）实例，以提升智能制造业的互操作性并减轻人工负担。通过构建“语义节点”这一数据结构，我们成功捕捉了文本数据的深层语义。接着，我们设计并实施了一个由大型语言模型支持的系统，它能够处理这些“语义节点”，并基于技术文本数据生成AAS实例模型。评估结果显示，有效生成率介于62%至79%之间，这意味着大部分原本需要手动完成的工作现在可以转化为相对简单的验证过程，大大节约了创建AAS实例模型的时间和精力。在评估过程中，我们对不同的LLMs进行了对比分析，并对检索增强生成（RAG）机制进行了深入研究，这有助于我们理解LLM系统在解读技术概念方面的有效性。研究结果凸显了LLMs在自动化AAS实例生成、提升语义互操作性方面的强大能力，并为数字孪生在工业应用中的语义互操作性领域做出了贡献。相关的原型实现和评估成果已在我们的GitHub仓库上线，链接如下：https://github.com/YuchenXia/AASbyLLM

> This research introduces a novel approach for assisting the creation of Asset Administration Shell (AAS) instances for digital twin modeling within the context of Industry 4.0, aiming to enhance interoperability in smart manufacturing and reduce manual effort. We construct a "semantic node" data structure to capture the semantic essence of textual data. Then, a system powered by large language models is designed and implemented to process "semantic node" and generate AAS instance models from textual technical data. Our evaluation demonstrates a 62-79% effective generation rate, indicating a substantial proportion of manual creation effort can be converted into easier validation effort, thereby reducing the time and cost in creating AAS instance models. In our evaluation, a comparative analysis of different LLMs and an in-depth ablation study of Retrieval-Augmented Generation (RAG) mechanisms provide insights into the effectiveness of LLM systems for interpreting technical concepts. Our findings emphasize LLMs' capability in automating AAS instance creation, enhancing semantic interoperability, and contributing to the broader field of semantic interoperability for digital twins in industrial applications. The prototype implementation and evaluation results are released on our GitHub Repository with the link: https://github.com/YuchenXia/AASbyLLM

[Arxiv](https://arxiv.org/abs/2403.17209)