# 绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。

发布时间：2024年03月29日

`LLM应用` `人工智能` `多模态交互`

> Draw-and-Understand: Leveraging Visual Prompts to Enable MLLMs to Comprehend What You Want

# 摘要

> 人与AI的互动是衡量多模态大型语言模型（MLLMs）成效的关键。然而，现行MLLMs过于侧重图像理解，互动仅限于文字指令，这限制了它们的应用灵活性和回应深度。本文提出了Draw-and-Understand项目，这是一个创新的模型、多领域数据集和视觉提示的挑战性基准。我们推出了SPHINX-V，一个全新的端到端训练的MLLM，它整合了视觉编码器、视觉提示编码器和LLM，以处理各种视觉提示（如点、边界框和自由形状）和语言理解任务。为推动MLLMs在视觉提示研究上的进步，我们引入了MDVP-Data和MDVP-Bench。MDVP-Data包含1.6M个独特的图像-视觉提示-文本指令样本，覆盖自然图像、文档图像、OCR图像、移动和网页截图以及多面板图像。MDVP-Bench则是一个全面的挑战性基准，用以评估模型对视觉提示的理解能力。实验表明，SPHINX-V在视觉提示方面的多模态互动表现出色，显著提升了细节描述和问答能力。

> The interaction between humans and artificial intelligence (AI) is a crucial factor that reflects the effectiveness of multimodal large language models (MLLMs). However, current MLLMs primarily focus on image-level comprehension and limit interaction to textual instructions, thereby constraining their flexibility in usage and depth of response. In this paper, we introduce the Draw-and-Understand project: a new model, a multi-domain dataset, and a challenging benchmark for visual prompting. Specifically, we propose SPHINX-V, a new end-to-end trained Multimodal Large Language Model (MLLM) that connects a vision encoder, a visual prompt encoder and an LLM for various visual prompts (points, bounding boxes, and free-form shape) and language understanding. To advance visual prompting research for MLLMs, we introduce MDVP-Data and MDVP-Bench. MDVP-Data features a multi-domain dataset containing 1.6M unique image-visual prompt-text instruction-following samples, including natural images, document images, OCR images, mobile screenshots, web screenshots, and multi-panel images. Furthermore, we present MDVP-Bench, a comprehensive and challenging benchmark to assess a model's capability in understanding visual prompting instructions. Our experiments demonstrate SPHINX-V's impressive multimodal interaction capabilities through visual prompting, revealing significant improvements in detailed pixel-level description and question-answering abilities.

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/x1.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/func.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/x2.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/x3.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/visual-samples.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/x5.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/x6.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/x7.png)

![绘图理解：通过视觉提示，让混合多模态大型语言模型（MLLMs）明白你的意图。](../../../paper_images/2403.20271/x8.png)

[Arxiv](https://arxiv.org/abs/2403.20271)