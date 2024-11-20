# 借助优化的向量检索与指令提升问答的精准度

发布时间：2024年11月01日

`LLM应用` `信息检索` `问答系统`

> Enhancing Question Answering Precision with Optimized Vector Retrieval and Instructions

# 摘要

> 问答（QA）是信息检索（IR）和语言模型的重要应用，当下的最新趋势是朝着具备嵌入参数的预训练大型神经网络发展。借助这些大型语言模型（LLMs）提升问答性能，需要大量计算资源用于微调。我们提出了一种创新途径，通过融合优化的向量检索与指导方法来改进问答任务的表现。基于检索增强，此过程涵盖文档嵌入、向量检索以及上下文构建，以获取最优的问答结果。我们对不同的文本分割技术与相似性函数组合展开实验，并剖析它们对问答性能的影响。结果显示，块大小为 100 且块间无重叠的模型效果最佳，胜过基于句子语义分割的模型。我们探讨了相关的问答实例，并深入阐释了在两阶段框架内模型性能得以提升的方式。

> Question-answering (QA) is an important application of Information Retrieval (IR) and language models, and the latest trend is toward pre-trained large neural networks with embedding parameters. Augmenting QA performances with these LLMs requires intensive computational resources for fine-tuning. We propose an innovative approach to improve QA task performances by integrating optimized vector retrievals and instruction methodologies. Based on retrieval augmentation, the process involves document embedding, vector retrieval, and context construction for optimal QA results. We experiment with different combinations of text segmentation techniques and similarity functions, and analyze their impacts on QA performances. Results show that the model with a small chunk size of 100 without any overlap of the chunks achieves the best result and outperforms the models based on semantic segmentation using sentences. We discuss related QA examples and offer insight into how model performances are improved within the two-stage framework.

[Arxiv](https://arxiv.org/abs/2411.01039)