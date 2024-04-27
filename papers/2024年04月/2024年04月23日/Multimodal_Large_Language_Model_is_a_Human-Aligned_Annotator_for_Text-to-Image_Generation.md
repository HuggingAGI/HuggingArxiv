# 多模态大型语言模型，作为文本到图像生成任务中的人类对齐注释器，展现出卓越的性能。

发布时间：2024年04月23日

`LLM应用` `图像生成` `人工智能`

> Multimodal Large Language Model is a Human-Aligned Annotator for Text-to-Image Generation

# 摘要

> 最新研究表明，通过利用人类偏好数据集来优化文本到图像的生成模型，可以显著提升生成图像与文本描述的匹配度。然而，目前构建这样的数据集要么成本过高，要么偏好维度的多样性不足，这限制了其在开源文本到图像生成模型中的指令调优应用，并影响了进一步的研究。为了解决这些问题，我们运用多模态大型语言模型，开发了 VisionPrefer——一个捕捉多元偏好维度的高质量、细致入微的偏好数据集。我们汇总了 AI 注释者在四个方面——遵循提示、审美、忠实度和无害性——的反馈，构建了 VisionPrefer。为了证明其有效性，我们基于该数据集训练了一个奖励模型 VP-Score，用以指导文本到图像生成模型的训练，其偏好预测的准确度与人类注释者不相上下。此外，我们采用两种强化学习方法对生成模型进行监督微调，并使用 VisionPrefer 进行性能评估，广泛的实验结果显示，VisionPrefer 在多样化维度上显著提升了文本与图像的一致性，比如审美，并在不同图像分布上比以往的人类偏好指标更具泛化能力。更重要的是，VisionPrefer 的研究指出，将 AI 生成的合成数据作为监督信号，是提高视觉生成模型与人类偏好一致性的一个充满希望的方向。

> Recent studies have demonstrated the exceptional potentials of leveraging human preference datasets to refine text-to-image generative models, enhancing the alignment between generated images and textual prompts. Despite these advances, current human preference datasets are either prohibitively expensive to construct or suffer from a lack of diversity in preference dimensions, resulting in limited applicability for instruction tuning in open-source text-to-image generative models and hinder further exploration. To address these challenges and promote the alignment of generative models through instruction tuning, we leverage multimodal large language models to create VisionPrefer, a high-quality and fine-grained preference dataset that captures multiple preference aspects. We aggregate feedback from AI annotators across four aspects: prompt-following, aesthetic, fidelity, and harmlessness to construct VisionPrefer. To validate the effectiveness of VisionPrefer, we train a reward model VP-Score over VisionPrefer to guide the training of text-to-image generative models and the preference prediction accuracy of VP-Score is comparable to human annotators. Furthermore, we use two reinforcement learning methods to supervised fine-tune generative models to evaluate the performance of VisionPrefer, and extensive experimental results demonstrate that VisionPrefer significantly improves text-image alignment in compositional image generation across diverse aspects, e.g., aesthetic, and generalizes better than previous human-preference metrics across various image distributions. Moreover, VisionPrefer indicates that the integration of AI-generated synthetic data as a supervisory signal is a promising avenue for achieving improved alignment with human preferences in vision generative models.

[Arxiv](https://arxiv.org/abs/2404.15100)