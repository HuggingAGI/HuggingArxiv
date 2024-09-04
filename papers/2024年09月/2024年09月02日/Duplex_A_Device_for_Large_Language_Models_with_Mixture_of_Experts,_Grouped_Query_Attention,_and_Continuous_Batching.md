# Duplex 是一款专为大型语言模型设计的设备，集成了专家混合、分组查询注意力和连续批处理技术，以提升模型性能。

发布时间：2024年09月02日

`LLM理论` `半导体` `人工智能`

> Duplex: A Device for Large Language Models with Mixture of Experts, Grouped Query Attention, and Continuous Batching

# 摘要

> 大型语言模型 (LLM) 因其跨领域生成高质量内容的能力而备受瞩目。为应对其对计算资源需求的激增，混合专家 (MoE) 技术应运而生，通过 MoE 层在较少计算量下利用大量参数。尽管先进连续批处理技术提升了吞吐量，却加剧了 MoE 和注意力层对 DRAM 的频繁访问。传统计算设备在处理这些主导执行时间且算术强度低的层时显得力不从心。仅依赖内存中处理 (PIM) 架构处理 Op/B 波动的 MoE 层颇具挑战。  为此，我们推出 Duplex，结合高-Op/B 定制的 xPU 和 Logic-PIM，实现单设备内高效低-Op/B 操作。Duplex 根据 LLM 各层 Op/B 智能选配处理器。鉴于 MoE 层 Op/B 至少为 1，注意力层在分组查询中为 4-8，传统 PIM 架构因仅适配极低-Op/B 而效率受限。Logic-PIM 通过增设硅通孔 (TSVs)，强化 DRAM 与逻辑芯片间通信，并在逻辑芯片部署强大处理单元，专为处理低至数十的 Op/B 操作。为最大化 xPU 与 Logic-PIM 效能，我们倡导专家与注意力协同处理。

> Large language models (LLMs) have emerged due to their capability to generate high-quality content across diverse contexts. To reduce their explosively increasing demands for computing resources, a mixture of experts (MoE) has emerged. The MoE layer enables exploiting a huge number of parameters with less computation. Applying state-of-the-art continuous batching increases throughput; however, it leads to frequent DRAM access in the MoE and attention layers. We observe that conventional computing devices have limitations when processing the MoE and attention layers, which dominate the total execution time and exhibit low arithmetic intensity (Op/B). Processing MoE layers only with devices targeting low-Op/B such as processing-in-memory (PIM) architectures is challenging due to the fluctuating Op/B in the MoE layer caused by continuous batching.
  To address these challenges, we propose Duplex, which comprises xPU tailored for high-Op/B and Logic-PIM to effectively perform low-Op/B operation within a single device. Duplex selects the most suitable processor based on the Op/B of each layer within LLMs. As the Op/B of the MoE layer is at least 1 and that of the attention layer has a value of 4-8 for grouped query attention, prior PIM architectures are not efficient, which place processing units inside DRAM dies and only target extremely low-Op/B (under one) operations. Based on recent trends, Logic-PIM adds more through-silicon vias (TSVs) to enable high-bandwidth communication between the DRAM die and the logic die and place powerful processing units on the logic die, which is best suited for handling low-Op/B operations ranging from few to a few dozens. To maximally utilize the xPU and Logic-PIM, we propose expert and attention co-processing.

[Arxiv](https://arxiv.org/abs/2409.01141)