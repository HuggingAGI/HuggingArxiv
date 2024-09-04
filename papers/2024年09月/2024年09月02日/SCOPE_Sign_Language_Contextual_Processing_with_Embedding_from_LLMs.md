# SCOPE：利用 LLM 嵌入技术进行手语上下文处理

发布时间：2024年09月02日

`LLM应用` `聋人社区` `符号语言`

> SCOPE: Sign Language Contextual Processing with Embedding from LLMs

# 摘要

> 全球约有7000万聋人使用的符号语言，通过视觉传递丰富信息。然而，当前基于视觉的SLR和SLT技术在处理对话场景时受限于数据集的单一性和上下文信息的忽视。为此，我们创新性地提出了SCOPE框架，它结合了LLMs的嵌入技术，能够感知并利用上下文信息进行SLR和SLT。在SLR方面，我们通过多模态编码器强化了词素识别；在SLT方面，我们通过融入对话历史进一步优化了LLM。同时，我们发布了一个包含72小时中国符号语言对话视频的新数据集，覆盖多种情境。实验显示，SCOPE在多个数据集上表现卓越，且聋人社区的反馈证实了其在现实中的实用价值。我们承诺将数据集和代码公开，助力该领域的深入探索。

> Sign languages, used by around 70 million Deaf individuals globally, are visual languages that convey visual and contextual information. Current methods in vision-based sign language recognition (SLR) and translation (SLT) struggle with dialogue scenes due to limited dataset diversity and the neglect of contextually relevant information. To address these challenges, we introduce SCOPE (Sign language Contextual Processing with Embedding from LLMs), a novel context-aware vision-based SLR and SLT framework. For SLR, we utilize dialogue contexts through a multi-modal encoder to enhance gloss-level recognition. For subsequent SLT, we further fine-tune a Large Language Model (LLM) by incorporating prior conversational context. We also contribute a new sign language dataset that contains 72 hours of Chinese sign language videos in contextual dialogues across various scenarios. Experimental results demonstrate that our SCOPE framework achieves state-of-the-art performance on multiple datasets, including Phoenix-2014T, CSL-Daily, and our SCOPE dataset. Moreover, surveys conducted with participants from the Deaf community further validate the robustness and effectiveness of our approach in real-world applications. Both our dataset and code will be open-sourced to facilitate further research.

[Arxiv](https://arxiv.org/abs/2409.01073)