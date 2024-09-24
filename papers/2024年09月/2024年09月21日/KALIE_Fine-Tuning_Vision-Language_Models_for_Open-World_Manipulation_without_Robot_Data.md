# KALIE：通过微调视觉-语言模型，实现无需机器人数据的开放世界操作

发布时间：2024年09月21日

`Agent` `机器人` `人工智能`

> KALIE: Fine-Tuning Vision-Language Models for Open-World Manipulation without Robot Data

# 摘要

> 打造全能机器人系统，关键在于让机器人在开放世界中自如应对新对象。借鉴大型预训练模型的成功，我们推出了KALIE，一种将预训练视觉语言模型（VLM）灵活应用于机器人控制的创新方法。KALIE不直接下达动作指令，而是通过解析自然语言指令和视觉场景，预测关键点的功能特征来操控机器人。VLM在人类标注功能的2D图像上训练，无需机器人实操数据。借助功能感知的数据合成技术，KALIE能从少量人工收集的样本中，自动生成海量高质量训练数据。实验证明，仅需50个示例，KALIE便能稳健应对新操作任务。与传统预训练VLM方法相比，KALIE表现更胜一筹。

> Building generalist robotic systems involves effectively endowing robots with the capabilities to handle novel objects in an open-world setting. Inspired by the advances of large pre-trained models, we propose Keypoint Affordance Learning from Imagined Environments (KALIE), which adapts pre-trained Vision Language Models (VLMs) for robotic control in a scalable manner. Instead of directly producing motor commands, KALIE controls the robot by predicting point-based affordance representations based on natural language instructions and visual observations of the scene. The VLM is trained on 2D images with affordances labeled by humans, bypassing the need for training data collected on robotic systems. Through an affordance-aware data synthesis pipeline, KALIE automatically creates massive high-quality training data based on limited example data manually collected by humans. We demonstrate that KALIE can learn to robustly solve new manipulation tasks with unseen objects given only 50 example data points. Compared to baselines using pre-trained VLMs, our approach consistently achieves superior performance.

[Arxiv](https://arxiv.org/abs/2409.14066)