# 长上下文检索增强生成的推理规模化

发布时间：2024年10月05日

`RAG` `人工智能`

> Inference Scaling for Long-Context Retrieval Augmented Generation

# 摘要

> 推理计算的扩展为长上下文 LLM 在各种场景中的应用打开了新的大门。对于知识密集型任务，增加的计算资源通常用于整合更多外部知识。然而，仅靠扩展上下文并不总能提升性能，除非这些知识得到有效利用。我们深入研究了检索增强生成 (RAG) 的推理扩展策略，超越了单纯增加知识量的范畴。我们聚焦于两种策略：上下文学习和迭代提示。这些策略通过增加检索文档或生成步骤，灵活扩展测试时的计算，从而提升 LLM 获取和利用上下文信息的能力。我们探讨了两个核心问题：(1) 在最佳配置下，推理计算的扩展如何提升 RAG 性能？(2) 能否通过建模 RAG 性能与推理参数的关系，预测在给定预算下的最佳计算分配？我们的研究发现，当计算资源得到最佳分配时，RAG 性能几乎呈线性增长，这被称为 RAG 的推理扩展定律。基于此，我们构建了计算分配模型，预测不同配置下的 RAG 性能，其结果与实验数据高度吻合。通过应用这些最佳配置，我们在长上下文 LLM 上实现了高达 58.9% 的性能提升，远超标准 RAG。

> The scaling of inference computation has unlocked the potential of long-context large language models (LLMs) across diverse settings. For knowledge-intensive tasks, the increased compute is often allocated to incorporate more external knowledge. However, without effectively utilizing such knowledge, solely expanding context does not always enhance performance. In this work, we investigate inference scaling for retrieval augmented generation (RAG), exploring strategies beyond simply increasing the quantity of knowledge. We focus on two inference scaling strategies: in-context learning and iterative prompting. These strategies provide additional flexibility to scale test-time computation (e.g., by increasing retrieved documents or generation steps), thereby enhancing LLMs' ability to effectively acquire and utilize contextual information. We address two key questions: (1) How does RAG performance benefit from the scaling of inference computation when optimally configured? (2) Can we predict the optimal test-time compute allocation for a given budget by modeling the relationship between RAG performance and inference parameters? Our observations reveal that increasing inference computation leads to nearly linear gains in RAG performance when optimally allocated, a relationship we describe as the inference scaling laws for RAG. Building on this, we further develop the computation allocation model to estimate RAG performance across different inference configurations. The model predicts optimal inference parameters under various computation constraints, which align closely with the experimental results. By applying these optimal configurations, we demonstrate that scaling inference compute on long-context LLMs achieves up to 58.9% gains on benchmark datasets compared to standard RAG.

[Arxiv](https://arxiv.org/abs/2410.04343)