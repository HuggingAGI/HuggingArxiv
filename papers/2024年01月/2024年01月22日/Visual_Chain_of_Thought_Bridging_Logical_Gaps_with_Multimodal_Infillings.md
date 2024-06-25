# 视觉思维链：借助多模态填充，弥合逻辑鸿沟

发布时间：2024年01月22日

`LLM应用

这篇论文介绍了一种新的方法VCoT，它结合了视觉元素和语言模型的链式思维提示，以提升多步骤推理能力。这种方法特别适用于需要视觉和语言结合的复杂任务，如视觉故事讲述和WikiHow摘要。因此，它属于大型语言模型（LLM）的应用范畴，因为它展示了如何将LLM技术应用于特定的多模态任务中，以提高模型的性能和透明度。` `多媒体内容创作`

> Visual Chain of Thought: Bridging Logical Gaps with Multimodal Infillings

# 摘要

> 大型语言模型的最新进展使得模型能够以人类般的链式思维分解问题，从而提升多步骤推理能力。然而，这种单一模态的方法主要局限于问答任务。我们认为，将视觉元素融入推理对于处理复杂、富有想象力的任务至关重要。因此，我们开发了VCoT，一种结合视觉-语言基础的链式思维提示的新方法，旨在递归地填补序列数据中的逻辑断层。通过视觉引导，VCoT生成连贯且创新的多模态信息，有效缩小了时间推理相关下游任务的逻辑鸿沟，并增强了模型多步骤推理的透明度。在视觉故事讲述和WikiHow摘要数据集上的应用表明，VCoT通过人类评估提供的合成数据增强不仅新颖且一致，显著优于传统链式思维方法，有力提升了下游任务的表现。

> Recent advances in large language models elicit reasoning in a chain-of-thought that allows models to decompose problems in a human-like fashion. Though this paradigm improves multi-step reasoning ability in language models, it is limited by being unimodal and applied mainly to question-answering tasks. We claim that incorporating visual augmentation into reasoning is essential, especially for complex, imaginative tasks. Consequently, we introduce VCoT, a novel method that leverages chain-of-thought prompting with vision-language grounding to recursively bridge the logical gaps within sequential data. Our method uses visual guidance to generate synthetic multimodal infillings that add consistent and novel information to reduce the logical gaps for downstream tasks that can benefit from temporal reasoning, as well as provide interpretability into models' multi-step reasoning. We apply VCoT to the Visual Storytelling and WikiHow summarization datasets and demonstrate through human evaluation that VCoT offers novel and consistent synthetic data augmentation beating chain-of-thought baselines, which can be used to enhance downstream performance.

[Arxiv](https://arxiv.org/abs/2305.02317)