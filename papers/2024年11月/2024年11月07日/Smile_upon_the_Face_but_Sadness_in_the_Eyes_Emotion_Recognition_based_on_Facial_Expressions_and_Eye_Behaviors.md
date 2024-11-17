# 脸上挂着微笑，眼中却藏着悲伤：基于面部表情和眼部行为的情绪识别

发布时间：2024年11月07日

`其他` `情感识别` `面部表情识别`

> Smile upon the Face but Sadness in the Eyes: Emotion Recognition based on Facial Expressions and Eye Behaviors

# 摘要

> 情感识别（ER）指的是从给定数据中辨识人类情感的过程。当下，此领域高度依赖面部表情识别（FER），毕竟面部表情蕴含着丰富的情感线索。但要注意，面部表情未必总能精准反映真实情感，基于FER的结果或许会造成误导性的ER。为了理解并填补FER与ER之间的鸿沟，我们引入眼睛行为作为关键的情感线索，创建了全新的眼行为辅助多模态情感识别（EMER）数据集。和现有的多模态ER数据集不同，EMER数据集运用刺激材料诱导的自发情感生成方式，把非侵入性的眼睛行为数据（像眼球运动和眼球注视图）与面部视频相融合，旨在获取自然且准确的人类情感。值得一提的是，我们在EMER中首次为ER和FER都提供了标注，得以进行全面分析，以更好地阐释这两项任务之间的差距。另外，我们专门设计了一种新的EMERT架构，通过有效识别并弥合二者之间的情感差距，同步提升ER和FER的性能。具体而言，我们的EMERT采用模态对抗特征解耦和多任务Transformer来强化眼睛行为的建模，从而为面部表情提供了有效的补充。在实验中，我们为EMER数据集的各类综合评估引入了七种多模态基准协议。结果显示，EMERT大幅优于其他前沿的多模态方法，揭示了对眼睛行为建模对于强大的ER的重要性。总之，我们对眼睛行为在ER中的重要性展开了全面剖析，推动了有关解决FER和ER之间差距以实现更出色的ER性能的研究。

> Emotion Recognition (ER) is the process of identifying human emotions from given data. Currently, the field heavily relies on facial expression recognition (FER) because facial expressions contain rich emotional cues. However, it is important to note that facial expressions may not always precisely reflect genuine emotions and FER-based results may yield misleading ER. To understand and bridge this gap between FER and ER, we introduce eye behaviors as an important emotional cues for the creation of a new Eye-behavior-aided Multimodal Emotion Recognition (EMER) dataset. Different from existing multimodal ER datasets, the EMER dataset employs a stimulus material-induced spontaneous emotion generation method to integrate non-invasive eye behavior data, like eye movements and eye fixation maps, with facial videos, aiming to obtain natural and accurate human emotions. Notably, for the first time, we provide annotations for both ER and FER in the EMER, enabling a comprehensive analysis to better illustrate the gap between both tasks. Furthermore, we specifically design a new EMERT architecture to concurrently enhance performance in both ER and FER by efficiently identifying and bridging the emotion gap between the two.Specifically, our EMERT employs modality-adversarial feature decoupling and multi-task Transformer to augment the modeling of eye behaviors, thus providing an effective complement to facial expressions. In the experiment, we introduce seven multimodal benchmark protocols for a variety of comprehensive evaluations of the EMER dataset. The results show that the EMERT outperforms other state-of-the-art multimodal methods by a great margin, revealing the importance of modeling eye behaviors for robust ER. To sum up, we provide a comprehensive analysis of the importance of eye behaviors in ER, advancing the study on addressing the gap between FER and ER for more robust ER performance.

[Arxiv](https://arxiv.org/abs/2411.05879)