# DAdEE：早期退出 PLM 中的无监督领域自适应

发布时间：2024年10月06日

`LLM理论` `人工智能` `软件工程`

> DAdEE: Unsupervised Domain Adaptation in Early Exit PLMs

# 摘要

> 预训练语言模型 (PLM) 在自监督下表现出色，但庞大的体积导致推理延迟高。早期退出 (EE) 策略通过允许样本从中间层分类器退出，来解决这一问题，但退出分类器对领域变化敏感，泛化能力有限。为此，我们提出了无监督领域适应的 DADEE 框架，利用知识蒸馏进行多层次适应。DADEE 在每层使用 GAN 对抗适应，实现领域不变表示，缩小源域与目标域的差距。附加的退出不仅加速推理，还通过减少灾难性遗忘和模式崩溃，增强领域适应，更适合现实场景。实验表明，DADEE 在领域转移场景下，不仅超越早期退出方法，还优于多种领域适应方法。源代码见 https://github.com/Div290/DAdEE。

> Pre-trained Language Models (PLMs) exhibit good accuracy and generalization ability across various tasks using self-supervision, but their large size results in high inference latency. Early Exit (EE) strategies handle the issue by allowing the samples to exit from classifiers attached to the intermediary layers, but they do not generalize well, as exit classifiers can be sensitive to domain changes. To address this, we propose Unsupervised Domain Adaptation in EE framework (DADEE) that employs multi-level adaptation using knowledge distillation. DADEE utilizes GAN-based adversarial adaptation at each layer to achieve domain-invariant representations, reducing the domain gap between the source and target domain across all layers. The attached exits not only speed up inference but also enhance domain adaptation by reducing catastrophic forgetting and mode collapse, making it more suitable for real-world scenarios. Experiments on tasks such as sentiment analysis, entailment classification, and natural language inference demonstrate that DADEE consistently outperforms not only early exit methods but also various domain adaptation methods under domain shift scenarios. The anonymized source code is available at https://github.com/Div290/DAdEE.

[Arxiv](https://arxiv.org/abs/2410.04424)