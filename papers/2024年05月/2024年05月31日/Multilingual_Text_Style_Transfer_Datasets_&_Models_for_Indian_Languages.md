# 探索印度语言的多语言文本风格转换：数据集与模型概览

发布时间：2024年05月31日

`LLM应用

理由：这篇论文主要探讨了文本风格转换（TST）中的情感转移任务，特别是在八种印度语言中的应用。它涉及了多种模型（如Llama2和GPT-3.5）的评估，并强调了平行数据集的重要性以及掩码风格填充（MSF）方法的有效性。这些内容主要关注于大型语言模型（LLM）在实际应用中的表现和优化，特别是在多语言环境下的情感转移任务，因此归类为LLM应用。` `跨语言研究`

> Multilingual Text Style Transfer: Datasets & Models for Indian Languages

# 摘要

> 文本风格转换（TST）旨在改变文本的语言风格而不失其核心内容。本文专注于情感转移，这是TST的关键子任务，并扩展至八种印度语言：印地语、马加希语、马拉雅拉姆语、马拉地语、旁遮普语、奥里亚语、泰卢固语和乌尔都语，超越了之前的英语-孟加拉语研究。我们为每种语言精心准备了包含1,000个积极和1,000个消极句子的平行数据集。通过评估包括Llama2和GPT-3.5在内的多种模型，我们发现平行数据在TST中至关重要，并验证了掩码风格填充（MSF）方法在非平行技术中的高效性。跨语言和多语言联合学习方法展现出潜力，为根据特定语言和任务需求选择最佳模型提供了新视角。这是首次对TST任务在多种语言中进行情感转移的全面探索。

> Text style transfer (TST) involves altering the linguistic style of a text while preserving its core content. This paper focuses on sentiment transfer, a vital TST subtask (Mukherjee et al., 2022a), across a spectrum of Indian languages: Hindi, Magahi, Malayalam, Marathi, Punjabi, Odia, Telugu, and Urdu, expanding upon previous work on English-Bangla sentiment transfer (Mukherjee et al., 2023). We introduce dedicated datasets of 1,000 positive and 1,000 negative style-parallel sentences for each of these eight languages. We then evaluate the performance of various benchmark models categorized into parallel, non-parallel, cross-lingual, and shared learning approaches, including the Llama2 and GPT-3.5 large language models (LLMs). Our experiments highlight the significance of parallel data in TST and demonstrate the effectiveness of the Masked Style Filling (MSF) approach (Mukherjee et al., 2023) in non-parallel techniques. Moreover, cross-lingual and joint multilingual learning methods show promise, offering insights into selecting optimal models tailored to the specific language and task requirements. To the best of our knowledge, this work represents the first comprehensive exploration of the TST task as sentiment transfer across a diverse set of languages.

[Arxiv](https://arxiv.org/abs/2405.20805)