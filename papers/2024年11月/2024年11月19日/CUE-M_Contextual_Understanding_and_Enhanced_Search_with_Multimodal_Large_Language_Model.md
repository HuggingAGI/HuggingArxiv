# CUE-M：借助多模态大型语言模型实现的上下文理解与增强搜索

发布时间：2024年11月19日

`RAG` `多模态`

> CUE-M: Contextual Understanding and Enhanced Search with Multimodal Large Language Model

# 摘要

> RAG 与 MLLMs 的集成拓展了多模态查询解决的范畴。但当下的系统在意图理解、信息检索和安全过滤上遭遇难题，制约了其效用。本文引入了 CUE-M，即具有 MLLM 的上下文理解和增强搜索，这是一种新型的多模态搜索管道，它通过包含图像上下文丰富、意图细化、上下文查询生成、外部 API 集成以及基于相关性的过滤的多阶段框架来应对上述挑战。CUE-M 融入了一个强大的安全框架，它整合了基于图像、基于文本和多模态的分类器，能动态适应实例和类别特定的风险。在多模态问答数据集和公共安全基准上的评估显示，CUE-M 在准确性、知识集成和安全性方面优于基线，增强了多模态检索系统的能力。

> The integration of Retrieval-Augmented Generation (RAG) with Multimodal Large Language Models (MLLMs) has expanded the scope of multimodal query resolution. However, current systems struggle with intent understanding, information retrieval, and safety filtering, limiting their effectiveness. This paper introduces Contextual Understanding and Enhanced Search with MLLM (CUE-M), a novel multimodal search pipeline that addresses these challenges through a multi-stage framework comprising image context enrichment, intent refinement, contextual query generation, external API integration, and relevance-based filtering. CUE-M incorporates a robust safety framework combining image-based, text-based, and multimodal classifiers, dynamically adapting to instance- and category-specific risks. Evaluations on a multimodal Q&A dataset and a public safety benchmark demonstrate that CUE-M outperforms baselines in accuracy, knowledge integration, and safety, advancing the capabilities of multimodal retrieval systems.

[Arxiv](https://arxiv.org/abs/2411.12287)