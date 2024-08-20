# PanoSent：一款全景式六重提取基准，专为多模态对话中的基于方面的情感分析设计

发布时间：2024年08月18日

`LLM应用` `情感分析` `多模态数据处理`

> PanoSent: A Panoptic Sextuple Extraction Benchmark for Multimodal Conversational Aspect-based Sentiment Analysis

# 摘要

> 尽管 ABSA 领域已取得显著进展，但在整合多模态、对话上下文、细粒度及情感动态与认知因果方面仍存挑战。本文通过提出多模态对话 ABSA，填补了这些研究空白，并引入了两个创新子任务：全景情感六元组提取和情感翻转分析。为支持这些任务，我们构建了高质量、多模态的 PanoSent 数据集。同时，我们设计了情感链推理框架和多模态语言模型 Sentica，以及释义验证机制，以有效应对挑战。实验证明，我们的方法性能卓越，为 ABSA 领域开辟了新纪元。所有资源均已公开，详情访问 https://PanoSent.github.io/。

> While existing Aspect-based Sentiment Analysis (ABSA) has received extensive effort and advancement, there are still gaps in defining a more holistic research target seamlessly integrating multimodality, conversation context, fine-granularity, and also covering the changing sentiment dynamics as well as cognitive causal rationales. This paper bridges the gaps by introducing a multimodal conversational ABSA, where two novel subtasks are proposed: 1) Panoptic Sentiment Sextuple Extraction, panoramically recognizing holder, target, aspect, opinion, sentiment, rationale from multi-turn multi-party multimodal dialogue. 2) Sentiment Flipping Analysis, detecting the dynamic sentiment transformation throughout the conversation with the causal reasons. To benchmark the tasks, we construct PanoSent, a dataset annotated both manually and automatically, featuring high quality, large scale, multimodality, multilingualism, multi-scenarios, and covering both implicit and explicit sentiment elements. To effectively address the tasks, we devise a novel Chain-of-Sentiment reasoning framework, together with a novel multimodal large language model (namely Sentica) and a paraphrase-based verification mechanism. Extensive evaluations demonstrate the superiority of our methods over strong baselines, validating the efficacy of all our proposed methods. The work is expected to open up a new era for the ABSA community, and thus all our codes and data are open at https://PanoSent.github.io/

[Arxiv](https://arxiv.org/abs/2408.09481)