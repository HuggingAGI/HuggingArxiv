# 模糊性的视觉演绎：Winograd Schema Challenge 的新视角

发布时间：2024年05月25日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在多模态环境中的应用，特别是在处理文本和图像结合的任务中的表现。通过介绍WinoVis数据集和评估框架，论文关注的是模型在代词消歧任务上的性能，这是一个具体的应用场景。因此，这篇论文更适合归类于LLM应用，因为它专注于LLM在特定任务中的实际应用和性能评估，而不是理论研究或Agent的设计与实现。` `多模态学习` `数据集构建`

> Picturing Ambiguity: A Visual Twist on the Winograd Schema Challenge

# 摘要

> 大型语言模型（LLMs）在文本常识推理任务中表现出色，但在需要同时处理文本和图像的多模态领域仍面临挑战。为此，我们推出了WinoVis数据集，专门用于评估模型在多模态环境中处理代词消歧的能力。通过GPT-4生成提示和DAAM进行热图分析，我们构建了一个新的评估框架，专注于模型在代词消歧上的表现，而非其他视觉处理任务。尽管Stable Diffusion 2.0在WinoVis上的准确率提升至56.7%，但仍仅略胜于随机猜测。错误分析揭示了未来研究的关键方向，以期提升模型在复杂视觉环境中的理解和交互能力。

> Large Language Models (LLMs) have demonstrated remarkable success in tasks like the Winograd Schema Challenge (WSC), showcasing advanced textual common-sense reasoning. However, applying this reasoning to multimodal domains, where understanding text and images together is essential, remains a substantial challenge. To address this, we introduce WinoVis, a novel dataset specifically designed to probe text-to-image models on pronoun disambiguation within multimodal contexts. Utilizing GPT-4 for prompt generation and Diffusion Attentive Attribution Maps (DAAM) for heatmap analysis, we propose a novel evaluation framework that isolates the models' ability in pronoun disambiguation from other visual processing challenges. Evaluation of successive model versions reveals that, despite incremental advancements, Stable Diffusion 2.0 achieves a precision of 56.7% on WinoVis, only marginally surpassing random guessing. Further error analysis identifies important areas for future research aimed at advancing text-to-image models in their ability to interpret and interact with the complex visual world.

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/x1.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/gen-overview.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/x2.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/bees.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/scarecrow_archaeologist.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/thresholds.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/skinny_confusion_matrices.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/small_pie.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/side_by_side.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/corpus_construction.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/captioning.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/horse.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/cat.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/wolf.png)

![模糊性的视觉演绎：Winograd Schema Challenge 的新视角](../../../paper_images/2405.16277/SDXL.png)

[Arxiv](https://arxiv.org/abs/2405.16277)