# VLA-3D：用于 3D 语义场景理解和导航的数据集

发布时间：2024年11月05日

`LLM应用` `室内导航` `数据集`

> VLA-3D: A Dataset for 3D Semantic Scene Understanding and Navigation

# 摘要

> 随着大型语言模型（LLMs）、视觉语言模型（VLMs）和其他通用基础模型的近期兴起，仅以自然语言作为输入就能在不同环境中运行的多模态、多任务具身智能体的潜力越来越大。其中一个应用领域是使用自然语言指令的室内导航。然而，尽管最近取得了进展，但由于所需的空间推理和语义理解，特别是在可能包含许多细粒度类别的物体的任意场景中，这个问题仍然具有挑战性。为了应对这一挑战，我们整理了用于 3D 场景中视觉和语言引导行动的最大真实世界数据集（VLA-3D），它由来自现有数据集的超过 11.5 万个扫描的 3D 室内房间、2350 万个启发式生成的物体间语义关系和 970 万个综合生成的指称语句组成。我们的数据集包括处理后的 3D 点云、语义对象和房间注释、场景图、可导航自由空间注释以及专门关注用于消除对象歧义的视图独立空间关系的指称语言语句。这些特征的目标是辅助导航的下游任务，特别是在现实世界系统中，在不断变化的场景和不完美语言的开放世界中必须保证一定程度的鲁棒性。我们用当前最先进的模型对我们的数据集进行基准测试，以获得性能基线。生成和可视化数据集的所有代码均已公开发布，见 https://github.com/HaochenZ11/VLA-3D。随着这个数据集的发布，我们希望为对变化具有鲁棒性的语义 3D 场景理解的进展提供资源，并有助于交互式室内导航系统的开发。

> With the recent rise of Large Language Models (LLMs), Vision-Language Models (VLMs), and other general foundation models, there is growing potential for multimodal, multi-task embodied agents that can operate in diverse environments given only natural language as input. One such application area is indoor navigation using natural language instructions. However, despite recent progress, this problem remains challenging due to the spatial reasoning and semantic understanding required, particularly in arbitrary scenes that may contain many objects belonging to fine-grained classes. To address this challenge, we curate the largest real-world dataset for Vision and Language-guided Action in 3D Scenes (VLA-3D), consisting of over 11.5K scanned 3D indoor rooms from existing datasets, 23.5M heuristically generated semantic relations between objects, and 9.7M synthetically generated referential statements. Our dataset consists of processed 3D point clouds, semantic object and room annotations, scene graphs, navigable free space annotations, and referential language statements that specifically focus on view-independent spatial relations for disambiguating objects. The goal of these features is to aid the downstream task of navigation, especially on real-world systems where some level of robustness must be guaranteed in an open world of changing scenes and imperfect language. We benchmark our dataset with current state-of-the-art models to obtain a performance baseline. All code to generate and visualize the dataset is publicly released, see https://github.com/HaochenZ11/VLA-3D. With the release of this dataset, we hope to provide a resource for progress in semantic 3D scene understanding that is robust to changes and one which will aid the development of interactive indoor navigation systems.

[Arxiv](https://arxiv.org/abs/2411.03540)