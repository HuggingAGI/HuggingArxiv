# Athena：借助大型语言模型提升检索功能的法律判决预测系统

发布时间：2024年10月14日

`RAG` `人工智能`

> Athena: Retrieval-augmented Legal Judgment Prediction with Large Language Models

# 摘要

> 近期，ChatGPT、LLaMA 和 Claude 等大型语言模型 (LLM) 在法律等多个领域大放异彩。随着 LLM 技术的迅猛发展，提示工程 (PE) 作为连接 LLM 与实际应用的桥梁，备受开发者瞩目。为应对现实挑战，少样本提示、思维链和检索增强生成 (RAG) 等 PE 方法应运而生。然而，RAG 在法律判决预测 (LJP) 领域的探索尚显不足。为此，我们推出 "Athena" 框架，将 RAG 作为核心预处理组件，提升 LLM 在专业任务中的表现。Athena 构建了指控知识库，并结合向量化实现语义检索。实验显示，Athena 在 CAIL2018 数据集上表现卓越，整体性能显著提升。此外，通过调整上下文窗口大小参数，我们再现了 LLM 的 "中间迷失" 现象，并实现了高达 95% 的准确率。我们还探讨了查询重写与数据分布的影响，为未来研究指明方向。

> Recently, large language models (LLMs) like ChatGPT, LLaMA, and Claude have prevailed in countless domains, including legal scenarios. With LLMs' rapid technological progress, the development of prompt engineering (PE) as an interface between the LLMs and real-world applications has drawn the attention of all developers. Various PE methods have been proposed to overcome real-world challenges, such as few-shot prompting, chain-of-thought, and retrieval-augmented generation (RAG). However, RAG for legal judgment prediction (LJP) is still underexplored. To address this, we propose "Athena", a novel framework cultivating RAG as a core preprocess component to enhance LLMs' performance on specialized tasks. Athena constructs a knowledge base for accusations, attached with a semantic retrieval mechanism through vectorization. Our experiments show that Athena's overall performance has improved significantly, achieving state-of-the-art results on the CAIL2018 dataset. Our ablation study on the in-context window size parameter further reproduces LLMs' "lost-in-the-middle" phenomenon with a relative positional variation. And with moderate hyper-parameter-tuning, we can achieve at most 95% of accuracy accordingly. We also study the impact of query rewriting and data distribution, providing possible directions for future research based on former analyses.

[Arxiv](https://arxiv.org/abs/2410.11195)