# 从PDF构建基于RAG的LLM系统：实践经验分享

发布时间：2024年10月21日

`RAG` `人工智能` `信息检索`

> Developing Retrieval Augmented Generation (RAG) based LLM Systems from PDFs: An Experience Report

# 摘要

> 本文分享了基于 PDF 文档开发 RAG 系统的实践经验。RAG 系统融合了 LLM 的生成能力与信息检索的精准性，有望革新我们与生成模型中知识交互的方式，提升响应的透明度、准确性与上下文相关性。文章详细阐述了从数据采集、预处理到检索索引及响应生成的全流程，并探讨了技术难题与解决方案。我们旨在为使用 OpenAI 的 Assistant API 与 GPT 系列或 Llama 开源模型的研究者和开发者提供参考。此研究的应用价值在于强化生成式 AI 系统在各领域的可靠性，尤其是在需要特定领域知识与实时信息检索的场景中。相关 Python 代码已开源，详见：https://github.com/GPT-Laboratory/RAG-LLM-Development-Guidebook-from-PDFs。

> This paper presents an experience report on the development of Retrieval Augmented Generation (RAG) systems using PDF documents as the primary data source. The RAG architecture combines generative capabilities of Large Language Models (LLMs) with the precision of information retrieval. This approach has the potential to redefine how we interact with and augment both structured and unstructured knowledge in generative models to enhance transparency, accuracy, and contextuality of responses. The paper details the end-to-end pipeline, from data collection, preprocessing, to retrieval indexing and response generation, highlighting technical challenges and practical solutions. We aim to offer insights to researchers and practitioners developing similar systems using two distinct approaches: OpenAI's Assistant API with GPT Series and Llama's open-source models. The practical implications of this research lie in enhancing the reliability of generative AI systems in various sectors where domain-specific knowledge and real-time information retrieval is important. The Python code used in this work is also available at: https://github.com/GPT-Laboratory/RAG-LLM-Development-Guidebook-from-PDFs.

[Arxiv](https://arxiv.org/abs/2410.15944)