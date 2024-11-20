# 评估大型语言模型在印度官方语言里的分词器表现

发布时间：2024年11月19日

`LLM应用` `语言模型` `印度语言`

> Evaluating Tokenizer Performance of Large Language Models Across Official Indian Languages

# 摘要

> 基于 Transformer 架构的大型语言模型（LLMs）已在众多领域掀起变革，标记化在其预处理和微调阶段发挥着关键作用。在多语言模型，尤其是为印度语言定制的模型中，有效的标记化对优化性能极为重要。本文全面评估了涵盖印度所有 22 种官方语言的 12 个 LLMs 所使用的标记器，重点对比了它们标记化过程的效率。我们在分析中运用了归一化序列长度（NSL）这一关键指标。研究发现，SUTRA 标记器胜过其他所有模型，包括数个印度专属模型，在 14 种语言中表现卓越。显著的发现有：SUTRA 标记器处理印度语言的出色能力、GPT-4o 相比其前身 GPT-4 在处理印度语言上的进步，以及 Project Indus 在某些语言中的有限表现。本研究突显了为多语言和以印度为核心的模型开发针对性标记化策略的极端重要性，为未来标记器设计的改进奠定基础，以增强语言覆盖范围和模型效率。

> Large Language Models (LLMs) based on transformer architectures have revolutionized a variety of domains, with tokenization playing a pivotal role in their pre-processing and fine-tuning stages. In multilingual models, particularly those tailored for Indic languages, effective tokenization is crucial for optimizing performance. This paper presents a comprehensive evaluation of tokenizers used by 12 LLMs across all 22 official languages of India, with a focus on comparing the efficiency of their tokenization processes. We employed the Normalized Sequence Length (NSL) as a key metric in our analysis. Our findings reveal that the SUTRA tokenizer outperforms all other models, including several Indic-specific models, excelling in 14 languages. Notable insights include the SUTRA tokenizer's superior handling of Indic languages, GPT-4o's advancement over its predecessor GPT-4 in processing Indian languages, and the limited performance of Project Indus in certain languages. This study underscores the critical importance of developing targeted tokenization strategies for multilingual and Indic-centric models, laying the groundwork for future improvements in tokenizer design to enhance linguistic coverage and model efficiency.

[Arxiv](https://arxiv.org/abs/2411.12240)