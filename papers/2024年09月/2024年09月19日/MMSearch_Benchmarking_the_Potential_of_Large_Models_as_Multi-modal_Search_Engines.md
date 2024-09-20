# MMSearch：探索大型模型在多模态搜索中的潜力

发布时间：2024年09月19日

`LLM应用` `搜索引擎` `人工智能`

> MMSearch: Benchmarking the Potential of Large Models as Multi-modal Search Engines

# 摘要

> 大型语言模型 (LLM) 的崛起催生了 AI 搜索引擎（如 SearchGPT），为人机交互开辟了新天地。然而，现有 AI 搜索引擎多局限于纯文本，忽略了多模态查询和图文交织的网站信息。近期，大型多模态模型 (LMM) 虽有显著进展，但其作为 AI 搜索引擎的潜力仍待挖掘。为此，我们设计了 MMSearch-Engine 管道，赋予 LMM 多模态搜索能力，并推出 MMSearch 评估基准，全面检验其性能。数据集包含 300 个无训练数据重叠的实例，确保答案仅能通过搜索获得。实验表明，GPT-4o 结合 MMSearch-Engine 在端到端任务中超越了 Perplexity Pro，验证了管道的有效性。我们还通过错误分析和消融研究，揭示了 LMM 在多模态搜索中的挑战与潜力。希望 MMSearch 能为多模态 AI 搜索引擎的未来发展提供新思路。项目页面：https://mmsearch.github.io

> The advent of Large Language Models (LLMs) has paved the way for AI search engines, e.g., SearchGPT, showcasing a new paradigm in human-internet interaction. However, most current AI search engines are limited to text-only settings, neglecting the multimodal user queries and the text-image interleaved nature of website information. Recently, Large Multimodal Models (LMMs) have made impressive strides. Yet, whether they can function as AI search engines remains under-explored, leaving the potential of LMMs in multimodal search an open question. To this end, we first design a delicate pipeline, MMSearch-Engine, to empower any LMMs with multimodal search capabilities. On top of this, we introduce MMSearch, a comprehensive evaluation benchmark to assess the multimodal search performance of LMMs. The curated dataset contains 300 manually collected instances spanning 14 subfields, which involves no overlap with the current LMMs' training data, ensuring the correct answer can only be obtained within searching. By using MMSearch-Engine, the LMMs are evaluated by performing three individual tasks (requery, rerank, and summarization), and one challenging end-to-end task with a complete searching process. We conduct extensive experiments on closed-source and open-source LMMs. Among all tested models, GPT-4o with MMSearch-Engine achieves the best results, which surpasses the commercial product, Perplexity Pro, in the end-to-end task, demonstrating the effectiveness of our proposed pipeline. We further present error analysis to unveil current LMMs still struggle to fully grasp the multimodal search tasks, and conduct ablation study to indicate the potential of scaling test-time computation for AI search engine. We hope MMSearch may provide unique insights to guide the future development of multimodal AI search engine. Project Page: https://mmsearch.github.io

[Arxiv](https://arxiv.org/abs/2409.12959)