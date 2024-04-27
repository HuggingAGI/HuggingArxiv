# 多模态的大型语言模型，作为文本到图像生成任务的人类对齐注释器，展现出了其独特的价值。

发布时间：2024年04月23日

`LLM应用` `图像生成` `人工智能`

> Multimodal Large Language Model is a Human-Aligned Annotator for Text-to-Image Generation

# 摘要

> 最新研究表明，利用人类偏好数据集来优化文本到图像的生成模型，能够显著提升生成图像与文本描述的匹配度。然而，目前这类数据集要么成本过高，要么偏好维度多样性不足，限制了其在开源图像生成模型中的指令微调应用，并影响了进一步的研究。为了解决这些问题，我们开发了 VisionPrefer——一个高质量、细致的偏好数据集，它覆盖了多个偏好维度。我们通过 AI 标注员在四个维度——遵循提示、审美、忠实度和无害性——上的反馈，构建了 VisionPrefer。为了证明其有效性，我们基于该数据集训练了一个奖励模型 VP-Score，用以指导图像生成模型的训练，其预测准确度与人类标注员相媲美。我们还采用了两种强化学习方法对生成模型进行监督式微调，并通过大量实验验证了 VisionPrefer 在提升组合图像生成任务中的文本-图像匹配度方面的显著效果，其在不同图像分布上的泛化能力也优于以往的人类偏好评价指标。此外，VisionPrefer 的研究还指出，将 AI 生成的合成数据作为监督信号，是提高视觉生成模型与人类偏好一致性的一个有前景的方向。

> Recent studies have demonstrated the exceptional potentials of leveraging human preference datasets to refine text-to-image generative models, enhancing the alignment between generated images and textual prompts. Despite these advances, current human preference datasets are either prohibitively expensive to construct or suffer from a lack of diversity in preference dimensions, resulting in limited applicability for instruction tuning in open-source text-to-image generative models and hinder further exploration. To address these challenges and promote the alignment of generative models through instruction tuning, we leverage multimodal large language models to create VisionPrefer, a high-quality and fine-grained preference dataset that captures multiple preference aspects. We aggregate feedback from AI annotators across four aspects: prompt-following, aesthetic, fidelity, and harmlessness to construct VisionPrefer. To validate the effectiveness of VisionPrefer, we train a reward model VP-Score over VisionPrefer to guide the training of text-to-image generative models and the preference prediction accuracy of VP-Score is comparable to human annotators. Furthermore, we use two reinforcement learning methods to supervised fine-tune generative models to evaluate the performance of VisionPrefer, and extensive experimental results demonstrate that VisionPrefer significantly improves text-image alignment in compositional image generation across diverse aspects, e.g., aesthetic, and generalizes better than previous human-preference metrics across various image distributions. Moreover, VisionPrefer indicates that the integration of AI-generated synthetic data as a supervisory signal is a promising avenue for achieving improved alignment with human preferences in vision generative models.

[Arxiv](https://arxiv.org/abs/2404.15100)