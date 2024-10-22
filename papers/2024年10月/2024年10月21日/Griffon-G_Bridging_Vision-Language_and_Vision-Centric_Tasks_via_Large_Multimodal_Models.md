# Griffon-G：借助大型多模态模型，架起视觉-语言与视觉核心任务之间的桥梁

发布时间：2024年10月21日

`LLM应用` `人工智能` `计算机视觉`

> Griffon-G: Bridging Vision-Language and Vision-Centric Tasks via Large Multimodal Models

# 摘要

> 大型多模态模型 (LMMs) 在视觉与语言结合的任务中表现出色，但它们往往只专注于单一类型的任务，如视觉定位或图像描述。目前，还没有模型能像大型语言模型那样，全面整合视觉与语言任务。此外，尽管有多任务数据支持，直接扩展通用能力仍具挑战。为此，我们推出了 CCMD-8M 数据集，通过多层次精选与整合，解决了视觉与语言任务的统一难题。更重要的是，我们开发了 Griffon-G 模型，它在一个端到端框架内，同时处理视觉与语言任务，并有效避免了训练中的崩溃问题。在多项基准测试中，Griffon-G 不仅超越了现有模型，还在复杂视觉任务中展现了专家级水准。

> Large Multimodal Models (LMMs) have achieved significant breakthroughs in various vision-language and vision-centric tasks based on auto-regressive modeling. However, these models typically focus on either vision-centric tasks, such as visual grounding and region description, or vision-language tasks, like image caption and multi-scenario VQAs. None of the LMMs have yet comprehensively unified both types of tasks within a single model, as seen in Large Language Models in the natural language processing field. Furthermore, even with abundant multi-task instruction-following data, directly stacking these data for universal capabilities extension remains challenging. To address these issues, we introduce a novel multi-dimension curated and consolidated multimodal dataset, named CCMD-8M, which overcomes the data barriers of unifying vision-centric and vision-language tasks through multi-level data curation and multi-task consolidation. More importantly, we present Griffon-G, a general large multimodal model that addresses both vision-centric and vision-language tasks within a single end-to-end paradigm. Griffon-G resolves the training collapse issue encountered during the joint optimization of these tasks, achieving better training efficiency. Evaluations across multimodal benchmarks, general Visual Question Answering (VQA) tasks, scene text-centric VQA tasks, document-related VQA tasks, Referring Expression Comprehension, and object detection demonstrate that Griffon-G surpasses the advanced LMMs and achieves expert-level performance in complicated vision-centric tasks.

[Arxiv](https://arxiv.org/abs/2410.16163)