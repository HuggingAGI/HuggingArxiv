# LLM 在代码生成中的幻觉现象、产生机制及缓解策略

发布时间：2024年09月30日

`LLM应用` `软件开发` `人工智能`

> LLM Hallucinations in Practical Code Generation: Phenomena, Mechanism, and Mitigation

# 摘要

> 代码生成旨在根据输入需求自动生成代码，显著提高开发效率。基于大型语言模型 (LLM) 的最新方法已显示出有希望的结果，并彻底改变了代码生成任务。尽管性能有希望，但 LLM 经常生成带有幻觉的内容，特别是在需要处理实际开发过程中复杂上下文依赖的代码生成场景中。尽管之前的研究已经分析了 LLM 驱动的代码生成中的幻觉，但该研究仅限于独立函数生成。在本文中，我们进行了一项实证研究，以研究在仓库级别生成场景中更实际和复杂的开发上下文中的 LLM 幻觉现象、机制和缓解措施。首先，我们手动检查了来自六个主流 LLM 的代码生成结果，以建立 LLM 生成的代码的幻觉分类。接下来，我们详细阐述了幻觉现象，分析了它们在不同模型中的分布。然后，我们分析了幻觉的原因，并确定了四个可能导致幻觉的因素。最后，我们提出了一种基于 RAG 的缓解方法，该方法在所有研究的 LLM 中表现出一致的有效性。包括代码、数据和实验结果的复制包可在 https://github.com/DeepSoftwareAnalytics/LLMCodingHallucination 获取。

> Code generation aims to automatically generate code from input requirements, significantly enhancing development efficiency. Recent large language models (LLMs) based approaches have shown promising results and revolutionized code generation task. Despite the promising performance, LLMs often generate contents with hallucinations, especially for the code generation scenario requiring the handling of complex contextual dependencies in practical development process. Although previous study has analyzed hallucinations in LLM-powered code generation, the study is limited to standalone function generation. In this paper, we conduct an empirical study to study the phenomena, mechanism, and mitigation of LLM hallucinations within more practical and complex development contexts in repository-level generation scenario. First, we manually examine the code generation results from six mainstream LLMs to establish a hallucination taxonomy of LLM-generated code. Next, we elaborate on the phenomenon of hallucinations, analyze their distribution across different models. We then analyze causes of hallucinations and identify four potential factors contributing to hallucinations. Finally, we propose an RAG-based mitigation method, which demonstrates consistent effectiveness in all studied LLMs. The replication package including code, data, and experimental results is available at https://github.com/DeepSoftwareAnalytics/LLMCodingHallucination

[Arxiv](https://arxiv.org/abs/2409.20550)