# 利用优化后的 BERT 模型，在 5G 生态系统中实现高效的联邦入侵检测

发布时间：2024年09月28日

`LLM应用` `网络安全` `物联网`

> Efficient Federated Intrusion Detection in 5G ecosystem using optimized BERT-based model

# 摘要

> 5G 技术不仅支持智能交通、互联医疗和智慧城市等先进应用，还带来了严峻的安全挑战。本文提出了一种结合联邦学习和大型语言模型 (LLM) 的入侵检测系统 (IDS)，核心采用 BERT 变压器模型识别恶意网络流量。我们优化了该模型在边缘设备上的性能，实验结果显示，在集中式环境中，推理准确率达 97.79%；在联邦学习环境中，通过 IID 和非 IID 数据训练，确保数据隐私和合规性。此外，我们通过线性量化压缩模型，使其在边缘设备上部署时，模型大小减少 28.74%，准确率仅下降 0.02%。这些成果展示了 LLM 在资源受限的 IoT 设备上运行的巨大潜力。

> The fifth-generation (5G) offers advanced services, supporting applications such as intelligent transportation, connected healthcare, and smart cities within the Internet of Things (IoT). However, these advancements introduce significant security challenges, with increasingly sophisticated cyber-attacks. This paper proposes a robust intrusion detection system (IDS) using federated learning and large language models (LLMs). The core of our IDS is based on BERT, a transformer model adapted to identify malicious network flows. We modified this transformer to optimize performance on edge devices with limited resources. Experiments were conducted in both centralized and federated learning contexts. In the centralized setup, the model achieved an inference accuracy of 97.79%. In a federated learning context, the model was trained across multiple devices using both IID (Independent and Identically Distributed) and non-IID data, based on various scenarios, ensuring data privacy and compliance with regulations. We also leveraged linear quantization to compress the model for deployment on edge devices. This reduction resulted in a slight decrease of 0.02% in accuracy for a model size reduction of 28.74%. The results underscore the viability of LLMs for deployment in IoT ecosystems, highlighting their ability to operate on devices with constrained computational and storage resources.

[Arxiv](https://arxiv.org/abs/2409.19390)