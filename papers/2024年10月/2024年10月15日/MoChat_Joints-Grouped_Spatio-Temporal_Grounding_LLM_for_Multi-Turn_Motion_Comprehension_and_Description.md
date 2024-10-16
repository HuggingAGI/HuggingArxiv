# MoChat：一款专为多轮运动理解和描述设计的联合分组时空定位大型语言模型

发布时间：2024年10月15日

`LLM应用`

> MoChat: Joints-Grouped Spatio-Temporal Grounding LLM for Multi-Turn Motion Comprehension and Description

# 摘要

> 尽管深度学习在理解人类运动方面不断进步，但现有模型在识别动作时间和特定身体部位方面仍显不足，且仅支持单轮交互。这限制了它们在捕捉细粒度运动细节上的能力。为此，我们提出了 MoChat，一种多模态大型语言模型，能够进行人类运动的时空定位和多轮对话理解。我们通过人体解剖结构对骨骼帧进行分组，并结合 Joints-Grouped Skeleton Encoder 和 LLM 嵌入，分别生成空间和时间感知的嵌入。此外，我们还开发了从骨骼序列中提取时间戳的流程，并构建了多轮对话进行空间定位。最终，通过生成多样化的任务指令进行联合训练。实验结果显示，MoChat 在运动理解任务中表现卓越，成为首个实现细粒度时空定位的模型。

> Despite continuous advancements in deep learning for understanding human motion, existing models often struggle to accurately identify action timing and specific body parts, typically supporting only single-round interaction. Such limitations in capturing fine-grained motion details reduce their effectiveness in motion understanding tasks. In this paper, we propose MoChat, a multimodal large language model capable of spatio-temporal grounding of human motion and understanding multi-turn dialogue context. To achieve these capabilities, we group the spatial information of each skeleton frame based on human anatomical structure and then apply them with Joints-Grouped Skeleton Encoder, whose outputs are combined with LLM embeddings to create spatio-aware and temporal-aware embeddings separately. Additionally, we develop a pipeline for extracting timestamps from skeleton sequences based on textual annotations, and construct multi-turn dialogues for spatially grounding. Finally, various task instructions are generated for jointly training. Experimental results demonstrate that MoChat achieves state-of-the-art performance across multiple metrics in motion understanding tasks, making it as the first model capable of fine-grained spatio-temporal grounding of human motion.

[Arxiv](https://arxiv.org/abs/2410.11404)