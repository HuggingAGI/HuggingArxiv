# COSMo：探索 CLIP 在开放集多目标域适应中的应用

发布时间：2024年08月31日

`Agent` `计算机视觉` `机器学习`

> COSMo: CLIP Talks on Open-Set Multi-Target Domain Adaptation

# 摘要

> 多目标域适应 (MTDA) 旨在从单一源域提取不变信息，并应用于多个未标记目标域。然而，现有方法多聚焦于视觉特征的域偏移，忽视了语义特征，且难以应对未知类别，形成了开放集 MTDA 的挑战。本文提出的 COSMo 方法，通过源域引导的提示学习，在提示空间中学习域无关提示，有效应对 MTDA 问题。COSMo 利用特定域偏差网络和针对已知与未知类别的独立提示，成功适应域和类别偏移。作为首个解决开放集多目标域适应 (OSMTDA) 的方法，COSMo 更真实地反映了现实场景，并克服了开放集和多目标域适应的难题。在 Mini-DomainNet、Office-31 和 Office-Home 三个挑战性数据集上，COSMo 相较于其他适应 OSMTDA 设置的方法，平均提升了 5.1%。代码已公开，详见：https://github.com/munish30monga/COSMo

> Multi-Target Domain Adaptation (MTDA) entails learning domain-invariant information from a single source domain and applying it to multiple unlabeled target domains. Yet, existing MTDA methods predominantly focus on addressing domain shifts within visual features, often overlooking semantic features and struggling to handle unknown classes, resulting in what is known as Open-Set (OS) MTDA. While large-scale vision-language foundation models like CLIP show promise, their potential for MTDA remains largely unexplored. This paper introduces COSMo, a novel method that learns domain-agnostic prompts through source domain-guided prompt learning to tackle the MTDA problem in the prompt space. By leveraging a domain-specific bias network and separate prompts for known and unknown classes, COSMo effectively adapts across domain and class shifts. To the best of our knowledge, COSMo is the first method to address Open-Set Multi-Target DA (OSMTDA), offering a more realistic representation of real-world scenarios and addressing the challenges of both open-set and multi-target DA. COSMo demonstrates an average improvement of $5.1\%$ across three challenging datasets: Mini-DomainNet, Office-31, and Office-Home, compared to other related DA methods adapted to operate within the OSMTDA setting. Code is available at: https://github.com/munish30monga/COSMo

[Arxiv](https://arxiv.org/abs/2409.00397)