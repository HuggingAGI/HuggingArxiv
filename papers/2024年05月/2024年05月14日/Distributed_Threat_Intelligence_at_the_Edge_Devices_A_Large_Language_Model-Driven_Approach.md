# 大型语言模型驱动的边缘设备分布式威胁情报策略在边缘设备上，分布式威胁情报的收集与分析正成为网络安全的新前沿。本文提出了一种基于大型语言模型的创新方法，旨在提升威胁情报的实时处理能力，并增强网络防御的智能化水平。通过这种方法，我们能够更有效地识别和响应潜在的安全威胁，确保网络环境的安全稳定。

发布时间：2024年05月14日

`Agent

这篇论文探讨了在边缘设备上部署去中心化的威胁情报系统，并结合大型语言模型的上下文学习功能来增强网络安全。这种方法涉及在边缘设备上直接部署轻量级机器学习模型，并利用LLM服务器来提高威胁检测的准确性。此外，它还通过协作学习机制促进设备间的安全知识共享，实现动态威胁应对。这种自主适应新威胁、实时分析本地数据并与其他设备协作的系统，符合Agent的定义，即一个能够感知环境、做出决策并执行动作的实体。因此，这篇论文应归类为Agent。` `网络安全` `边缘计算`

> Distributed Threat Intelligence at the Edge Devices: A Large Language Model-Driven Approach

# 摘要

> 随着边缘设备的普及，其面临的攻击面也随之扩大。通过在边缘设备上部署去中心化的威胁情报，并结合大型语言模型的上下文学习功能等机器学习技术，我们探索了一种增强低功耗设备网络安全的新途径。该方法将轻量级机器学习模型直接部署于边缘设备，实时分析网络流量和系统日志等本地数据。同时，将计算任务分散至边缘服务器，不仅降低了延迟，提升了响应速度，还通过本地处理敏感数据保护了隐私。LLM服务器赋予边缘服务器自主适应新威胁的能力，不断优化模型以提高威胁检测的准确性，减少误报。协作学习机制则促进了边缘设备间的安全知识共享，增强了网络的整体智能，并实现了动态的威胁应对措施，如在检测到异常时自动隔离设备。这种方法的灵活性和可扩展性使其成为应对多样化网络环境的理想选择，边缘设备仅在发现可疑活动时上报，为抵御网络边缘的新兴威胁提供了高效且有弹性的解决方案。我们的框架通过隔离边缘设备，有效提升了边缘计算的安全性，为网络威胁的检测与缓解提供了更为坚实的保障。

> With the proliferation of edge devices, there is a significant increase in attack surface on these devices. The decentralized deployment of threat intelligence on edge devices, coupled with adaptive machine learning techniques such as the in-context learning feature of large language models (LLMs), represents a promising paradigm for enhancing cybersecurity on low-powered edge devices. This approach involves the deployment of lightweight machine learning models directly onto edge devices to analyze local data streams, such as network traffic and system logs, in real-time. Additionally, distributing computational tasks to an edge server reduces latency and improves responsiveness while also enhancing privacy by processing sensitive data locally. LLM servers can enable these edge servers to autonomously adapt to evolving threats and attack patterns, continuously updating their models to improve detection accuracy and reduce false positives. Furthermore, collaborative learning mechanisms facilitate peer-to-peer secure and trustworthy knowledge sharing among edge devices, enhancing the collective intelligence of the network and enabling dynamic threat mitigation measures such as device quarantine in response to detected anomalies. The scalability and flexibility of this approach make it well-suited for diverse and evolving network environments, as edge devices only send suspicious information such as network traffic and system log changes, offering a resilient and efficient solution to combat emerging cyber threats at the network edge. Thus, our proposed framework can improve edge computing security by providing better security in cyber threat detection and mitigation by isolating the edge devices from the network.

[Arxiv](https://arxiv.org/abs/2405.08755)