# 电子健康记录信息检索的实践经验：嵌入模型与池化策略的对比分析

发布时间：2024年09月23日

`RAG` `信息检索`

> Lessons Learned on Information Retrieval in Electronic Health Records: A Comparison of Embedding Models and Pooling Strategies

# 摘要

> 目标：将 LLM 应用于临床领域因医疗记录的高度上下文依赖性而充满挑战。RAG 通过增强对大量文本的推理能力提供了解决方案，但检索系统中的参数优化仍需深入研究。本文通过消融研究，探讨了不同嵌入模型和池化方法对临床信息检索的影响。方法：我们在两个 EHR 数据源上的三个检索任务中，对比了七种模型，包括医学和通用领域模型、专用编码器嵌入模型及现成的解码器 LLM。我们还独立分析了各模型在查询和文本检索中的嵌入池化策略。结果：研究发现，嵌入模型的选择对检索性能影响显著，其中 BGE 这一通用领域的小型模型表现尤为突出，超越了所有医学特定模型。此外，数据集和查询文本的差异也带来了显著的性能波动。我们还确定了各模型的最佳池化方法，为未来检索系统设计提供了指导。讨论：嵌入模型、池化策略及查询设计的合理选择，对检索性能及模型在新领域的适应性至关重要。本研究强调了进一步探索的重要性，以推动基于实证的检索框架在临床领域的应用，特别是在 RAG 的背景下。

> Objective: Applying large language models (LLMs) to the clinical domain is challenging due to the context-heavy nature of processing medical records. Retrieval-augmented generation (RAG) offers a solution by facilitating reasoning over large text sources. However, there are many parameters to optimize in just the retrieval system alone. This paper presents an ablation study exploring how different embedding models and pooling methods affect information retrieval for the clinical domain.
  Methods: Evaluating on three retrieval tasks on two electronic health record (EHR) data sources, we compared seven models, including medical- and general-domain models, specialized encoder embedding models, and off-the-shelf decoder LLMs. We also examine the choice of embedding pooling strategy for each model, independently on the query and the text to retrieve.
  Results: We found that the choice of embedding model significantly impacts retrieval performance, with BGE, a comparatively small general-domain model, consistently outperforming all others, including medical-specific models. However, our findings also revealed substantial variability across datasets and query text phrasings. We also determined the best pooling methods for each of these models to guide future design of retrieval systems.
  Discussion: The choice of embedding model, pooling strategy, and query formulation can significantly impact retrieval performance and the performance of these models on other public benchmarks does not necessarily transfer to new domains. Further studies such as this one are vital for guiding empirically-grounded development of retrieval frameworks, such as in the context of RAG, for the clinical domain.

[Arxiv](https://arxiv.org/abs/2409.15163)