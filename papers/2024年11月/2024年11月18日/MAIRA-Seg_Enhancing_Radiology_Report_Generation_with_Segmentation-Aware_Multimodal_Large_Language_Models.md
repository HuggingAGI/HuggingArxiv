# MAIRA-Seg：借助具有分割感知能力的多模态大型语言模型来强化放射学报告的生成

发布时间：2024年11月18日

`LLM应用` `放射学` `人工智能`

> MAIRA-Seg: Enhancing Radiology Report Generation with Segmentation-Aware Multimodal Large Language Models

# 摘要

> 如今，将人工智能用于放射学报告生成，尤其是针对胸部 X 光（CXRs）这方面，人们的兴趣愈发浓厚。本文探究了借助分割掩码纳入像素级信息能否提升多模态大型语言模型（MLLMs）在放射学报告生成中的细粒度图像解读能力。我们推出了 MAIRA-Seg，这是一个具备分割意识的 MLLM 框架，旨在结合语义分割掩码与 CXRs 来生成放射学报告。我们训练了专家分割模型，以获取 CXRs 中放射学特定结构的掩码伪标签。接着，基于 MAIRA（一个专门用于报告生成的 CXR 模型）的架构，我们整合了一个可训练的分割令牌提取器，它能利用这些掩码伪标签，并通过掩码感知提示来生成放射学报告草案。在公开的 MIMIC-CXR 数据集上进行的实验表明，MAIRA-Seg 优于非分割基线。我们还对 MAIRA 的标记集提示进行了研究，发现 MAIRA-Seg 始终展现出相当或更优的性能。这些结果证实，使用分割掩码增强了 MLLMs 的精细推理能力，有可能助力实现更优的临床效果。

> There is growing interest in applying AI to radiology report generation, particularly for chest X-rays (CXRs). This paper investigates whether incorporating pixel-level information through segmentation masks can improve fine-grained image interpretation of multimodal large language models (MLLMs) for radiology report generation. We introduce MAIRA-Seg, a segmentation-aware MLLM framework designed to utilize semantic segmentation masks alongside CXRs for generating radiology reports. We train expert segmentation models to obtain mask pseudolabels for radiology-specific structures in CXRs. Subsequently, building on the architectures of MAIRA, a CXR-specialised model for report generation, we integrate a trainable segmentation tokens extractor that leverages these mask pseudolabels, and employ mask-aware prompting to generate draft radiology reports. Our experiments on the publicly available MIMIC-CXR dataset show that MAIRA-Seg outperforms non-segmentation baselines. We also investigate set-of-marks prompting with MAIRA and find that MAIRA-Seg consistently demonstrates comparable or superior performance. The results confirm that using segmentation masks enhances the nuanced reasoning of MLLMs, potentially contributing to better clinical outcomes.

[Arxiv](https://arxiv.org/abs/2411.11362)