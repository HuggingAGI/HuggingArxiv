# 关于有序三维结构的自监督学习

发布时间：2024年11月21日

`LLM应用` `材料物理` `几何任务`

> Self-Supervised Learning for Ordered Three-Dimensional Structures

# 摘要

> 近期工作表明，以自监督任务训练大型语言模型，并在迁移学习场景下微调这些模型以完成新任务，是个很厉害的构想，即便标记数据少，也能创建出参数众多的模型；但利用这些进展的领域数量有限。在本研究中，我们设定了一组适用于大规模研究有序三维结构的几何任务，无需人工干预数据标注。我们基于几何代数构建了深度旋转和平移等变神经网络，并用于解决理想化和模拟的三维结构上的这些任务。在材料物理领域，量化复杂结构组件的顺序一直是个难题；这些模型能以多种方式阐释真实自组装系统的行为，比如无需进一步修改就能从已学习的任务中提炼见解，或者通过迁移学习用少量标记数据解决新任务。

> Recent work has proven that training large language models with self-supervised tasks and fine-tuning these models to complete new tasks in a transfer learning setting is a powerful idea, enabling the creation of models with many parameters, even with little labeled data; however, the number of domains that have harnessed these advancements has been limited. In this work, we formulate a set of geometric tasks suitable for the large-scale study of ordered three-dimensional structures, without requiring any human intervention in data labeling. We build deep rotation- and permutation-equivariant neural networks based on geometric algebra and use them to solve these tasks on both idealized and simulated three-dimensional structures. Quantifying order in complex-structured assemblies remains a long-standing challenge in materials physics; these models can elucidate the behavior of real self-assembling systems in a variety of ways, from distilling insights from learned tasks without further modification to solving new tasks with smaller amounts of labeled data via transfer learning.

[Arxiv](https://arxiv.org/abs/2411.14680)