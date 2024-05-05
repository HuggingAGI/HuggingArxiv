# 通过大型语言模型代理打造资产管理壳，实现数字孪生体中的语义节点互操作性。

发布时间：2024年03月25日

`分类：LLM应用` `工业自动化` `智能制造`

> Generation of Asset Administration Shell with Large Language Model Agents: Interoperability in Digital Twins with Semantic Node

# 摘要

> 本研究提出了一种创新方法，辅助在工业4.0环境下创建数字孪生模型的资产行政壳（AAS）实例，目标是提升智能制造业的互操作性并降低人工操作的负担。我们设计了一种“语义节点”数据结构，用以捕捉文本数据的深层语义。基于此，开发了一个由大型语言模型支持的系统，它能够处理这些“语义节点”，并从技术文本数据中生成AAS实例模型。我们的评估结果表明，该系统的有效生成率高达62-79%，这意味着可以将大量手动创建工作转化为更简便的验证工作，从而显著降低创建AAS实例模型的时间和成本。在评估过程中，我们对多种大型语言模型进行了比较分析，并对检索增强生成（RAG）机制进行了深入的消融研究，这些研究揭示了LLM系统在理解技术概念方面的高效性。我们的研究结果突出了LLM在自动化创建AAS实例、提升语义互操作性以及在工业应用中数字孪生的语义互操作性领域的潜力。相关的原型实现和评估结果已在我们的GitHub仓库中公开，具体链接为：https://github.com/YuchenXia/AASbyLLM。

> This research introduces a novel approach for assisting the creation of Asset Administration Shell (AAS) instances for digital twin modeling within the context of Industry 4.0, aiming to enhance interoperability in smart manufacturing and reduce manual effort. We construct a "semantic node" data structure to capture the semantic essence of textual data. Then, a system powered by large language models is designed and implemented to process "semantic node" and generate AAS instance models from textual technical data. Our evaluation demonstrates a 62-79% effective generation rate, indicating a substantial proportion of manual creation effort can be converted into easier validation effort, thereby reducing the time and cost in creating AAS instance models. In our evaluation, a comparative analysis of different LLMs and an in-depth ablation study of Retrieval-Augmented Generation (RAG) mechanisms provide insights into the effectiveness of LLM systems for interpreting technical concepts. Our findings emphasize LLMs' capability in automating AAS instance creation, enhancing semantic interoperability, and contributing to the broader field of semantic interoperability for digital twins in industrial applications. The prototype implementation and evaluation results are released on our GitHub Repository with the link: https://github.com/YuchenXia/AASbyLLM

[Arxiv](https://arxiv.org/abs/2403.17209)