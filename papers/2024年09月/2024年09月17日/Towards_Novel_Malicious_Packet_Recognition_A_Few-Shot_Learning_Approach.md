# 探索新型恶意数据包识别：一种少样本学习策略

发布时间：2024年09月17日

`LLM应用` `网络安全` `物联网`

> Towards Novel Malicious Packet Recognition: A Few-Shot Learning Approach

# 摘要

> 随着网络的复杂性和连接性日益增加，新型恶意软件检测方法的需求变得尤为迫切。传统的安全防御手段在面对现代网络攻击的高级战术时，效果逐渐减弱。深度包检测 (DPI) 技术应运而生，成为强化网络安全的关键，它不仅分析数据包的元数据，还能深入解析其内容，提供全面的网络流量洞察。本研究提出了一种创新方法，结合大型语言模型 (LLM) 和少样本学习，以少量标签样本准确识别新型恶意软件。我们利用预训练的 LLM 提取已知恶意软件的数据包嵌入，并结合未见过的恶意软件的少量标签样本，使模型能够适应不同的恶意软件表示，生成强大的嵌入。随后，通过少样本学习进一步提升性能。我们的评估基于两个知名数据集，专注于网络流量和物联网 (IoT) 环境中的恶意软件识别，结果显示平均准确率达 86.35%，F1 得分为 86.40%，显示出良好的前景。

> As the complexity and connectivity of networks increase, the need for novel malware detection approaches becomes imperative. Traditional security defenses are becoming less effective against the advanced tactics of today's cyberattacks. Deep Packet Inspection (DPI) has emerged as a key technology in strengthening network security, offering detailed analysis of network traffic that goes beyond simple metadata analysis. DPI examines not only the packet headers but also the payload content within, offering a thorough insight into the data traversing the network. This study proposes a novel approach that leverages a large language model (LLM) and few-shot learning to accurately recognizes novel, unseen malware types with few labels samples. Our proposed approach uses a pretrained LLM on known malware types to extract the embeddings from packets. The embeddings are then used alongside few labeled samples of an unseen malware type. This technique is designed to acclimate the model to different malware representations, further enabling it to generate robust embeddings for each trained and unseen classes. Following the extraction of embeddings from the LLM, few-shot learning is utilized to enhance performance with minimal labeled data. Our evaluation, which utilized two renowned datasets, focused on identifying malware types within network traffic and Internet of Things (IoT) environments. Our approach shows promising results with an average accuracy of 86.35% and F1-Score of 86.40% on different malware types across the two datasets.

[Arxiv](https://arxiv.org/abs/2409.11254)