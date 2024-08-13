# 本研究聚焦于优化汽车行业PDF聊天机器人的RAG技术，通过本地部署Ollama模型进行案例分析。

发布时间：2024年08月12日

`RAG` `智能制造`

> Optimizing RAG Techniques for Automotive Industry PDF Chatbots: A Case Study with Locally Deployed Ollama Models

# 摘要

> 随着汽车工业对离线PDF聊天机器人需求的增长，优化大型语言模型在本地低性能环境中的部署变得至关重要。本研究聚焦于利用本地Ollama模型提升处理复杂汽车行业文档的RAG技术。基于Langchain框架，我们提出了一种多维优化策略，针对Ollama的本地RAG实现。我们的方法解决了汽车文档处理中的关键问题，如多列布局和技术规格。我们改进了PDF处理、检索机制和上下文压缩，以适应汽车行业文档的独特性。此外，我们还设计了支持嵌入流程的自定义类和一个基于最佳实践的自RAG代理。为了评估我们的方法，我们构建了一个包含典型汽车行业文档的专有数据集，并在三个数据集上进行了比较。结果显示，在上下文精度、召回率、答案相关性和忠实度方面有显著提升，特别是在汽车行业数据集上表现卓越。我们的优化方案为汽车行业部署本地RAG系统提供了有效途径，满足了工业生产环境中PDF聊天机器人的特定需求。这项研究对推进汽车行业的信息处理和智能生产具有深远影响。

> With the growing demand for offline PDF chatbots in automotive industrial production environments, optimizing the deployment of large language models (LLMs) in local, low-performance settings has become increasingly important. This study focuses on enhancing Retrieval-Augmented Generation (RAG) techniques for processing complex automotive industry documents using locally deployed Ollama models. Based on the Langchain framework, we propose a multi-dimensional optimization approach for Ollama's local RAG implementation. Our method addresses key challenges in automotive document processing, including multi-column layouts and technical specifications. We introduce improvements in PDF processing, retrieval mechanisms, and context compression, tailored to the unique characteristics of automotive industry documents. Additionally, we design custom classes supporting embedding pipelines and an agent supporting self-RAG based on LangGraph best practices. To evaluate our approach, we constructed a proprietary dataset comprising typical automotive industry documents, including technical reports and corporate regulations. We compared our optimized RAG model and self-RAG agent against a naive RAG baseline across three datasets: our automotive industry dataset, QReCC, and CoQA. Results demonstrate significant improvements in context precision, context recall, answer relevancy, and faithfulness, with particularly notable performance on the automotive industry dataset. Our optimization scheme provides an effective solution for deploying local RAG systems in the automotive sector, addressing the specific needs of PDF chatbots in industrial production environments. This research has important implications for advancing information processing and intelligent production in the automotive industry.

[Arxiv](https://arxiv.org/abs/2408.05933)