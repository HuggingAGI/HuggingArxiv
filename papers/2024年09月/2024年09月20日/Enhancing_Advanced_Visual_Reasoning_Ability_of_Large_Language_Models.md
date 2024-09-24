# 提升大型语言模型的视觉推理能力

发布时间：2024年09月20日

`LLM应用` `人工智能` `计算机视觉`

> Enhancing Advanced Visual Reasoning Ability of Large Language Models

# 摘要

> 视觉-语言研究的最新进展为复杂视觉推理设定了新标准，考验着模型的推理能力。传统 VLM 在视觉感知上表现优异，但在复杂推理中力不从心。而 LLM 虽擅长文本推理，却缺乏视觉敏锐度。为此，我们提出 CVR-LLM，结合 VLM 的视觉感知与 LLM 的强大推理。不同于需要投影层的多模态模型，我们通过迭代自精炼循环将图像转化为详尽的上下文描述，并利用 LLM 的文本知识进行精准预测，无需额外训练。我们还创新了多模态 ICL 方法，提升 LLM 的上下文理解和推理能力。此外，引入链式比较 (CoC) 技术，逐步对比预测的各个方面。CVR-LLM 在广泛复杂视觉推理任务中首次进行全面研究，并取得了 SOTA 性能。

> Recent advancements in Vision-Language (VL) research have sparked new benchmarks for complex visual reasoning, challenging models' advanced reasoning ability. Traditional Vision-Language Models (VLMs) perform well in visual perception tasks while struggling with complex reasoning scenarios. Conversely, Large Language Models (LLMs) demonstrate robust text reasoning capabilities; however, they lack visual acuity. To bridge this gap, we propose Complex Visual Reasoning Large Language Models (CVR-LLM), capitalizing on VLMs' visual perception proficiency and LLMs' extensive reasoning capability. Unlike recent multimodal large language models (MLLMs) that require a projection layer, our approach transforms images into detailed, context-aware descriptions using an iterative self-refinement loop and leverages LLMs' text knowledge for accurate predictions without extra training. We also introduce a novel multi-modal in-context learning (ICL) methodology to enhance LLMs' contextual understanding and reasoning. Additionally, we introduce Chain-of-Comparison (CoC), a step-by-step comparison technique enabling contrasting various aspects of predictions. Our CVR-LLM presents the first comprehensive study across a wide array of complex visual reasoning tasks and achieves SOTA performance among all.

[Arxiv](https://arxiv.org/abs/2409.13980)