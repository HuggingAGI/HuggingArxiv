# [LLM-PQ方案，针对异构集群环境，采用阶段感知分区与自适应量化技术，有效服务于大型语言模型，提升其在各类集群上的运行效率。](https://arxiv.org/abs/2403.01136)

> LLM-PQ: Serving LLM on Heterogeneous Clusters with Phase-Aware Partition and Adaptive Quantization

发布时间：2024年03月02日

> 近年来LLMs的显著进展使其在多种任务上表现出色，但巨大的模型尺寸也让运行成本与资源需求居高不下。虽然现今普遍采用高端GPU来部署模型，然而，合理利用包含高低容量GPU在内的异构集群有望显著降低成本。遗憾的是，目前主流方案聚焦于同质设备间模型分割与统一压缩，而在异构集群上高效服务LLM的设计尚属空白。本文提出了一项名为LLM-PQ的新系统，它倡导运用自适应模型量化技术和阶段感知分割策略，以优化LLM在异构GPU集群中的服务效率。我们创新性地设计了一套高效的分布式LLM服务算法，巧妙地结合了混合精度量化、阶段感知模型切分及微批次调整，确保既能达到预期的模型质量标准，又能大幅度提升推理处理速度。实验证明，在11个不同集群的实际生产推理场景下，LLM-PQ可将推理吞吐量最高提升至原来的2.88倍（平均提升2.26倍），远超当前最先进成果。

> Recent breakthroughs in Large-scale language models (LLMs) have demonstrated impressive performance on various tasks. The immense sizes of LLMs have led to very high resource demand and cost for running the models. Though the models are largely served using uniform high-caliber GPUs nowadays, utilizing a heterogeneous cluster with a mix of available high- and low-capacity GPUs can potentially substantially reduce the serving cost. There is a lack of designs to support efficient LLM serving using a heterogeneous cluster, while the current solutions focus on model partition and uniform compression among homogeneous devices. This paper proposes LLM-PQ, a system that advocates adaptive model quantization and phase-aware partition to improve LLM serving efficiency on heterogeneous GPU clusters. We carefully decide on mixed-precision model quantization together with phase-aware model partition and micro-batch sizing in distributed LLM serving with an efficient algorithm, to greatly enhance inference throughput while fulfilling user-specified model quality targets. Extensive experiments on production inference workloads in 11 different clusters demonstrate that LLM-PQ achieves up to 2.88x (2.26x on average) throughput improvement in inference, showing great advantages over state-of-the-art works.

`LLM应用`