# 怎样打造一个能同时聊天和决策的预训练多模态模型？

发布时间：2024年10月21日

`LLM应用` `自动驾驶` `人工智能`

> How to Build a Pre-trained Multimodal model for Simultaneously Chatting and Decision-making?

# 摘要

> 现有的预训练模型如 ChatGPT 和 OpenVLA，通常只能单一地处理文本或动作决策。然而，人类在驾驶时却能边聊天边精准操作。基于此，我们探索了一个新问题：能否打造一个既能聊天又能精准决策的预训练模型？为此，我们推出了 VLA4CD 模型，并在自动驾驶任务中验证了其双重能力。VLA4CD 通过 LoRA 技术，融合了语言、视觉和动作数据，设计了独特的计算模块和训练方法，使其能在输出对话的同时做出连续的动作决策，这在自动驾驶等复杂任务中尤为重要。实验证明，VLA4CD 不仅有效，而且在实时决策精度上超越了现有最先进的 VLA 模型，同时保留了 LLM 的对话能力。

> Existing large pre-trained models typically map text input to text output in an end-to-end manner, such as ChatGPT, or map a segment of text input to a hierarchy of action decisions, such as OpenVLA. However, humans can simultaneously generate text and actions when receiving specific input signals. For example, a driver can make precise driving decisions while conversing with a friend in the passenger seat. Motivated by this observation, we consider the following question in this work: is it possible to construct a pre-trained model that can provide both language interaction and precise decision-making capabilities in dynamic open scenarios. We provide a definitive answer to this question by developing a new model architecture termed Visual Language Action model for Chatting and Decision Making (VLA4CD), and further demonstrating its performance in challenging autonomous driving tasks. Specifically, we leverage LoRA to fine-tune a pre-trained LLM with data of multiple modalities covering language, visual, and action. Unlike the existing LoRA operations used for LLM fine-tuning, we have designed new computational modules and training cost functions for VLA4CD. These designs enable VLA4CD to provide continuous-valued action decisions while outputting text responses. In contrast, existing LLMs can only output text responses, and current VLA models can only output action decisions. Moreover, these VLA models handle action data by discretizing and then tokenizing the discretized actions, a method unsuitable for complex decision-making tasks involving high-dimensional continuous-valued action vectors, such as autonomous driving. The experimental results on CARLA validate that: (1) our proposed model construction method is effective; (2) compared to the SOTA VLA model, VLA4CD can provide more accurate real-time decision-making while retaining the text interaction capability inherent to LLMs.

[Arxiv](https://arxiv.org/abs/2410.15885)