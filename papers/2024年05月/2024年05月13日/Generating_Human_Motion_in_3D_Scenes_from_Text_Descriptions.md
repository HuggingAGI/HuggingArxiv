# 通过文本描述赋予3D场景生命，创造逼真的人体动作。

发布时间：2024年05月13日

`Agent

这篇论文关注的是根据文本描述生成3D室内场景中的人类动作，这是一个涉及多模态数据处理和空间推理的任务。论文提出的方法包括使用大型语言模型来实现目标对象的语言基础，并设计以对象为中心的场景表示来简化场景复杂性。这种方法可以被视为一个智能代理（Agent）的行为，因为它涉及到理解和响应文本指令，并在虚拟环境中执行动作。因此，这篇论文更适合归类到Agent分类中。` `虚拟现实` `人机交互`

> Generating Human Motion in 3D Scenes from Text Descriptions

# 摘要

> 文本描述驱动的人类动作生成因其广泛的应用而受到越来越多的关注。然而，鲜有研究同时考虑人与场景的交互和文本条件，这对视觉和物理真实性至关重要。本文聚焦于根据文本描述生成3D室内场景中的人类动作，这一任务因文本、场景和动作的多模态特性以及空间推理的需求而充满挑战。为此，我们提出了一种新策略，将复杂问题分解为两个更易处理的部分：一是通过大型语言模型实现目标对象的语言基础；二是设计以对象为中心的场景表示，以简化场景复杂性并促进人类动作与对象关系的建模。实验结果显示，我们的方法在动作质量上超越了基线，并证实了我们的设计决策的有效性。

> Generating human motions from textual descriptions has gained growing research interest due to its wide range of applications. However, only a few works consider human-scene interactions together with text conditions, which is crucial for visual and physical realism. This paper focuses on the task of generating human motions in 3D indoor scenes given text descriptions of the human-scene interactions. This task presents challenges due to the multi-modality nature of text, scene, and motion, as well as the need for spatial reasoning. To address these challenges, we propose a new approach that decomposes the complex problem into two more manageable sub-problems: (1) language grounding of the target object and (2) object-centric motion generation. For language grounding of the target object, we leverage the power of large language models. For motion generation, we design an object-centric scene representation for the generative model to focus on the target object, thereby reducing the scene complexity and facilitating the modeling of the relationship between human motions and the object. Experiments demonstrate the better motion quality of our approach compared to baselines and validate our design choices.

[Arxiv](https://arxiv.org/abs/2405.07784)