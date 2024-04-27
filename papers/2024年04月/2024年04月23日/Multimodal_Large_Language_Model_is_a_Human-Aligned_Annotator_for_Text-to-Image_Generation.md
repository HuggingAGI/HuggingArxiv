# 多模态的大型语言模型，作为文本到图像生成任务的人类对齐注释器，展现出了其独特的价值。

发布时间：2024年04月23日

`LLM应用` `图像生成` `人工智能`

> Multimodal Large Language Model is a Human-Aligned Annotator for Text-to-Image Generation

# 摘要

> 最新研究表明，通过利用人类偏好数据集，可以显著提升文本到图像的生成模型，使得生成的图像与文本描述更加匹配。然而，目前构建这样的数据集要么成本过高，要么偏好维度的多样性不足，这限制了它们在开源文本到图像生成模型中的指令调整应用，并阻碍了进一步的研究。为了解决这些问题，我们采用了多模态大型语言模型，开发了 VisionPrefer——一个捕捉多种偏好维度的高质量、细致的偏好数据集。我们汇集了 AI 标注员在四个维度——遵循提示、审美、忠实度和无害性——上的反馈，构建了 VisionPrefer。为了证明其有效性，我们基于该数据集训练了一个奖励模型 VP-Score，用以引导文本到图像生成模型的训练，其预测的准确性与人类标注员相当。此外，我们还采用了两种强化学习方法对生成模型进行监督微调，并验证了 VisionPrefer 的性能，实验结果表明，VisionPrefer 在多样化的组合图像生成任务中显著提升了文本与图像的匹配度，并且在不同图像分布上的泛化能力优于以往的人类偏好指标。更重要的是，VisionPrefer 的研究揭示了将 AI 生成的合成数据作为监督信号，是提高视觉生成模型与人类偏好一致性的一个有前景的方向。

> Recent studies have demonstrated the exceptional potentials of leveraging human preference datasets to refine text-to-image generative models, enhancing the alignment between generated images and textual prompts. Despite these advances, current human preference datasets are either prohibitively expensive to construct or suffer from a lack of diversity in preference dimensions, resulting in limited applicability for instruction tuning in open-source text-to-image generative models and hinder further exploration. To address these challenges and promote the alignment of generative models through instruction tuning, we leverage multimodal large language models to create VisionPrefer, a high-quality and fine-grained preference dataset that captures multiple preference aspects. We aggregate feedback from AI annotators across four aspects: prompt-following, aesthetic, fidelity, and harmlessness to construct VisionPrefer. To validate the effectiveness of VisionPrefer, we train a reward model VP-Score over VisionPrefer to guide the training of text-to-image generative models and the preference prediction accuracy of VP-Score is comparable to human annotators. Furthermore, we use two reinforcement learning methods to supervised fine-tune generative models to evaluate the performance of VisionPrefer, and extensive experimental results demonstrate that VisionPrefer significantly improves text-image alignment in compositional image generation across diverse aspects, e.g., aesthetic, and generalizes better than previous human-preference metrics across various image distributions. Moreover, VisionPrefer indicates that the integration of AI-generated synthetic data as a supervisory signal is a promising avenue for achieving improved alignment with human preferences in vision generative models.

[Arxiv](https://arxiv.org/abs/2404.15100)