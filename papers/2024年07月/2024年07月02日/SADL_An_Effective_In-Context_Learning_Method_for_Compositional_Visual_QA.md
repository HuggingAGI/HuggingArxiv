# SADL：组合视觉问答中一种高效的上下文学习策略

发布时间：2024年07月02日

`LLM应用` `计算机视觉` `人工智能`

> SADL: An Effective In-Context Learning Method for Compositional Visual QA

# 摘要

> 大型视觉-语言模型（LVLMs）在视觉问答（Visual QA）中展现了一种创新的上下文学习能力。通过少量图像-问题-答案三元组的演示，LVLMs能够识别潜在模式，并将这些隐性知识应用于回答未见图像的新问题，无需昂贵的监督微调。然而，设计针对组合性问题的有效视觉-语言提示仍是一个挑战。由于视觉内容与语言结构存在差异，仅依赖语言的ICL技术可能不适用。为此，本文提出了SADL，一个结合采样、深思和伪标签的视觉-语言提示框架。该框架通过从训练数据中选取语义相近的图像-问题对，分解复杂问题为子问题，并逐步生成伪标签，以应对视觉问答任务。在OpenFlamingo平台上对GQA、GQA-OOD、CLEVR和CRIC等数据集的实验表明，采样、问题分解和标签配对是关键因素。这些发现为视觉-语言领域的ICL提供了新的视角。

> Large vision-language models (LVLMs) offer a novel capability for performing in-context learning (ICL) in Visual QA. When prompted with a few demonstrations of image-question-answer triplets, LVLMs have demonstrated the ability to discern underlying patterns and transfer this latent knowledge to answer new questions about unseen images without the need for expensive supervised fine-tuning. However, designing effective vision-language prompts, especially for compositional questions, remains poorly understood. Adapting language-only ICL techniques may not necessarily work because we need to bridge the visual-linguistic semantic gap: Symbolic concepts must be grounded in visual content, which does not share the syntactic linguistic structures. This paper introduces SADL, a new visual-linguistic prompting framework for the task. SADL revolves around three key components: SAmpling, Deliberation, and Pseudo-Labeling of image-question pairs. Given an image-question query, we sample image-question pairs from the training data that are in semantic proximity to the query. To address the compositional nature of questions, the deliberation step decomposes complex questions into a sequence of subquestions. Finally, the sequence is progressively annotated one subquestion at a time to generate a sequence of pseudo-labels. We investigate the behaviors of SADL under OpenFlamingo on large-scale Visual QA datasets, namely GQA, GQA-OOD, CLEVR, and CRIC. The evaluation demonstrates the critical roles of sampling in the neighborhood of the image, the decomposition of complex questions, and the accurate pairing of the subquestions and labels. These findings do not always align with those found in language-only ICL, suggesting fresh insights in vision-language settings.

[Arxiv](https://arxiv.org/abs/2407.01983)