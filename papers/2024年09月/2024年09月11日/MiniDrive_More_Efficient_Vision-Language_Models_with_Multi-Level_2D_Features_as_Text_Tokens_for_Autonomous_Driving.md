# MiniDrive：利用多层次2D特征作为文本标记，打造更高效的自动驾驶视觉-语言模型

发布时间：2024年09月11日

`LLM应用` `自动驾驶` `计算机视觉`

> MiniDrive: More Efficient Vision-Language Models with Multi-Level 2D Features as Text Tokens for Autonomous Driving

# 摘要

> 视觉-语言模型 (VLM) 在自动驾驶中通过问答交互执行预测、规划和感知等任务。然而，现有方法多依赖于计算密集型的视觉编码器和大型语言模型 (LLM)，难以在现实场景和实时应用中部署。此外，现有 VLM 大多缺乏处理多张图像的能力，难以适应自动驾驶中的多摄像头感知。为此，我们提出了 MiniDrive 框架，结合了特征工程混合专家 (FE-MoE) 模块和动态指令适配器 (DI-Adapter)。FE-MoE 将 2D 特征高效映射为视觉令牌嵌入，而 DI-Adapter 使视觉令牌嵌入随指令文本嵌入动态变化，解决了先前方法中相同图像的静态视觉令牌嵌入问题。与先前工作相比，MiniDrive 在参数大小、浮点运算和响应效率方面表现卓越，最小版本仅包含 83M 参数。

> Vision-language models (VLMs) serve as general-purpose end-to-end models in autonomous driving, performing subtasks such as prediction, planning, and perception through question-and-answer interactions. However, most existing methods rely on computationally expensive visual encoders and large language models (LLMs), making them difficult to deploy in real-world scenarios and real-time applications. Meanwhile, most existing VLMs lack the ability to process multiple images, making it difficult to adapt to multi-camera perception in autonomous driving. To address these issues, we propose a novel framework called MiniDrive, which incorporates our proposed Feature Engineering Mixture of Experts (FE-MoE) module and Dynamic Instruction Adapter (DI-Adapter). The FE-MoE effectively maps 2D features into visual token embeddings before being input into the language model. The DI-Adapter enables the visual token embeddings to dynamically change with the instruction text embeddings, resolving the issue of static visual token embeddings for the same image in previous approaches. Compared to previous works, MiniDrive achieves state-of-the-art performance in terms of parameter size, floating point operations, and response efficiency, with the smallest version containing only 83M parameters.

[Arxiv](https://arxiv.org/abs/2409.07267)