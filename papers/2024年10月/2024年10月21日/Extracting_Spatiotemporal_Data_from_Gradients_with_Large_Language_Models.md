# 利用大型语言模型从梯度中提取时空数据

发布时间：2024年10月21日

`LLM应用` `网络安全` `联邦学习`

> Extracting Spatiotemporal Data from Gradients with Large Language Models

# 摘要

> 近期研究发现，敏感用户数据可通过梯度更新被重建，威胁到联邦学习的隐私安全。尽管这些方法在图像数据上表现出色，但难以直接应用于时空数据领域。为此，我们首创了时空梯度反转攻击（ST-GIA），成功从梯度中还原原始位置。针对时空数据攻击中缺乏先验知识的难题，我们进一步提出ST-GIA+，借助语言模型精准定位，实现数据重建。同时，我们设计了自适应防御策略，动态调整保护力度，优化隐私与效用的平衡。实验证明，该策略在确保安全的同时，有效维持了时空联邦学习的效能。

> Recent works show that sensitive user data can be reconstructed from gradient updates, breaking the key privacy promise of federated learning. While success was demonstrated primarily on image data, these methods do not directly transfer to other domains, such as spatiotemporal data. To understand privacy risks in spatiotemporal federated learning, we first propose Spatiotemporal Gradient Inversion Attack (ST-GIA), a gradient attack algorithm tailored to spatiotemporal data that successfully reconstructs the original location from gradients. Furthermore, the absence of priors in attacks on spatiotemporal data has hindered the accurate reconstruction of real client data. To address this limitation, we propose ST-GIA+, which utilizes an auxiliary language model to guide the search for potential locations, thereby successfully reconstructing the original data from gradients. In addition, we design an adaptive defense strategy to mitigate gradient inversion attacks in spatiotemporal federated learning. By dynamically adjusting the perturbation levels, we can offer tailored protection for varying rounds of training data, thereby achieving a better trade-off between privacy and utility than current state-of-the-art methods. Through intensive experimental analysis on three real-world datasets, we reveal that the proposed defense strategy can well preserve the utility of spatiotemporal federated learning with effective security protection.

[Arxiv](https://arxiv.org/abs/2410.16121)