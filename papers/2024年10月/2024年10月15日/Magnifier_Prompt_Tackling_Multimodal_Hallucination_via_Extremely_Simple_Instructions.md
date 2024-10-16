# 放大镜提示：用极简指令攻克多模态幻觉难题

发布时间：2024年10月15日

`LLM应用` `人工智能` `计算机视觉`

> Magnifier Prompt: Tackling Multimodal Hallucination via Extremely Simple Instructions

# 摘要

> 多模态大型语言模型 (MLLM) 中的幻觉问题限制了其应用。为此，我们提出了 Magnifier Prompt (MagPrompt)，一种通过简单指令有效解决幻觉问题的方法。MagPrompt 基于两个核心原则：(1) 模型应更关注图像；(2) 当图像与模型知识冲突时，优先考虑图像。MagPrompt 无需训练，适用于 GPT-4o 和 Gemini-pro 等模型，在多个数据集上表现优异，效果甚至优于 VCD 等复杂方法。我们的设计原则和实验分析为多模态幻觉问题提供了宝贵见解。

> Hallucinations in multimodal large language models (MLLMs) hinder their practical applications. To address this, we propose a Magnifier Prompt (MagPrompt), a simple yet effective method to tackle hallucinations in MLLMs via extremely simple instructions. MagPrompt is based on the following two key principles, which guide the design of various effective prompts, demonstrating robustness: (1) MLLMs should focus more on the image. (2) When there are conflicts between the image and the model's inner knowledge, MLLMs should prioritize the image. MagPrompt is training-free and can be applied to open-source and closed-source models, such as GPT-4o and Gemini-pro. It performs well across many datasets and its effectiveness is comparable or even better than more complex methods like VCD. Furthermore, our prompt design principles and experimental analyses provide valuable insights into multimodal hallucination.

[Arxiv](https://arxiv.org/abs/2410.11701)