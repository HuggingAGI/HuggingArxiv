# Octopi：通过大型触觉-语言模型进行物体属性推理

发布时间：2024年05月04日

`Agent` `机器人技术` `人工智能`

> Octopi: Object Property Reasoning with Large Tactile-Language Models

# 摘要

> 物理推理乃机器人精准操作之关键。最新研究通过视觉与语言双重模态探究物理推理，视觉捕捉环境物体细节，语言则架起抽象与沟通的桥梁。尽管这些成果在多样化的物理推理挑战中成绩斐然，但仅限于通过视觉或语言信息可推知的物理特性。本研究创新性地融合触觉感知与语言，赋予具身系统以交互方式捕捉物理属性并运用常识进行推理的能力。我们推出了PhysiCleAR数据集，内含物理属性推理任务及GelSight触觉传感器采集的触觉视频。此外，我们开发了Octopi系统，该系统结合触觉表征学习与先进的视觉-语言模型，以最小化语言微调来预测和推理触觉信息。PhysiCleAR的测试结果证明，Octopi能够利用中间物理属性预测显著提升物理推理的效能，无论是在训练有素的任务还是零样本推理中。PhysiCleAR和Octopi项目已在https://github.com/clear-nus/octopi上线。

> Physical reasoning is important for effective robot manipulation. Recent work has investigated both vision and language modalities for physical reasoning; vision can reveal information about objects in the environment and language serves as an abstraction and communication medium for additional context. Although these works have demonstrated success on a variety of physical reasoning tasks, they are limited to physical properties that can be inferred from visual or language inputs. In this work, we investigate combining tactile perception with language, which enables embodied systems to obtain physical properties through interaction and apply common-sense reasoning. We contribute a new dataset PhysiCleAR, which comprises both physical/property reasoning tasks and annotated tactile videos obtained using a GelSight tactile sensor. We then introduce Octopi, a system that leverages both tactile representation learning and large vision-language models to predict and reason about tactile inputs with minimal language fine-tuning. Our evaluations on PhysiCleAR show that Octopi is able to effectively use intermediate physical property predictions to improve physical reasoning in both trained tasks and for zero-shot reasoning. PhysiCleAR and Octopi are available on https://github.com/clear-nus/octopi.

![Octopi：通过大型触觉-语言模型进行物体属性推理](../../../paper_images/2405.02794/main_figure_2.png)

![Octopi：通过大型触觉-语言模型进行物体属性推理](../../../paper_images/2405.02794/pipeline.png)

![Octopi：通过大型触觉-语言模型进行物体属性推理](../../../paper_images/2405.02794/model_diagram.png)

![Octopi：通过大型触觉-语言模型进行物体属性推理](../../../paper_images/2405.02794/food_state_reasoning.png)

![Octopi：通过大型触觉-语言模型进行物体属性推理](../../../paper_images/2405.02794/object_part_reasoning.png)

![Octopi：通过大型触觉-语言模型进行物体属性推理](../../../paper_images/2405.02794/avocado_cropped.png)

[Arxiv](https://arxiv.org/abs/2405.02794)