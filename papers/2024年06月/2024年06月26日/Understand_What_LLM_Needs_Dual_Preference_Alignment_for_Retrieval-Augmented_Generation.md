# 洞悉LLM所需：检索增强生成中的双重偏好对齐

发布时间：2024年06月26日

`RAG

这篇论文主要讨论了检索增强生成（RAG）框架的发展，特别是针对大型语言模型（LLMs）的幻觉问题，并通过开发DPA-RAG框架来统一对齐RAG系统内的多样化知识偏好。论文中提到的技术细节和实验结果表明，该框架在知识密集型问答数据集上表现优异，并且能够与不同类型的LLM阅读器结合使用。因此，这篇论文更符合RAG分类，因为它专注于RAG系统的改进和优化。` `问答系统` `人工智能`

> Understand What LLM Needs: Dual Preference Alignment for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）有效缓解了大型语言模型（LLMs）的幻觉问题，但将检索器与多样化的LLMs知识偏好对齐的挑战依然存在。为此，我们开发了DPA-RAG框架，旨在统一对齐RAG系统内的多样化知识偏好。我们首先构建了偏好知识流程，并采用五种创新查询增强策略来解决偏好数据不足的问题。DPA-RAG通过集成成对、点对点和对比偏好对齐技术于重排器中，实现了RAG组件间的外部偏好对齐，并通过在SFT前增加预对齐阶段，使LLMs能够隐式学习与其推理偏好一致的知识，完成了LLMs的内部对齐。实验证明，DPA-RAG在四个知识密集型问答数据集上优于所有基线，并能无缝结合黑盒和开源LLM阅读器。我们的代码已公开，网址为https://github.com/dongguanting/DPA-RAG，为构建可靠的RAG系统提供了实证指导。

> Retrieval-augmented generation (RAG) has demonstrated effectiveness in mitigating the hallucination problem of large language models (LLMs). However, the difficulty of aligning the retriever with the diverse LLMs' knowledge preferences inevitably poses an inevitable challenge in developing a reliable RAG system. To address this issue, we propose DPA-RAG, a universal framework designed to align diverse knowledge preferences within RAG systems. Specifically, we initially introduce a preference knowledge construction pipline and incorporate five novel query augmentation strategies to alleviate preference data scarcity. Based on preference data, DPA-RAG accomplishes both external and internal preference alignment: 1) It jointly integrate pair-wise, point-wise, and contrastive preference alignment abilities into the reranker, achieving external preference alignment among RAG components. 2) It further introduces a pre-aligned stage before vanilla Supervised Fine-tuning (SFT), enabling LLMs to implicitly capture knowledge aligned with their reasoning preferences, achieving LLMs' internal alignment. Experimental results across four knowledge-intensive QA datasets demonstrate that DPA-RAG outperforms all baselines and seamlessly integrates both black-box and open-sourced LLM readers. Further qualitative analysis and discussions also provide empirical guidance for achieving reliable RAG systems. Our code is publicly available at https://github.com/dongguanting/DPA-RAG.

[Arxiv](https://arxiv.org/abs/2406.18676)