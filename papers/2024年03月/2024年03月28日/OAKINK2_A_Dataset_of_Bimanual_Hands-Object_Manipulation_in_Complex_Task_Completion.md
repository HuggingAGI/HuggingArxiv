# OAKINK2：一个涵盖双手协同操作物体以完成复杂任务的数据集

发布时间：2024年03月28日

`LLM应用` `机器人` `交互重建`

> OAKINK2: A Dataset of Bimanual Hands-Object Manipulation in Complex Task Completion

# 摘要

> 我们推出了OAKINK2数据集，它包含了复杂日常活动中双手操控物体的任务。为了将这些复杂任务转化为有条理的表述，OAKINK2采用了三层抽象法：功能、基础任务和复杂任务，以系统化地组织操作任务。该数据集从物体的角度出发，将复杂任务视为一系列物体功能实现的过程。功能层阐述了场景中物体所具备的功能；基础任务层描述了人类与物体之间实现这些功能的最小互动单元；而复杂任务层则展示了这些基础任务是如何组合并相互依存的。OAKINK2提供了丰富的多视角图像和精确的人体、手部及交互物体姿态标注，支持交互重建和动作合成等应用。基于OAKINK2的三层抽象，我们研究了一个面向完成复杂任务（CTC）的框架。CTC致力于生成一系列双手操控动作，以达成任务目标。在这个框架下，我们利用大型语言模型（LLMs）将复杂任务目标分解成一系列基础任务，并开发了一个动作实现模型，用于生成每个基础任务对应的双手手部动作。相关数据集和模型可在 https://oakink.net/v2 查看和下载。

> We present OAKINK2, a dataset of bimanual object manipulation tasks for complex daily activities. In pursuit of constructing the complex tasks into a structured representation, OAKINK2 introduces three level of abstraction to organize the manipulation tasks: Affordance, Primitive Task, and Complex Task. OAKINK2 features on an object-centric perspective for decoding the complex tasks, treating them as a sequence of object affordance fulfillment. The first level, Affordance, outlines the functionalities that objects in the scene can afford, the second level, Primitive Task, describes the minimal interaction units that humans interact with the object to achieve its affordance, and the third level, Complex Task, illustrates how Primitive Tasks are composed and interdependent. OAKINK2 dataset provides multi-view image streams and precise pose annotations for the human body, hands and various interacting objects. This extensive collection supports applications such as interaction reconstruction and motion synthesis. Based on the 3-level abstraction of OAKINK2, we explore a task-oriented framework for Complex Task Completion (CTC). CTC aims to generate a sequence of bimanual manipulation to achieve task objectives. Within the CTC framework, we employ Large Language Models (LLMs) to decompose the complex task objectives into sequences of Primitive Tasks and have developed a Motion Fulfillment Model that generates bimanual hand motion for each Primitive Task. OAKINK2 datasets and models are available at https://oakink.net/v2.

[Arxiv](https://arxiv.org/abs/2403.19417)