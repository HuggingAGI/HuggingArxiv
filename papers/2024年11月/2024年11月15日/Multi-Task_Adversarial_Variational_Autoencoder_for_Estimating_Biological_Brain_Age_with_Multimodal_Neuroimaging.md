# 多任务对抗变分自编码器用于借助多模态神经成像来估算生物大脑年龄

发布时间：2024年11月15日

`LLM应用` `脑科学`

> Multi-Task Adversarial Variational Autoencoder for Estimating Biological Brain Age with Multimodal Neuroimaging

# 摘要

> 尽管在基于结构 MRI 数据来估算脑年龄的深度学习领域有所进展，但由于功能 MRI 数据结构复杂且功能连接测量具有噪声特性，将其纳入存在困难。为此，我们推出了多任务对抗变分自编码器，这是一个专门设计的深度学习框架，旨在通过多模态 MRI 数据的整合来优化脑年龄预测。此模型把潜在变量划分为通用和独特代码，分离出共享及模态特定的特征。通过将多任务学习与性别分类作为附加任务相融合，该模型捕捉到了性别特定的衰老模式。在 OpenBHB 数据集（一个大型多站点脑 MRI 集合）上进行评估，该模型的平均绝对误差为 2.77 年，超越了传统方法。这一成果让 M-AVAE 成为脑年龄估算中基于元宇宙的医疗保健应用的有力工具。

> Despite advances in deep learning for estimating brain age from structural MRI data, incorporating functional MRI data is challenging due to its complex structure and the noisy nature of functional connectivity measurements. To address this, we present the Multitask Adversarial Variational Autoencoder, a custom deep learning framework designed to improve brain age predictions through multimodal MRI data integration. This model separates latent variables into generic and unique codes, isolating shared and modality-specific features. By integrating multitask learning with sex classification as an additional task, the model captures sex-specific aging patterns. Evaluated on the OpenBHB dataset, a large multisite brain MRI collection, the model achieves a mean absolute error of 2.77 years, outperforming traditional methods. This success positions M-AVAE as a powerful tool for metaverse-based healthcare applications in brain age estimation.

[Arxiv](https://arxiv.org/abs/2411.10100)