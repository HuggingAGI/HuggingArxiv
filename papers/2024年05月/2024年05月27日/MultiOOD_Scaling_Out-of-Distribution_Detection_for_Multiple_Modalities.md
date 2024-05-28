# MultiOOD：多模态分布外检测的扩展研究

发布时间：2024年05月27日

`Agent

理由：这篇论文主要关注的是在安全关键应用中，如自动驾驶和机器人辅助手术，如何通过多模态数据整合来提升分布外（OOD）样本的检测效能。论文中提出的MultiOOD基准和Agree-to-Disagree（A2D）算法，以及NP-Mix异常合成方法，都是为了增强Agent（在这里指的是自动驾驶系统或机器人手术系统）在面对未知或异常情况时的识别和应对能力。这些技术的发展和应用直接关联到Agent的性能和安全性，因此将其归类为Agent。` `自动驾驶`

> MultiOOD: Scaling Out-of-Distribution Detection for Multiple Modalities

# 摘要

> 在自动驾驶和机器人辅助手术等安全关键应用中，检测分布外（OOD）样本至关重要。尽管现有研究多聚焦于单模态图像数据，但现实世界的多模态特性要求我们整合多源信息以提升OOD检测的效能。为此，我们推出了首个多模态OOD检测基准——MultiOOD，它涵盖了多样化的数据集和模态组合。初步评估显示，即便是简单地引入额外模态，也能显著提升检测效果，凸显了多模态整合的重要性。基于分布内（ID）与OOD数据间的模态预测差异及其与OOD性能的紧密关联，我们开发了Agree-to-Disagree（A2D）算法，旨在训练中放大这种差异。同时，我们创新性地提出了NP-Mix异常合成方法，通过挖掘最近邻类别的信息，拓展特征空间，与A2D相辅相成，共同强化OOD检测。实验证明，结合A2D与NP-Mix的训练策略能大幅提升现有OOD检测算法的性能。我们的源代码及MultiOOD基准已公开于https://github.com/donghao51/MultiOOD。

> Detecting out-of-distribution (OOD) samples is important for deploying machine learning models in safety-critical applications such as autonomous driving and robot-assisted surgery. Existing research has mainly focused on unimodal scenarios on image data. However, real-world applications are inherently multimodal, which makes it essential to leverage information from multiple modalities to enhance the efficacy of OOD detection. To establish a foundation for more realistic Multimodal OOD Detection, we introduce the first-of-its-kind benchmark, MultiOOD, characterized by diverse dataset sizes and varying modality combinations. We first evaluate existing unimodal OOD detection algorithms on MultiOOD, observing that the mere inclusion of additional modalities yields substantial improvements. This underscores the importance of utilizing multiple modalities for OOD detection. Based on the observation of Modality Prediction Discrepancy between in-distribution (ID) and OOD data, and its strong correlation with OOD performance, we propose the Agree-to-Disagree (A2D) algorithm to encourage such discrepancy during training. Moreover, we introduce a novel outlier synthesis method, NP-Mix, which explores broader feature spaces by leveraging the information from nearest neighbor classes and complements A2D to strengthen OOD detection performance. Extensive experiments on MultiOOD demonstrate that training with A2D and NP-Mix improves existing OOD detection algorithms by a large margin. Our source code and MultiOOD benchmark are available at https://github.com/donghao51/MultiOOD.

[Arxiv](https://arxiv.org/abs/2405.17419)