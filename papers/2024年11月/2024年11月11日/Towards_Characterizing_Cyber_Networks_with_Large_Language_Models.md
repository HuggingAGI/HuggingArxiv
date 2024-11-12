# 朝着用大型语言模型表征网络的方向发展

发布时间：2024年11月11日

`其他` `网络安全` `物联网`

> Towards Characterizing Cyber Networks with Large Language Models

# 摘要

> 威胁狩猎分析大量、嘈杂、高维的数据以发现稀疏的对抗行为。我们认为，无论对抗活动如何伪装，在高维空间中都极难完全掩盖。在本文中，我们利用网络数据的这些潜在特征，通过一个名为网络日志嵌入模型（CLEM）的原型工具来发现异常。CLEM 是在来自真实生产网络和物联网（IoT）网络安全测试平台的 Zeek 网络流量日志上进行训练的。该模型在数据的滑动窗口上故意过度训练，以紧密表征每个窗口。我们使用调整兰德指数（ARI）将 CLEM 输出的 k 均值聚类与专家对嵌入的标记进行比较。我们的方法表明，使用自然语言建模来理解网络数据是有前景的。

> Threat hunting analyzes large, noisy, high-dimensional data to find sparse adversarial behavior. We believe adversarial activities, however they are disguised, are extremely difficult to completely obscure in high dimensional space. In this paper, we employ these latent features of cyber data to find anomalies via a prototype tool called Cyber Log Embeddings Model (CLEM). CLEM was trained on Zeek network traffic logs from both a real-world production network and an from Internet of Things (IoT) cybersecurity testbed. The model is deliberately overtrained on a sliding window of data to characterize each window closely. We use the Adjusted Rand Index (ARI) to comparing the k-means clustering of CLEM output to expert labeling of the embeddings. Our approach demonstrates that there is promise in using natural language modeling to understand cyber data.

[Arxiv](https://arxiv.org/abs/2411.07089)