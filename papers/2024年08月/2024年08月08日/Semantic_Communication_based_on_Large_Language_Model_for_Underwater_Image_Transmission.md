# 利用大型语言模型实现水下图像的语义通信

发布时间：2024年08月08日

`LLM应用` `海洋研究` `环境监测`

> Semantic Communication based on Large Language Model for Underwater Image Transmission

# 摘要

> 水下通信在环境监测和海洋研究中不可或缺。传统通信方式受限于低带宽和高延迟，而语义通信（SC）通过专注于语义交换，提供了一种创新解决方案。然而，SC在水下环境中的应用面临信息丢失和关键信息传输难题。为此，我们提出了一种基于大型语言模型的语义通信框架，利用视觉LLM对水下图像进行智能压缩和优先级排序。系统通过识别图像中的关键语义元素，高效传输重要信息，同时对非关键区域进行高压缩。接收端采用先进的恢复机制，结合全局和关键区域控制网络，确保图像重建的质量和准确性。实验显示，我们的方法将数据量大幅压缩至原大小的0.8%，且在图像重建质量上显著超越现有技术。

> Underwater communication is essential for environmental monitoring, marine biology research, and underwater exploration. Traditional underwater communication faces limitations like low bandwidth, high latency, and susceptibility to noise, while semantic communication (SC) offers a promising solution by focusing on the exchange of semantics rather than symbols or bits. However, SC encounters challenges in underwater environments, including information loss and difficulties in accurately identifying and transmitting critical information that aligns with the diverse requirements of underwater applications. To address these challenges, we propose a novel Semantic Communication (SC) framework based on Large Language Models (LLMs). Our framework leverages visual LLMs to perform semantic compression and prioritization of underwater image data according to the query from users. By identifying and encoding key semantic elements within the images, the system selectively transmits high-priority information while applying higher compression rates to less critical regions. On the receiver side, an LLM-based recovery mechanism, along with Global Vision ControlNet and Key Region ControlNet networks, aids in reconstructing the images, thereby enhancing communication efficiency and robustness. Our framework reduces the overall data size to 0.8\% of the original. Experimental results demonstrate that our method significantly outperforms existing approaches, ensuring high-quality, semantically accurate image reconstruction.

[Arxiv](https://arxiv.org/abs/2408.12616)