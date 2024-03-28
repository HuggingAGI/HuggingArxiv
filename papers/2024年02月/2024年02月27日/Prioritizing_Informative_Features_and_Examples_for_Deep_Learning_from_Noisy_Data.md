# 在嘈杂数据中进行深度学习时，我们致力于优先挖掘并利用富含信息的特征及代表性示例。

发布时间：2024年02月27日

`Agent`

> Prioritizing Informative Features and Examples for Deep Learning from Noisy Data

# 摘要

> 本论文提出一个统一的系统框架，它优先提炼并利用信息丰富的特征及实例，有力地强化深度学习开发过程的各个环节，包括特征学习、数据标注和数据筛选。首先，我们借助辅助的离分布数据剔除无关噪声，精准提取目标任务关键的信息特征。接着，为了降低主动学习所需的标注成本，我们创新了一种策略，从无标签噪声数据中高效挑选出最具信息价值的实例。针对在追求信息丰富度时容易引入噪声实例的难题，我们设计了一种元模型，力求在纯度和信息量之间寻找最佳平衡点。最后，我们提出了一项技术，从已标注的噪声数据集中优选信息丰富的实例，确保数据筛选阶段的性能不打折扣。对于已标注图像噪声数据，我们研发了一种基于邻近样本置信度的数据筛选方法，有效维护了当前最先进重标签模型的表现；而对于已标注文本噪声数据，则提出了一种注重多样性的指令筛选方法，通过提示方式优化指令排序，进而显著提升了大型语言模型的表现力。综上所述，我们的这一整体框架使深度学习开发流程对噪声数据具备强大的鲁棒性，在实际应用中有效缓解了噪声特征和实例带来的影响。

> In this dissertation, we propose a systemic framework that prioritizes informative features and examples to enhance each stage of the development process. Specifically, we prioritize informative features and examples and improve the performance of feature learning, data labeling, and data selection. We first propose an approach to extract only informative features that are inherent to solving a target task by using auxiliary out-of-distribution data. We deactivate the noise features in the target distribution by using that in the out-of-distribution data. Next, we introduce an approach that prioritizes informative examples from unlabeled noisy data in order to reduce the labeling cost of active learning. In order to solve the purity-information dilemma, where an attempt to select informative examples induces the selection of many noisy examples, we propose a meta-model that finds the best balance between purity and informativeness. Lastly, we suggest an approach that prioritizes informative examples from labeled noisy data to preserve the performance of data selection. For labeled image noise data, we propose a data selection method that considers the confidence of neighboring samples to maintain the performance of the state-of-the-art Re-labeling models. For labeled text noise data, we present an instruction selection method that takes diversity into account for ranking the quality of instructions with prompting, thereby enhancing the performance of aligned large language models.
  Overall, our unified framework induces the deep learning development process robust to noisy data, thereby effectively mitigating noisy features and examples in real-world applications.

[Arxiv](https://arxiv.org/abs/2403.00013)