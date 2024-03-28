# 为实现与语言相关的机器人导航，我们构建了分层的开放词汇三维场景图。

发布时间：2024年03月26日

`Agent` `机器人` `导航系统`

> Hierarchical Open-Vocabulary 3D Scene Graphs for Language-Grounded Robot Navigation

# 摘要

> 最新的开放词汇机器人地图技术通过融入预训练的视觉-语言元素，为传统的几何地图注入了新的活力。尽管如此，面对广阔环境和更高级别的抽象查询，现有技术仍显吃力，这在很大程度上束缚了机器人导航与语言的紧密结合。本研究提出了HOV-SG，一种新颖的分层式开放词汇3D场景图构建方法，专为提升机器人的导航能力而设计。借助先进的开放词汇视觉模型，我们不仅在三维空间中绘制出精准的段级地图，还构建了一个包含楼层、房间和物体等概念的三维场景图，每个环节都融入了丰富的开放词汇信息。该方法能够精细刻画多层建筑结构，并通过跨层Voronoi图支持机器人的自由穿行。经过三大不同数据集的测试，HOV-SG在物体、房间和楼层等级别的语义准确性上均大幅超越了先前的研究，并且在保持高精度的同时，将数据表示的体积压缩至原来的四分之一。为验证HOV-SG的实用性和适应性，我们在真实世界的复杂仓储环境中进行了长期的语言引导式机器人导航实验，并取得了圆满成功。相关代码和演示视频可在http://hovsg.github.io/ 网站下载。

> Recent open-vocabulary robot mapping methods enrich dense geometric maps with pre-trained visual-language features. While these maps allow for the prediction of point-wise saliency maps when queried for a certain language concept, large-scale environments and abstract queries beyond the object level still pose a considerable hurdle, ultimately limiting language-grounded robotic navigation. In this work, we present HOV-SG, a hierarchical open-vocabulary 3D scene graph mapping approach for language-grounded robot navigation. Leveraging open-vocabulary vision foundation models, we first obtain state-of-the-art open-vocabulary segment-level maps in 3D and subsequently construct a 3D scene graph hierarchy consisting of floor, room, and object concepts, each enriched with open-vocabulary features. Our approach is able to represent multi-story buildings and allows robotic traversal of those using a cross-floor Voronoi graph. HOV-SG is evaluated on three distinct datasets and surpasses previous baselines in open-vocabulary semantic accuracy on the object, room, and floor level while producing a 75% reduction in representation size compared to dense open-vocabulary maps. In order to prove the efficacy and generalization capabilities of HOV-SG, we showcase successful long-horizon language-conditioned robot navigation within real-world multi-storage environments. We provide code and trial video data at http://hovsg.github.io/.

[Arxiv](https://arxiv.org/abs/2403.17846)