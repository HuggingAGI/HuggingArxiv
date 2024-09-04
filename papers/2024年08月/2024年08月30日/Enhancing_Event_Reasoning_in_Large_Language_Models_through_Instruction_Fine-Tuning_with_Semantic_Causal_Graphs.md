# 借助语义因果图的指令微调，提升大型语言模型的事件推理能力

发布时间：2024年08月30日

`LLM应用` `事件检测` `文本推理`

> Enhancing Event Reasoning in Large Language Models through Instruction Fine-Tuning with Semantic Causal Graphs

# 摘要

> 事件检测与文本推理在多领域中至关重要。尽管LLMs在推理上进步显著，但在事件检测上常因缺乏因果关系训练而受限。为此，我们创新地提出使用语义因果图（SCGs）捕捉文本因果与上下文，进而通过SCG指令聚焦事件触发与类型关系，辅以低秩适应（LoRA）保留推理能力，微调LLMs。实证显示，此法在事件触发分类上较传统微调提升35.69%。特别地，微调后的Mistral 7B模型在多项关键指标上超越GPT-4，平均提升显著。研究还表明，通用能力仅轻微下降。本研究深入探讨了LLMs在多样情境下的事件检测表现。

> Event detection and text reasoning have become critical applications across various domains. While LLMs have recently demonstrated impressive progress in reasoning abilities, they often struggle with event detection, particularly due to the absence of training methods that consider causal relationships between event triggers and types. To address this challenge, we propose a novel approach for instruction fine-tuning LLMs for event detection. Our method introduces Semantic Causal Graphs (SCGs) to capture both causal relationships and contextual information within text. Building off of SCGs, we propose SCG Instructions for fine-tuning LLMs by focusing on event triggers and their relationships to event types, and employ Low-Rank Adaptation (LoRA) to help preserve the general reasoning abilities of LLMs. Our evaluations demonstrate that training LLMs with SCG Instructions outperforms standard instruction fine-tuning by an average of 35.69\% on Event Trigger Classification. Notably, our fine-tuned Mistral 7B model also outperforms GPT-4 on key event detection metrics by an average of 31.01\% on Event Trigger Identification, 37.40\% on Event Trigger Classification, and 16.43\% on Event Classification. We analyze the retention of general capabilities, observing only a minimal average drop of 2.03 points across six benchmarks. This comprehensive study investigates multiple LLMs for the event detection task across various datasets, prompting strategies, and training approaches.

[Arxiv](https://arxiv.org/abs/2409.00209)