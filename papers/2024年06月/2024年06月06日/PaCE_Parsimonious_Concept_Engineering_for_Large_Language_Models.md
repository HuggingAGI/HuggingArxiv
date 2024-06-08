# PaCE：大型语言模型的精简概念工程

发布时间：2024年06月06日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的对齐问题，并提出了一种新的激活工程框架——简约概念工程（PaCE）。该框架通过构建激活空间概念字典和利用概念分区器来精确地标记和处理良性与不良概念，从而在保持语言表达力的同时，提升LLMs的对齐效果。这种研究属于LLM理论范畴，因为它专注于改进和理解LLMs内部的工作机制，以及如何通过技术手段优化其性能和行为。` `人工智能`

> PaCE: Parsimonious Concept Engineering for Large Language Models

# 摘要

> 大型语言模型（LLMs）在众多任务中大显身手，既能生成逼真的人类语言，也可能输出有害信息、歧视性言论或无中生有的内容。对齐技术如微调、提示设计和表示优化旨在减少这些不良输出，但现有方法各有短板：有的需为每个对齐任务付出高昂的微调成本；有的未能彻底清除不良概念，对齐效果不佳；还有的误伤良性概念，削弱了LLMs的语言表达力。为此，我们创新性地提出了简约概念工程（PaCE），一种针对对齐的新型激活工程框架。首先，我们构建了一个庞大的激活空间概念字典，确保每个原子精准映射到语义概念。接着，针对任何对齐任务，我们利用概念分区器高效标记概念为良性或不良。在推理阶段，我们通过稀疏编码，依据概念字典分解LLM激活，精确地将激活表达为良性与不良成分的线性组合。移除不良成分后，我们引导LLMs的行为更符合对齐目标。实验证明，PaCE在响应净化、忠诚度提升和情感修正等任务中，不仅实现了顶尖的对齐效果，还保持了LLMs的语言表达力。

> Large Language Models (LLMs) are being used for a wide variety of tasks. While they are capable of generating human-like responses, they can also produce undesirable output including potentially harmful information, racist or sexist language, and hallucinations. Alignment methods are designed to reduce such undesirable output, via techniques such as fine-tuning, prompt engineering, and representation engineering. However, existing methods face several challenges: some require costly fine-tuning for every alignment task; some do not adequately remove undesirable concepts, failing alignment; some remove benign concepts, lowering the linguistic capabilities of LLMs. To address these issues, we propose Parsimonious Concept Engineering (PaCE), a novel activation engineering framework for alignment. First, to sufficiently model the concepts, we construct a large-scale concept dictionary in the activation space, in which each atom corresponds to a semantic concept. Then, given any alignment task, we instruct a concept partitioner to efficiently annotate the concepts as benign or undesirable. Finally, at inference time, we decompose the LLM activations along the concept dictionary via sparse coding, to accurately represent the activation as a linear combination of the benign and undesirable components. By removing the latter ones from the activation, we reorient the behavior of LLMs towards alignment goals. We conduct experiments on tasks such as response detoxification, faithfulness enhancement, and sentiment revising, and show that PaCE achieves state-of-the-art alignment performance while maintaining linguistic capabilities.

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x1.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x2.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x3.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x4.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x5.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x6.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x7.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x8.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x9.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x10.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x11.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x12.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x13.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x14.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x15.png)

![PaCE：大型语言模型的精简概念工程](../../../paper_images/2406.04331/x16.png)

[Arxiv](https://arxiv.org/abs/2406.04331)