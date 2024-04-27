# EmoVIT：以视觉指令调校，引领情感洞察力的革新。

发布时间：2024年04月25日

`LLM应用` `情感分析`

> EmoVIT: Revolutionizing Emotion Insights with Visual Instruction Tuning

# 摘要

> 视觉指令调优是一种新颖的学习范式，它通过特定任务指令对预训练的语言模型进行精准调整。这一范式在多种自然语言处理任务中展现了出色的零样本性能，但在视觉情感理解领域尚待深入研究。本研究致力于提升模型对情感语境相关指令的理解和执行能力。我们首先识别了对视觉情感识别至关重要的关键视觉线索。接着，我们提出了一个创新的GPT辅助流程，用于生成情感视觉指令数据，有效解决了该领域标注指令数据不足的问题。在InstructBLIP的基础上，我们设计的EmoVIT架构整合了针对情感的指令数据，借助大型语言模型的强大功能，显著提升了性能。经过广泛的实验验证，我们的模型在情感分类、情感推理以及幽默理解方面展现了卓越的能力。这项比较分析为LLM时代的Emotion Visual Instruction Tuning提供了坚实的基准，并为未来在该领域的研究提供了宝贵的洞见和探索途径。相关代码已在 \url{https://github.com/aimmemotion/EmoVIT} 上公开。

> Visual Instruction Tuning represents a novel learning paradigm involving the fine-tuning of pre-trained language models using task-specific instructions. This paradigm shows promising zero-shot results in various natural language processing tasks but is still unexplored in vision emotion understanding. In this work, we focus on enhancing the model's proficiency in understanding and adhering to instructions related to emotional contexts. Initially, we identify key visual clues critical to visual emotion recognition. Subsequently, we introduce a novel GPT-assisted pipeline for generating emotion visual instruction data, effectively addressing the scarcity of annotated instruction data in this domain. Expanding on the groundwork established by InstructBLIP, our proposed EmoVIT architecture incorporates emotion-specific instruction data, leveraging the powerful capabilities of Large Language Models to enhance performance. Through extensive experiments, our model showcases its proficiency in emotion classification, adeptness in affective reasoning, and competence in comprehending humor. The comparative analysis provides a robust benchmark for Emotion Visual Instruction Tuning in the era of LLMs, providing valuable insights and opening avenues for future exploration in this domain. Our code is available at \url{https://github.com/aimmemotion/EmoVIT}.

[Arxiv](https://arxiv.org/abs/2404.16670)