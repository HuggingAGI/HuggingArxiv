# 借助语言引导的监督方式，提升视觉连续学习效果

发布时间：2024年03月24日

`LLM应用` `持续学习` `计算机视觉`

> Enhancing Visual Continual Learning with Language-Guided Supervision

# 摘要

> CL致力于让模型不断学习新任务且不丢失旧知识，以往研究多聚焦于结构设计、回放数据、正则化等策略，却较少关注类别名称的语义信息。目前普遍做法是采用独热标签及随机初始化分类器。然而，独热标签携带的有限语义信息不利于跨任务间知识的有效传递。本文在CL框架内重新审视了分类器头部的角色，并尝试用PLMs产生的语义知识替换传统分类器。具体来说，我们利用PLMs为各类别生成富含语义的目标标签，这些标签在训练阶段保持不变，作为指导信号，充分体现了各任务间类别间的语义联系。实验表明，这种方法通过减少表征漂移和增强跨任务知识迁移，有效地缓解了遗忘问题。此方法实施简便，可轻松整合到现有方法中，调整幅度极小。大量基于十一项主流基准的实验显示，不论何种协议，我们的方法均表现出显著的有效性和广泛的适用性。比如，在ImageNet-100的类增量学习场景下，我们的方法将Top-1精度提升3.2\%至6.1\%，同时将遗忘率降低2.6\%至13.1\%。

> Continual learning (CL) aims to empower models to learn new tasks without forgetting previously acquired knowledge. Most prior works concentrate on the techniques of architectures, replay data, regularization, \etc. However, the category name of each class is largely neglected. Existing methods commonly utilize the one-hot labels and randomly initialize the classifier head. We argue that the scarce semantic information conveyed by the one-hot labels hampers the effective knowledge transfer across tasks. In this paper, we revisit the role of the classifier head within the CL paradigm and replace the classifier with semantic knowledge from pretrained language models (PLMs). Specifically, we use PLMs to generate semantic targets for each class, which are frozen and serve as supervision signals during training. Such targets fully consider the semantic correlation between all classes across tasks. Empirical studies show that our approach mitigates forgetting by alleviating representation drifting and facilitating knowledge transfer across tasks. The proposed method is simple to implement and can seamlessly be plugged into existing methods with negligible adjustments. Extensive experiments based on eleven mainstream baselines demonstrate the effectiveness and generalizability of our approach to various protocols. For example, under the class-incremental learning setting on ImageNet-100, our method significantly improves the Top-1 accuracy by 3.2\% to 6.1\% while reducing the forgetting rate by 2.6\% to 13.1\%.

[Arxiv](https://arxiv.org/abs/2403.16124)