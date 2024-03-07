# [MiKASA——这款创新的三维视觉定位模型，巧妙融合了多键锚点与场景感知技术，以Transformer架构为核心，旨在提升三维空间中的目标定位精准度。](https://arxiv.org/abs/2403.03077)

> MiKASA: Multi-Key-Anchor & Scene-Aware Transformer for 3D Visual Grounding

发布时间：2024年03月05日

> 三维视觉定位任务要求模型能在三维环境中精准对应自然语言描述与目标物体，然而现存方法在处理复杂的、涉及多参照点或视角相关描述的语言理解及物体识别时常常遭遇瓶颈。为解决这一问题，我们创新研发了MiKASA（多关键参照点场景感知Transformer）。这款端到端训练的模型整合了基于自注意力机制的场景感知对象编码器和独创的多关键参照点技术，有效提高了物体识别精确度以及对空间关系的深入理解，并且增强了决策过程的可解释性，便于排查错误。MiKASA在Referit3D挑战赛中，在Sr3D和Nr3D两个数据集中整体精度最高，特别是在需要依据视角解析描述的类别上表现出色，遥遥领先。该项目的源代码和其他资源已在GitHub上公开：https://github.com/birdy666/MiKASA-3DVG。

> 3D visual grounding involves matching natural language descriptions with their corresponding objects in 3D spaces. Existing methods often face challenges with accuracy in object recognition and struggle in interpreting complex linguistic queries, particularly with descriptions that involve multiple anchors or are view-dependent. In response, we present the MiKASA (Multi-Key-Anchor Scene-Aware) Transformer. Our novel end-to-end trained model integrates a self-attention-based scene-aware object encoder and an original multi-key-anchor technique, enhancing object recognition accuracy and the understanding of spatial relationships. Furthermore, MiKASA improves the explainability of decision-making, facilitating error diagnosis. Our model achieves the highest overall accuracy in the Referit3D challenge for both the Sr3D and Nr3D datasets, particularly excelling by a large margin in categories that require viewpoint-dependent descriptions.
  The source code and additional resources for this project are available on GitHub: https://github.com/birdy666/MiKASA-3DVG

`Agent`