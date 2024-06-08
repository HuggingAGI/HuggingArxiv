# 倾听我，观察我，理解我：视听自闭症行为识别

发布时间：2024年03月22日

`Agent

理由：这篇论文主要关注的是利用多模态数据（音频和视觉）来识别自闭症相关行为，这是一个具体的应用场景，其中涉及到创建数据集、使用基础模型和多模态大型语言模型来提升识别准确性。这个任务可以被视为一个智能Agent的行为识别和分析，因此归类为Agent。虽然论文中提到了多模态大型语言模型的应用，但这主要是为了解决特定的识别问题，而不是专注于LLM的理论研究或应用开发，因此不适合归类为LLM应用或LLM理论。同时，该论文并未涉及RAG（Retrieval-Augmented Generation）的相关内容，因此也不适合归类为RAG。` `自闭症筛查` `多模态识别`

> Hear Me, See Me, Understand Me: Audio-Visual Autism Behavior Recognition

# 摘要

> 本文创新性地提出了视听自闭症行为识别问题，特别强调了社交行为识别，这一关键环节在以往的AI辅助自闭症筛查研究中常被忽略。我们定义此任务为利用音频和视觉线索，包括音频中的言语，来识别自闭症相关行为。为此，我们创建了目前最大的视听自闭症谱系数据集（AV-ASD），覆盖了广泛的社交沟通和互动相关行为。为了推动这一领域的研究，我们深入研究了如何利用基础模型和多模态大型语言模型。实验结果显示，整合音频、视觉和言语模态能显著提升自闭症行为识别的准确性。我们还探索了在多模态模型中应用事后到即席的策略，以增强模型在自闭症行为识别中的解释力。我们计划公开数据集、代码及预训练模型，以促进更多研究。

> In this article, we introduce a novel problem of audio-visual autism behavior recognition, which includes social behavior recognition, an essential aspect previously omitted in AI-assisted autism screening research. We define the task at hand as one that is audio-visual autism behavior recognition, which uses audio and visual cues, including any speech present in the audio, to recognize autism-related behaviors. To facilitate this new research direction, we collected an audio-visual autism spectrum dataset (AV-ASD), currently the largest video dataset for autism screening using a behavioral approach. It covers an extensive range of autism-associated behaviors, including those related to social communication and interaction. To pave the way for further research on this new problem, we intensively explored leveraging foundation models and multimodal large language models across different modalities. Our experiments on the AV-ASD dataset demonstrate that integrating audio, visual, and speech modalities significantly enhances the performance in autism behavior recognition. Additionally, we explored the use of a post-hoc to ad-hoc pipeline in a multimodal large language model to investigate its potential to augment the model's explanatory capability during autism behavior recognition. We will release our dataset, code, and pre-trained models.

[Arxiv](https://arxiv.org/abs/2406.02554)