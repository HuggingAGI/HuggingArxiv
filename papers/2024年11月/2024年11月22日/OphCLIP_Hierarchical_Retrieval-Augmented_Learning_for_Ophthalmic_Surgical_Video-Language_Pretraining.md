# OphCLIP：用于眼科手术视频语言预训练的分层检索增强式学习

发布时间：2024年11月22日

`LLM应用` `外科手术`

> OphCLIP: Hierarchical Retrieval-Augmented Learning for Ophthalmic Surgical Video-Language Pretraining

# 摘要

> 外科实践涵盖了复杂的视觉解读、操作技能和高深的医学知识，正因为如此的复杂性以及标注数据的稀缺，外科视觉语言预训练（VLP）困难重重。为了填补这一空缺，我们推出了 OphCLIP，这是一个专为眼科手术工作流程理解量身打造的分层检索增强型视觉语言预训练框架。OphCLIP 借助了我们构建的 OphVL 数据集，这是一个大规模且全面的集合，包含超过 37.5 万个分层结构的视频 - 文本对，具有数万个不同的属性组合（手术、阶段/操作/动作、器械、药物，还有更高级的方面，比如眼病的成因、手术目标和术后恢复建议等等）。这些分层的视频 - 文本对应关系，让 OphCLIP 能够通过将短视频片段与详尽的叙述描述相匹配，以及将完整视频与结构化标题相匹配，分别习得细粒度和长期的视觉表征，进而捕捉到复杂的手术细节和高层次的程序洞察。我们的 OphCLIP 还设计了一个检索增强型预训练框架，来利用尚未充分挖掘的大规模无声手术过程视频，自动检索语义相关内容，以强化叙事视频的表示学习。在针对阶段识别和多器械识别的 11 个数据集上进行的评估显示，OphCLIP 具备强大的泛化能力和出色的性能。

> Surgical practice involves complex visual interpretation, procedural skills, and advanced medical knowledge, making surgical vision-language pretraining (VLP) particularly challenging due to this complexity and the limited availability of annotated data. To address the gap, we propose OphCLIP, a hierarchical retrieval-augmented vision-language pretraining framework specifically designed for ophthalmic surgical workflow understanding. OphCLIP leverages the OphVL dataset we constructed, a large-scale and comprehensive collection of over 375K hierarchically structured video-text pairs with tens of thousands of different combinations of attributes (surgeries, phases/operations/actions, instruments, medications, as well as more advanced aspects like the causes of eye diseases, surgical objectives, and postoperative recovery recommendations, etc). These hierarchical video-text correspondences enable OphCLIP to learn both fine-grained and long-term visual representations by aligning short video clips with detailed narrative descriptions and full videos with structured titles, capturing intricate surgical details and high-level procedural insights, respectively. Our OphCLIP also designs a retrieval-augmented pretraining framework to leverage the underexplored large-scale silent surgical procedure videos, automatically retrieving semantically relevant content to enhance the representation learning of narrative videos. Evaluation across 11 datasets for phase recognition and multi-instrument identification shows OphCLIP's robust generalization and superior performance.

[Arxiv](https://arxiv.org/abs/2411.15421)