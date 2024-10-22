# 大型语言模型在实践中遭遇的知识冲突：谁是谁？

发布时间：2024年10月21日

`RAG` `人工智能` `数据科学`

> Who's Who: Large Language Models Meet Knowledge Conflicts in Practice

# 摘要

> RAG 方法为解决预训练语言模型的静态内存限制提供了有效途径。然而，在检索过程中遇到信息冲突是不可避免的挑战。此时，语言模型应透明地向用户揭示冲突，而非依赖固有偏见自行决定。为评估当前 LLM 在此情况下的表现，我们推出了 WhoQA 基准数据集，通过询问同名实体的共同属性，生成多达 8 种不同答案的问题，涵盖 5K 个问题、13 种 Wikidata 属性及 150K 个 Wikipedia 实体。实验显示，尽管 WhoQA 问题简单，知识冲突仍显著影响 LLM 在 RAG 环境中的性能。

> Retrieval-augmented generation (RAG) methods are viable solutions for addressing the static memory limits of pre-trained language models. Nevertheless, encountering conflicting sources of information within the retrieval context is an inevitable practical challenge. In such situations, the language models are recommended to transparently inform users about the conflicts rather than autonomously deciding what to present based on their inherent biases. To analyze how current large language models (LLMs) align with our recommendation, we introduce WhoQA, a public benchmark dataset to examine model's behavior in knowledge conflict situations. We induce conflicts by asking about a common property among entities having the same name, resulting in questions with up to 8 distinctive answers. WhoQA evaluation set includes 5K questions across 13 Wikidata property types and 150K Wikipedia entities. Our experiments show that despite the simplicity of WhoQA questions, knowledge conflicts significantly degrades LLMs' performance in RAG settings.

[Arxiv](https://arxiv.org/abs/2410.15737)