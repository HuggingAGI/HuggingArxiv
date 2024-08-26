# 探索大型语言模型在电商领域的应用

发布时间：2024年08月22日

`LLM应用` `电子商务`

> Investigating LLM Applications in E-Commerce

# 摘要

> 大型语言模型（LLM）的崛起，为自然语言处理领域，尤其是电子商务应用，带来了革命性的变革。在将这些模型应用于实际场景之前，理解并比较它们在不同任务中的表现至关重要。本文深入探讨了 LLM 在电商领域的应用效果，通过使用多样化的公共电商数据集对开源 LLM 进行指令调优，并对比了其在工业标准模型中的表现。我们详细比较了 LLM 与传统预训练模型在电商核心任务（如分类、生成、摘要和命名实体识别）中的性能。同时，我们还评估了在电商特定任务中采用情境学习的大型 LLM 的实际效果。研究发现，大型 LLM 的少量样本推理往往不及对小型预训练模型的精细调整，强调了针对特定任务进行模型优化的必要性。此外，我们还探索了包括单任务、混合任务训练及跨任务的 LoRA 融合等多种训练策略。通过一系列严谨的实验与分析，本文为 LLM 在电商行业中提升自然语言处理能力的潜力提供了深刻见解。

> The emergence of Large Language Models (LLMs) has revolutionized natural language processing in various applications especially in e-commerce. One crucial step before the application of such LLMs in these fields is to understand and compare the performance in different use cases in such tasks. This paper explored the efficacy of LLMs in the e-commerce domain, focusing on instruction-tuning an open source LLM model with public e-commerce datasets of varying sizes and comparing the performance with the conventional models prevalent in industrial applications. We conducted a comprehensive comparison between LLMs and traditional pre-trained language models across specific tasks intrinsic to the e-commerce domain, namely classification, generation, summarization, and named entity recognition (NER). Furthermore, we examined the effectiveness of the current niche industrial application of very large LLM, using in-context learning, in e-commerce specific tasks. Our findings indicate that few-shot inference with very large LLMs often does not outperform fine-tuning smaller pre-trained models, underscoring the importance of task-specific model optimization.Additionally, we investigated different training methodologies such as single-task training, mixed-task training, and LoRA merging both within domain/tasks and between different tasks. Through rigorous experimentation and analysis, this paper offers valuable insights into the potential effectiveness of LLMs to advance natural language processing capabilities within the e-commerce industry.

[Arxiv](https://arxiv.org/abs/2408.12779)