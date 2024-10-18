# 在行动之前，三思而后行：探讨大型语言模型中的思维逐步细化过程。

发布时间：2024年10月17日

`LLM理论` `人工智能`

> Think Thrice Before You Act: Progressive Thought Refinement in Large Language Models

# 摘要

> 大型语言模型 (LLM) 的最新进展表明，逐步精炼而非一次性给出答案，能产生更精准且深思熟虑的输出。然而，现有方法多依赖监督信号评估先前响应，难以在开放场景中有效评估输出质量。此外，这些方法通常针对特定任务设计，限制了其跨领域应用。为此，我们提出渐进思维精炼 (PTR) 框架，使 LLM 能逐步优化其响应。PTR 分两阶段：首先，通过弱强模型协作策略构建高质量精炼数据集，确保逻辑一致性，答案逐轮精炼；其次，设计思维掩码微调结构，调整损失权重，鼓励 LLM 优化先前思维，隐含理解“如何改进”而非“何为正确”。实验显示，PTR 显著提升 LLM 在十个任务中的表现（平均提升至 53.5%），且无需任务特定微调。尤其在开放任务中，LLM 的响应质量显著提升，表明 PTR 确实教会了 LLM 自我改进。

> Recent advancements in large language models (LLMs) have demonstrated that progressive refinement, rather than providing a single answer, results in more accurate and thoughtful outputs. However, existing methods often rely heavily on supervision signals to evaluate previous responses, making it difficult to assess output quality in more open-ended scenarios effectively. Additionally, these methods are typically designed for specific tasks, which limits their generalization to new domains. To address these limitations, we propose Progressive Thought Refinement (PTR), a framework that enables LLMs to refine their responses progressively. PTR operates in two phases: (1) Thought data construction stage: We propose a weak and strong model collaborative selection strategy to build a high-quality progressive refinement dataset to ensure logical consistency from thought to answers, and the answers are gradually refined in each round. (2) Thought-Mask Fine-Tuning Phase: We design a training structure to mask the "thought" and adjust loss weights to encourage LLMs to refine prior thought, teaching them to implicitly understand "how to improve" rather than "what is correct." Experimental results show that PTR significantly enhances LLM performance across ten diverse tasks (avg. from 49.6% to 53.5%) without task-specific fine-tuning. Notably, in more open-ended tasks, LLMs also demonstrate substantial improvements in the quality of responses beyond mere accuracy, suggesting that PTR truly teaches LLMs to self-improve over time.

[Arxiv](https://arxiv.org/abs/2410.13413)