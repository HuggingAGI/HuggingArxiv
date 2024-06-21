# 借助多模态大型语言模型，自动识别交通中的安全关键事件

发布时间：2024年06月19日

`Agent

理由：这篇论文主要探讨了如何利用多模态大型语言模型（MLLMs）来分析驾驶视频中的安全事件，通过特定的上下文提示引导模型输出，以实现对危险检测的自动化分析。这种方法涉及到了模型的自主推理和决策能力，因此更符合Agent分类，即关注于模型作为自主系统在特定任务中的应用和表现。虽然文中也提到了MLLMs的应用，但核心在于模型的自主性和对环境的交互理解，这更偏向于Agent的定义。` `自动驾驶` `安全监控`

> Using Multimodal Large Language Models for Automated Detection of Traffic Safety Critical Events

# 摘要

> 传统上，自主系统的安全事件分析依赖于复杂的机器学习模型和庞大的数据集以确保高精度和可靠性。多模态大型语言模型（MLLMs）的兴起，通过融合文本、视觉和音频信息，为驾驶视频的自动化分析开辟了新途径。我们的框架借助MLLMs的强大推理能力，并通过特定上下文的提示精确引导其输出，以确保对危险检测的见解既准确又实用。结合Gemini-Pro-Vision 1.5和Llava等模型，我们的方法旨在自动化处理关键安全事件，并解决MLLM输出中常见的幻觉问题。初步结果表明，该框架在零样本学习和场景分析方面展现出潜力，但仍需在更大数据集上进行验证。此外，通过少量样本学习和模型微调来进一步提升框架性能的研究也亟待开展。此研究凸显了MLLMs在提升自然驾驶视频中关键安全事件检测和复杂环境交互理解方面的重要作用。

> Traditional approaches to safety event analysis in autonomous systems have relied on complex machine learning models and extensive datasets for high accuracy and reliability. However, the advent of Multimodal Large Language Models (MLLMs) offers a novel approach by integrating textual, visual, and audio modalities, thereby providing automated analyses of driving videos. Our framework leverages the reasoning power of MLLMs, directing their output through context-specific prompts to ensure accurate, reliable, and actionable insights for hazard detection. By incorporating models like Gemini-Pro-Vision 1.5 and Llava, our methodology aims to automate the safety critical events and mitigate common issues such as hallucinations in MLLM outputs. Preliminary results demonstrate the framework's potential in zero-shot learning and accurate scenario analysis, though further validation on larger datasets is necessary. Furthermore, more investigations are required to explore the performance enhancements of the proposed framework through few-shot learning and fine-tuned models. This research underscores the significance of MLLMs in advancing the analysis of the naturalistic driving videos by improving safety-critical event detecting and understanding the interaction with complex environments.

[Arxiv](https://arxiv.org/abs/2406.13894)