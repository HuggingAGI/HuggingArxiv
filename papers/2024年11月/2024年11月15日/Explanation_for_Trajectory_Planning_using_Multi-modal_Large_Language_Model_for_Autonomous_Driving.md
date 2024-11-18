# 关于利用多模态大型语言模型实现自动驾驶轨迹规划的阐释

发布时间：2024年11月15日

`其他` `自动驾驶`

> Explanation for Trajectory Planning using Multi-modal Large Language Model for Autonomous Driving

# 摘要

> 近期，端到端风格的自动驾驶模型已被开发。然而，这些模型从感知到控制自我车辆的决策过程缺乏可解释性，令乘客感到焦虑。为减轻这一状况，构建一个能输出描述自我车辆未来行为及其原因的说明的模型是行之有效的。但现有方法生成的推理文本无法充分体现自我车辆的未来规划，因其利用瞬时控制信号作为输入来训练模型输出说明。在本研究中，我们提出了一个以自我车辆的未来规划轨迹为输入的推理模型，并用新收集的数据集来解决这一局限。

> End-to-end style autonomous driving models have been developed recently. These models lack interpretability of decision-making process from perception to control of the ego vehicle, resulting in anxiety for passengers. To alleviate it, it is effective to build a model which outputs captions describing future behaviors of the ego vehicle and their reason. However, the existing approaches generate reasoning text that inadequately reflects the future plans of the ego vehicle, because they train models to output captions using momentary control signals as inputs. In this study, we propose a reasoning model that takes future planning trajectories of the ego vehicle as inputs to solve this limitation with the dataset newly collected.

[Arxiv](https://arxiv.org/abs/2411.09971)