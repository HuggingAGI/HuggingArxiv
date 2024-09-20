# TinyVLA：为机器人操作打造快速、数据高效的视觉-语言-动作模型

发布时间：2024年09月19日

`Agent` `机器人` `人工智能`

> TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation

# 摘要

> VLA 模型在视觉运动控制和指令理解方面表现出色，但现有模型推理速度慢且需大量预训练数据，限制了实际应用。为此，我们推出了 TinyVLA 模型，它不仅推理速度更快，还提高了数据效率，无需预训练。通过结合鲁棒的多模态模型和扩散策略解码器，TinyVLA 在模拟和真实机器人测试中均表现优异，速度和数据效率超越了 OpenVLA，且在多种复杂环境下展现出强大的泛化能力。我们的项目详情请访问 https://tiny-vla.github.io。

> Vision-Language-Action (VLA) models have shown remarkable potential in visuomotor control and instruction comprehension through end-to-end learning processes. However, current VLA models face significant challenges: they are slow during inference and require extensive pre-training on large amounts of robotic data, making real-world deployment difficult. In this paper, we introduce a new family of compact vision-language-action models, called TinyVLA, which offers two key advantages over existing VLA models: (1) faster inference speeds, and (2) improved data efficiency, eliminating the need for pre-training stage. Our framework incorporates two essential components to build TinyVLA: (1) initializing the policy backbone with robust, high-speed multimodal models, and (2) integrating a diffusion policy decoder during fine-tuning to enable precise robot actions. We conducted extensive evaluations of TinyVLA in both simulation and on real robots, demonstrating that our approach significantly outperforms the state-of-the-art VLA model, OpenVLA, in terms of speed and data efficiency, while delivering comparable or superior performance. Additionally, TinyVLA exhibits strong generalization capabilities across various dimensions, including language instructions, novel objects, unseen positions, changes in object appearance, background variations, and environmental shifts, often matching or exceeding the performance of OpenVLA. We believe that \methodname offers an interesting perspective on utilizing pre-trained multimodal models for policy learning. Our project is at https://tiny-vla.github.io.

[Arxiv](https://arxiv.org/abs/2409.12514)