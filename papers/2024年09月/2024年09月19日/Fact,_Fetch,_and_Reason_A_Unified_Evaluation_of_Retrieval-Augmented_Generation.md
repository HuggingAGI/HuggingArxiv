# 事实、获取与推理：检索增强生成的综合评估

发布时间：2024年09月19日

`RAG` `人工智能` `数据科学`

> Fact, Fetch, and Reason: A Unified Evaluation of Retrieval-Augmented Generation

# 摘要

> 大型语言模型 (LLM) 在多种认知任务中表现出色，其中一项新兴应用是增强检索增强生成 (RAG) 能力。这类系统要求 LLM 理解用户查询、检索相关信息并生成连贯准确的回答。随着这些系统在实际应用中的普及，全面评估变得尤为重要。为此，我们推出了 FRAMES (Factuality, Retrieval, And reasoning MEasurement Set)，一个专为测试 LLM 事实性响应、检索能力和推理能力而设计的高质量数据集。与以往单独评估这些能力的数据集不同，FRAMES 提供了一个统一框架，更全面地展示了 LLM 在端到端 RAG 场景中的表现。我们的数据集包含复杂的多跳问题，需要整合多源信息。基线测试显示，即使是最先进的 LLM 也难以应对，无检索时准确率仅为 0.40。而通过我们提出的多步骤检索流程，准确率大幅提升至 0.66，改善超过 50%。我们期待 FRAMES 能帮助弥合评估差距，推动更强大 RAG 系统的开发。

> Large Language Models (LLMs) have demonstrated significant performance improvements across various cognitive tasks. An emerging application is using LLMs to enhance retrieval-augmented generation (RAG) capabilities. These systems require LLMs to understand user queries, retrieve relevant information, and synthesize coherent and accurate responses. Given the increasing real-world deployment of such systems, comprehensive evaluation becomes crucial. To this end, we propose FRAMES (Factuality, Retrieval, And reasoning MEasurement Set), a high-quality evaluation dataset designed to test LLMs' ability to provide factual responses, assess retrieval capabilities, and evaluate the reasoning required to generate final answers. While previous work has provided datasets and benchmarks to evaluate these abilities in isolation, FRAMES offers a unified framework that provides a clearer picture of LLM performance in end-to-end RAG scenarios. Our dataset comprises challenging multi-hop questions that require the integration of information from multiple sources. We present baseline results demonstrating that even state-of-the-art LLMs struggle with this task, achieving 0.40 accuracy with no retrieval. The accuracy is significantly improved with our proposed multi-step retrieval pipeline, achieving an accuracy of 0.66 (>50% improvement). We hope our work will help bridge evaluation gaps and assist in developing more robust and capable RAG systems.

[Arxiv](https://arxiv.org/abs/2409.12941)