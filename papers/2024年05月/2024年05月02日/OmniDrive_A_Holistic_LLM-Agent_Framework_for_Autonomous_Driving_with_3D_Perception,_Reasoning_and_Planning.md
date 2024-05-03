# OmniDrive：一套综合性的LLM代理框架，专为自动驾驶设计，集成了3D感知、推理和规划功能。

发布时间：2024年05月02日

`Agent` `自动驾驶` `人工智能`

> OmniDrive: A Holistic LLM-Agent Framework for Autonomous Driving with 3D Perception, Reasoning and Planning

# 摘要

> 随着多模态大型语言模型（MLLMs）的飞速发展，人们越来越关注利用这些模型强大推理能力的基于LLM的自动驾驶系统。然而，要利用MLLMs的推理能力来提升规划行为并非易事，因为这需要超越二维推理的三维情境感知。为解决这一难题，本研究提出了一个全新的框架，旨在实现代理模型与三维驾驶任务之间的紧密协同。该框架采用了创新的三维MLLM架构，通过稀疏查询技术将视觉信息提升并压缩成三维数据，再输入至LLM进行处理。这种基于查询的表示方法能够同时编码动态物体和静态地图元素，如交通线路等，为三维空间中的感知与行动对齐提供了一个精简的世界模型。此外，我们还推出了OmniDrive-nuScenes，这是一个全新的视觉问答数据集，它通过包含场景描述、交通规则、三维定位、反事实推理、决策制定和规划在内的全面视觉问答任务，挑战模型的真正三维情境感知能力。广泛的研究证实了所提出架构的有效性，以及视觉问答任务在复杂三维场景中推理和规划中的关键作用。

> The advances in multimodal large language models (MLLMs) have led to growing interests in LLM-based autonomous driving agents to leverage their strong reasoning capabilities. However, capitalizing on MLLMs' strong reasoning capabilities for improved planning behavior is challenging since planning requires full 3D situational awareness beyond 2D reasoning. To address this challenge, our work proposes a holistic framework for strong alignment between agent models and 3D driving tasks. Our framework starts with a novel 3D MLLM architecture that uses sparse queries to lift and compress visual representations into 3D before feeding them into an LLM. This query-based representation allows us to jointly encode dynamic objects and static map elements (e.g., traffic lanes), providing a condensed world model for perception-action alignment in 3D. We further propose OmniDrive-nuScenes, a new visual question-answering dataset challenging the true 3D situational awareness of a model with comprehensive visual question-answering (VQA) tasks, including scene description, traffic regulation, 3D grounding, counterfactual reasoning, decision making and planning. Extensive studies show the effectiveness of the proposed architecture as well as the importance of the VQA tasks for reasoning and planning in complex 3D scenes.

[Arxiv](https://arxiv.org/abs/2405.01533)