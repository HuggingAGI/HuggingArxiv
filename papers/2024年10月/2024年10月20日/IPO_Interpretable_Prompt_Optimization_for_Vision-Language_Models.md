# IPO：为视觉-语言模型打造的可解释提示优化

发布时间：2024年10月20日

`LLM应用` `计算机视觉`

> IPO: Interpretable Prompt Optimization for Vision-Language Models

# 摘要

> 预训练的视觉-语言模型如 CLIP 在下游任务中表现出色，但其性能高度依赖于输入文本提示的特异性，这需要精心的提示模板设计。当前的提示优化方法通过梯度下降学习提示，但往往导致过拟合和生成的提示难以理解。本文提出了一种简单且可解释的提示优化器 (IPO)，利用大型语言模型 (LLM) 动态生成文本提示。我们设计了一个提示优化提示，不仅指导 LLM 创建有效提示，还存储了过去提示及其性能指标，提供丰富的上下文信息。此外，我们引入大型多模态模型 (LMM) 生成图像描述，增强文本与视觉模态的交互。这使得 IPO 能够创建特定于数据集的提示，提高泛化性能，同时保持人类理解。在 11 个数据集上的测试表明，IPO 不仅提升了现有基于梯度下降的提示学习方法的准确性，还显著增强了生成提示的可解释性。通过利用 LLM 的优势，我们的方法确保提示保持人类可理解，从而为视觉-语言模型提供更好的透明度和监督。

> Pre-trained vision-language models like CLIP have remarkably adapted to various downstream tasks. Nonetheless, their performance heavily depends on the specificity of the input text prompts, which requires skillful prompt template engineering. Instead, current approaches to prompt optimization learn the prompts through gradient descent, where the prompts are treated as adjustable parameters. However, these methods tend to lead to overfitting of the base classes seen during training and produce prompts that are no longer understandable by humans. This paper introduces a simple but interpretable prompt optimizer (IPO), that utilizes large language models (LLMs) to generate textual prompts dynamically. We introduce a Prompt Optimization Prompt that not only guides LLMs in creating effective prompts but also stores past prompts with their performance metrics, providing rich in-context information. Additionally, we incorporate a large multimodal model (LMM) to condition on visual content by generating image descriptions, which enhance the interaction between textual and visual modalities. This allows for thae creation of dataset-specific prompts that improve generalization performance, while maintaining human comprehension. Extensive testing across 11 datasets reveals that IPO not only improves the accuracy of existing gradient-descent-based prompt learning methods but also considerably enhances the interpretability of the generated prompts. By leveraging the strengths of LLMs, our approach ensures that the prompts remain human-understandable, thereby facilitating better transparency and oversight for vision-language models.

[Arxiv](https://arxiv.org/abs/2410.15397)