# RT-Grasp：借助多模态大型语言模型实现机器人抓取的推理调整

发布时间：2024年11月07日

`LLM应用` `机器人` `语言模型`

> RT-Grasp: Reasoning Tuning Robotic Grasping via Multi-modal Large Language Model

# 摘要

> 近期大型语言模型（LLMs）的进步彰显出其非凡的推理能力，在众多领域产生了重大影响。但在机器人领域，因其固有的文本输出特性，其应用主要局限于操作规划任务。本文针对这一局限，探究了将LLMs的推理能力用于机器人任务中生成数值预测的可能性，尤其是在机器人抓取方面。我们提出了推理调优这一创新方法，即在训练时于预测前融入推理阶段，充分借助LLMs丰富的先验知识和先进的推理能力。此方法让LLMs，特别是具备多模态能力的LLMs，能够生成诸如通过对话实现上下文感知和适应的抓取姿势等精准的数值输出。另外，我们还推出了精心整理的推理调优VLM抓取数据集，以助力LLMs适应机器人抓取。在抓取数据集和真实世界实验中的大量验证凸显了多模态LLMs在机器人数值预测任务中的适应性。这不但拓展了其应用范围，还填补了基于文本的规划与直接机器人控制之间的空白，进而将LLMs在机器人领域的潜力发挥到极致。

> Recent advances in Large Language Models (LLMs) have showcased their remarkable reasoning capabilities, making them influential across various fields. However, in robotics, their use has primarily been limited to manipulation planning tasks due to their inherent textual output. This paper addresses this limitation by investigating the potential of adopting the reasoning ability of LLMs for generating numerical predictions in robotics tasks, specifically for robotic grasping. We propose Reasoning Tuning, a novel method that integrates a reasoning phase before prediction during training, leveraging the extensive prior knowledge and advanced reasoning abilities of LLMs. This approach enables LLMs, notably with multi-modal capabilities, to generate accurate numerical outputs like grasp poses that are context-aware and adaptable through conversations. Additionally, we present the Reasoning Tuning VLM Grasp dataset, carefully curated to facilitate the adaptation of LLMs to robotic grasping. Extensive validation on both grasping datasets and real-world experiments underscores the adaptability of multi-modal LLMs for numerical prediction tasks in robotics. This not only expands their applicability but also bridges the gap between text-based planning and direct robot control, thereby maximizing the potential of LLMs in robotics.

[Arxiv](https://arxiv.org/abs/2411.05212)