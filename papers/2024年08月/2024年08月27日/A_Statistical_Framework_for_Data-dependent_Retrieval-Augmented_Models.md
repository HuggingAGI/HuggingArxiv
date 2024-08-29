# 数据驱动型检索增强模型的统计框架

发布时间：2024年08月27日

`RAG` `机器学习` `问答系统`

> A Statistical Framework for Data-dependent Retrieval-Augmented Models

# 摘要

> 现代机器学习系统正日益通过融入更多相关信息来提升输入实例的预测质量。尽管这类检索增强模型备受关注，但其核心特性和训练机制仍待深入探究。为此，我们构建了一个统计框架，该框架包含两个关键组件：一是{\em检索器}，它依据数据依赖的度量标准从庞大数据集中筛选出相关信息；二是{\em预测器}，它结合原始输入与检索所得信息做出精准预测。我们设计了一套端到端训练流程，并探讨了其与现有训练策略的关联。同时，我们为检索增强模型设定了风险上限，并剖析了检索器与预测器对整体性能的贡献。通过在开放域问答任务中的实证研究，我们验证了所提训练方法的实效性，并总结了统计分析的关键洞见，凸显了检索增强在此类任务中的重要性。

> Modern ML systems increasingly augment input instances with additional relevant information to enhance final prediction. Despite growing interest in such retrieval-augmented models, their fundamental properties and training are not well understood. We propose a statistical framework to study such models with two components: 1) a {\em retriever} to identify the relevant information out of a large corpus via a data-dependent metric; and 2) a {\em predictor} that consumes the input instances along with the retrieved information to make the final predictions. We present a principled method for end-to-end training of both components and draw connections with various training approaches in the literature. Furthermore, we establish excess risk bounds for retrieval-augmented models while delineating the contributions of both retriever and predictor towards the model performance. We validate the utility of our proposed training methods along with the key takeaways from our statistical analysis on open domain question answering task where retrieval augmentation is important.

[Arxiv](https://arxiv.org/abs/2408.15399)