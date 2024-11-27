# PIM-AI：用于高效 LLM 推理的全新架构

发布时间：2024年11月26日

`LLM应用` `硬件架构` `云服务`

> PIM-AI: A Novel Architecture for High-Efficiency LLM Inference

# 摘要

> 大型语言模型（LLMs）凭借其出色的语言理解和生成能力，在众多应用中已不可或缺。但它们在计算和内存方面的需求，给传统硬件架构带来了严峻挑战。内存处理（PIM）将计算单元直接融入内存芯片，为LLM推理带来诸多优势，比如减少数据传输瓶颈、提升功率效率。
  本文引入了PIM-AI，这是一种新颖的DDR5/LPDDR5 PIM架构，专为LLM推理而设计，无需改动内存控制器或DDR/LPDDR内存PHY。我们开发了一个模拟器，用于评估PIM-AI在各种场景下的性能，并证明了其相较于传统架构的显著优势。在云场景中，依据所采用的LLM模型，与顶尖的GPU相比，PIM-AI能将每秒钟查询的3年总体拥有成本（TCO）最多降低6.94倍。在移动场景中，与先进的移动SoC相比，PIM-AI每个令牌的能耗降低10至20倍，使得每秒查询次数增加25%至45%，每次查询能耗降低6.9倍至13.4倍，延长了电池续航，每次充电能进行更多推理。
  这些成果彰显了PIM-AI在变革LLM部署方面的潜力，使其更高效、更具扩展性和可持续性。

> Large Language Models (LLMs) have become essential in a variety of applications due to their advanced language understanding and generation capabilities. However, their computational and memory requirements pose significant challenges to traditional hardware architectures. Processing-in-Memory (PIM), which integrates computational units directly into memory chips, offers several advantages for LLM inference, including reduced data transfer bottlenecks and improved power efficiency.
  This paper introduces PIM-AI, a novel DDR5/LPDDR5 PIM architecture designed for LLM inference without modifying the memory controller or DDR/LPDDR memory PHY. We have developed a simulator to evaluate the performance of PIM-AI in various scenarios and demonstrate its significant advantages over conventional architectures. In cloud-based scenarios, PIM-AI reduces the 3-year TCO per queries-per-second by up to 6.94x compared to state-of-the-art GPUs, depending on the LLM model used. In mobile scenarios, PIM-AI achieves a 10- to 20-fold reduction in energy per token compared to state-of-the-art mobile SoCs, resulting in 25 to 45~\% more queries per second and 6.9x to 13.4x less energy per query, extending battery life and enabling more inferences per charge.
  These results highlight PIM-AI's potential to revolutionize LLM deployments, making them more efficient, scalable, and sustainable.

[Arxiv](https://arxiv.org/abs/2411.17309)