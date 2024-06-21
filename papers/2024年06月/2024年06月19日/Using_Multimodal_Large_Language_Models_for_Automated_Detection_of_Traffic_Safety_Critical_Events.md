# 借助多模态大型语言模型，自动识别交通中的安全关键事件

发布时间：2024年06月19日

`Agent

理由：这篇论文主要探讨了如何利用多模态大型语言模型（MLLMs）来分析驾驶视频中的安全事件，通过融合文本、视觉和音频信息，以及使用针对性的上下文提示来提高危险检测的准确性和可靠性。这种方法涉及到自主系统的安全分析，强调了模型的推理能力和在复杂环境中的交互理解，这些都是Agent系统的关键特性。因此，这篇论文更适合归类于Agent分类，因为它关注的是如何构建和应用智能代理来处理特定的任务，即驾驶视频中的安全事件分析。` `自动驾驶` `安全监控`

> Using Multimodal Large Language Models for Automated Detection of Traffic Safety Critical Events

# 摘要

> 传统上，自主系统的安全事件分析依赖于复杂的机器学习模型和大量数据，以确保高精度和可靠性。多模态大型语言模型（MLLMs）的兴起，通过融合文本、视觉和音频信息，为驾驶视频的自动化分析开辟了新途径。我们的框架运用MLLMs的强大推理能力，并通过针对性的上下文提示，确保为危险检测提供精准、可靠且实用的洞察。结合Gemini-Pro-Vision 1.5和Llava等模型，我们的方法旨在自动处理关键安全事件，并解决MLLM输出中常见的幻觉问题。初步结果表明，该框架在零样本学习和场景分析方面具有潜力，但仍需在更大数据集上进行验证。此外，还需进一步研究，以探索通过少量样本学习和模型微调来提升框架性能的可能性。此研究凸显了MLLMs在提升自然驾驶视频中关键安全事件检测和复杂环境交互理解方面的重要作用。

> Traditional approaches to safety event analysis in autonomous systems have relied on complex machine learning models and extensive datasets for high accuracy and reliability. However, the advent of Multimodal Large Language Models (MLLMs) offers a novel approach by integrating textual, visual, and audio modalities, thereby providing automated analyses of driving videos. Our framework leverages the reasoning power of MLLMs, directing their output through context-specific prompts to ensure accurate, reliable, and actionable insights for hazard detection. By incorporating models like Gemini-Pro-Vision 1.5 and Llava, our methodology aims to automate the safety critical events and mitigate common issues such as hallucinations in MLLM outputs. Preliminary results demonstrate the framework's potential in zero-shot learning and accurate scenario analysis, though further validation on larger datasets is necessary. Furthermore, more investigations are required to explore the performance enhancements of the proposed framework through few-shot learning and fine-tuned models. This research underscores the significance of MLLMs in advancing the analysis of the naturalistic driving videos by improving safety-critical event detecting and understanding the interaction with complex environments.

[Arxiv](https://arxiv.org/abs/2406.13894)