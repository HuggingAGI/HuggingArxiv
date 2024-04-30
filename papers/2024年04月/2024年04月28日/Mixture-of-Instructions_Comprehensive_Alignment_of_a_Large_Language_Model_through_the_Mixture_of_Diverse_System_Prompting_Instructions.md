# 通过多样化的系统提示指令混合，实现对大型语言模型的全面校准。

发布时间：2024年04月28日

`LLM应用` `人工智能` `多任务学习`

> Mixture-of-Instructions: Comprehensive Alignment of a Large Language Model through the Mixture of Diverse System Prompting Instructions

# 摘要

> 大型语言模型（LLMs）的广泛使用催生了对这些模型在多样化任务中进行综合对齐的研究需求。目前，主流的对齐技术多聚焦于单一任务，比如多轮对话、编程、数学问题求解和工具应用等。但在现实世界的应用场景中，AI产品往往需要整合这些不同的能力来实现高效运作。此外，为了实现LLMs的精准对齐，所需的庞大计算资源也凸显了开发一种更为强大、高效且全面的多任务对齐方法的必要性，以提升模型的生成性能。面对这些挑战，我们提出了一种创新技术——指令混合（MoI），它通过指令串联和多样化的系统提示来增强语言模型的对齐效率。我们还特别设计了包含七个不同基准数据集的集合，用以严格测试MoI增强模型的对齐效果。该技术被应用于开源的Qwen-7B-chat模型，进而发展出了Qwen-SFT-MoI模型。这一增强版模型在编程、数学和工具使用等多个任务上展现了显著的生成能力提升。

> With the proliferation of large language models (LLMs), the comprehensive alignment of such models across multiple tasks has emerged as a critical area of research. Existing alignment methodologies primarily address single task, such as multi-turn dialogue, coding, mathematical problem-solving, and tool usage. However, AI-driven products that leverage language models usually necessitate a fusion of these abilities to function effectively in real-world scenarios. Moreover, the considerable computational resources required for proper alignment of LLMs underscore the need for a more robust, efficient, and encompassing approach to multi-task alignment, ensuring improved generative performance. In response to these challenges, we introduce a novel technique termed Mixture-of-Instructions (MoI), which employs a strategy of instruction concatenation combined with diverse system prompts to boost the alignment efficiency of language models. We have also compiled a diverse set of seven benchmark datasets to rigorously evaluate the alignment efficacy of the MoI-enhanced language model. Our methodology was applied to the open-source Qwen-7B-chat model, culminating in the development of Qwen-SFT-MoI. This enhanced model demonstrates significant advancements in generative capabilities across coding, mathematics, and tool use tasks.

[Arxiv](https://arxiv.org/abs/2404.18410)