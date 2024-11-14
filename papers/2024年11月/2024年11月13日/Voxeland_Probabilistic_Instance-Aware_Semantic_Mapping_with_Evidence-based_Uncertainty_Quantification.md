# Voxeland：具有基于证据的不确定性量化的概率实例感知语义映射

发布时间：2024年11月13日

`LLM应用` `机器人` `场景理解`

> Voxeland: Probabilistic Instance-Aware Semantic Mapping with Evidence-based Uncertainty Quantification

# 摘要

> 在以人为本的环境中的机器人需要准确的场景理解，才能有效地执行高级任务。这种理解可以通过实例感知语义映射来实现，这涉及到在单个实例的层面上重建元素。神经网络，作为场景理解的实际解决方案，仍然面临着一些限制，例如对于分布外对象的过度自信的错误预测或生成不准确的掩码。过度依赖这些预测会使重建容易出错，降低所得地图的稳健性，并阻碍机器人的操作。在这项工作中，我们提出了 Voxeland，一个用于逐步构建实例感知语义地图的概率框架。受证据理论的启发，Voxeland 将神经网络的预测视为在几何和语义层面上关于地图实例的主观意见。这些意见随着时间的推移被聚合形成证据，并通过概率模型进行形式化。这使我们能够量化重建过程中的不确定性，有助于识别需要改进的地图区域（例如重新观察或重新分类）。作为利用这一点的一种策略，我们纳入了一个大型视觉语言模型（LVLM），对不确定性高的实例进行语义层面的消歧。在公开可用的 SceneNN 数据集上的标准基准测试结果表明，Voxeland 优于最先进的方法，突出了结合和利用实例和语义层面的不确定性以增强重建稳健性的好处。这一点通过在现实世界的 ScanNet 数据集上进行的定性实验得到了进一步验证。

> Robots in human-centered environments require accurate scene understanding to perform high-level tasks effectively. This understanding can be achieved through instance-aware semantic mapping, which involves reconstructing elements at the level of individual instances. Neural networks, the de facto solution for scene understanding, still face limitations such as overconfident incorrect predictions with out-of-distribution objects or generating inaccurate masks.Placing excessive reliance on these predictions makes the reconstruction susceptible to errors, reducing the robustness of the resulting maps and hampering robot operation. In this work, we propose Voxeland, a probabilistic framework for incrementally building instance-aware semantic maps. Inspired by the Theory of Evidence, Voxeland treats neural network predictions as subjective opinions regarding map instances at both geometric and semantic levels. These opinions are aggregated over time to form evidences, which are formalized through a probabilistic model. This enables us to quantify uncertainty in the reconstruction process, facilitating the identification of map areas requiring improvement (e.g. reobservation or reclassification). As one strategy to exploit this, we incorporate a Large Vision-Language Model (LVLM) to perform semantic level disambiguation for instances with high uncertainty. Results from the standard benchmarking on the publicly available SceneNN dataset demonstrate that Voxeland outperforms state-of-the-art methods, highlighting the benefits of incorporating and leveraging both instance- and semantic-level uncertainties to enhance reconstruction robustness. This is further validated through qualitative experiments conducted on the real-world ScanNet dataset.

[Arxiv](https://arxiv.org/abs/2411.08727)