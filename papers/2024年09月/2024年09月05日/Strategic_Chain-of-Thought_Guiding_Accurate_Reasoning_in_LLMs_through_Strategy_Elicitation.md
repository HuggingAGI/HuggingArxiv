# 战略思维链：通过策略引导，助力 LLMs 实现精准推理

发布时间：2024年09月05日

`LLM应用` `人工智能`

> Strategic Chain-of-Thought: Guiding Accurate Reasoning in LLMs through Strategy Elicitation

# 摘要

> Chain-of-Thought (CoT) 范式已成为提升大型语言模型 (LLM) 推理能力的关键手段。然而，尽管广泛应用并取得成功，CoT 方法因无法稳定保证推理路径质量，常导致推理性能不佳。为此，我们提出 \textbf{Strategic Chain-of-Thought} (SCoT)，通过在推理步骤前融入战略知识，优化 LLM 性能。SCoT 在单个提示中分两步进行：先引出有效解题策略，再以此指导生成高质量推理路径和答案。实验显示，在 GSM8K 和 Tracking\_Objects 数据集上，分别提升 21.05\% 和 24.13\%，使用 Llama3-8b 模型。此外，SCoT 扩展为自动匹配演示的少样本方法，效果更佳。这些成果凸显 SCoT 在复杂推理任务中提升 LLM 性能的巨大潜力。

> The Chain-of-Thought (CoT) paradigm has emerged as a critical approach for enhancing the reasoning capabilities of large language models (LLMs). However, despite their widespread adoption and success, CoT methods often exhibit instability due to their inability to consistently ensure the quality of generated reasoning paths, leading to sub-optimal reasoning performance. To address this challenge, we propose the \textbf{Strategic Chain-of-Thought} (SCoT), a novel methodology designed to refine LLM performance by integrating strategic knowledge prior to generating intermediate reasoning steps. SCoT employs a two-stage approach within a single prompt: first eliciting an effective problem-solving strategy, which is then used to guide the generation of high-quality CoT paths and final answers. Our experiments across eight challenging reasoning datasets demonstrate significant improvements, including a 21.05\% increase on the GSM8K dataset and 24.13\% on the Tracking\_Objects dataset, respectively, using the Llama3-8b model. Additionally, we extend the SCoT framework to develop a few-shot method with automatically matched demonstrations, yielding even stronger results. These findings underscore the efficacy of SCoT, highlighting its potential to substantially enhance LLM performance in complex reasoning tasks.

[Arxiv](https://arxiv.org/abs/2409.03271)