# 多模态大型语言模型，作为文本到图像生成任务的人类对齐注释器，展现出卓越的性能。

发布时间：2024年04月23日

`分类：LLM应用

这篇论文主要讨论了如何通过利用人类偏好数据集来提升文本到图像的生成模型，使其生成的图像与文本描述更加匹配。它提出了一个名为 VisionPrefer 的高质量偏好数据集，并使用该数据集训练了一个奖励模型 VP-Score，以指导图像生成模型的训练并提高其预测准确度。此外，论文还探讨了将 AI 合成数据作为监督信号整合进模型的方法。这些内容都与大型语言模型（LLM）的应用相关，因此将其归类为 LLM应用。` `图像生成` `人工智能`

> Multimodal Large Language Model is a Human-Aligned Annotator for Text-to-Image Generation

# 摘要

> 最新研究表明，通过利用人类偏好数据集，我们可以显著提升文本到图像的生成模型，使得生成的图像与文本描述更加匹配。然而，现有的人类偏好数据集要么成本过高，要么偏好维度单一，这限制了它们在开源图像生成模型中的调优应用，并影响了进一步的研究。为了解决这些问题，我们开发了 VisionPrefer——一个细致入微、高质量的偏好数据集，它覆盖了多个偏好维度。我们综合了 AI 注释者在遵循提示、审美、保真度和无害性四个方面的反馈来构建此数据集。通过在 VisionPrefer 上训练奖励模型 VP-Score，我们不仅指导了图像生成模型的训练，还确保了其预测准确度与人类注释者相媲美。我们还采用了两种强化学习方法对模型进行监督微调，实验结果证明 VisionPrefer 在提升图像生成的文本图像一致性方面取得了显著成效，无论是在审美还是其他多样化方面，都显示出比以往人类偏好指标更好的泛化能力。此外，VisionPrefer 还指出，将 AI 合成数据作为监督信号整合进模型，是实现与人类偏好更高度一致性的有前景的方法。

> Recent studies have demonstrated the exceptional potentials of leveraging human preference datasets to refine text-to-image generative models, enhancing the alignment between generated images and textual prompts. Despite these advances, current human preference datasets are either prohibitively expensive to construct or suffer from a lack of diversity in preference dimensions, resulting in limited applicability for instruction tuning in open-source text-to-image generative models and hinder further exploration. To address these challenges and promote the alignment of generative models through instruction tuning, we leverage multimodal large language models to create VisionPrefer, a high-quality and fine-grained preference dataset that captures multiple preference aspects. We aggregate feedback from AI annotators across four aspects: prompt-following, aesthetic, fidelity, and harmlessness to construct VisionPrefer. To validate the effectiveness of VisionPrefer, we train a reward model VP-Score over VisionPrefer to guide the training of text-to-image generative models and the preference prediction accuracy of VP-Score is comparable to human annotators. Furthermore, we use two reinforcement learning methods to supervised fine-tune generative models to evaluate the performance of VisionPrefer, and extensive experimental results demonstrate that VisionPrefer significantly improves text-image alignment in compositional image generation across diverse aspects, e.g., aesthetic, and generalizes better than previous human-preference metrics across various image distributions. Moreover, VisionPrefer indicates that the integration of AI-generated synthetic data as a supervisory signal is a promising avenue for achieving improved alignment with human preferences in vision generative models.

[Arxiv](https://arxiv.org/abs/2404.15100)