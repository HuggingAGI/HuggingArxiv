# CoMERA：利用秩自适应张量优化，实现高效计算与内存的训练方法

发布时间：2024年05月23日

`LLM理论

理由：这篇论文介绍了一种名为CoMERA的方法，该方法通过秩自适应张量优化来提高大型AI模型（包括大型语言模型）的训练效率。这种方法涉及多目标优化和端到端的秩自适应张量压缩训练，旨在提高计算和内存的效率，同时保持训练精度。这些内容主要关注于大型语言模型训练的理论和方法优化，因此属于LLM理论分类。` `人工智能` `高性能计算`

> CoMERA: Computing- and Memory-Efficient Training via Rank-Adaptive Tensor Optimization

# 摘要

> 训练大型AI模型，如深度学习推荐系统和基础语言（或多模态）模型，耗费巨大，仅大型科技公司能承担，且引发了对环境影响的担忧。本文介绍的CoMERA方法，通过秩自适应张量优化，实现了计算和内存的高效利用。CoMERA采用多目标优化，实现了端到端的秩自适应张量压缩训练，不仅提高了压缩比，还保持了训练精度。通过优化数值计算和GPU实现，CoMERA在GPU上的张量化训练中减少了运行时开销，首次实现了每个训练周期比标准训练快2-3倍。与GaLore相比，CoMERA在单批次训练的六个编码器变压器上，每个训练周期快2倍，内存效率高9倍。通过进一步的高性能计算优化，CoMERA有望大幅降低大型语言模型的训练成本。

> Training large AI models such as deep learning recommendation systems and foundation language (or multi-modal) models costs massive GPUs and computing time. The high training cost has become only affordable to big tech companies, meanwhile also causing increasing concerns about the environmental impact. This paper presents CoMERA, a Computing- and Memory-Efficient training method via Rank-Adaptive tensor optimization. CoMERA achieves end-to-end rank-adaptive tensor-compressed training via a multi-objective optimization formulation, and improves the training to provide both a high compression ratio and excellent accuracy in the training process. Our optimized numerical computation (e.g., optimized tensorized embedding and tensor-vector contractions) and GPU implementation eliminate part of the run-time overhead in the tensorized training on GPU. This leads to, for the first time, $2-3\times$ speedup per training epoch compared with standard training. CoMERA also outperforms the recent GaLore in terms of both memory and computing efficiency. Specifically, CoMERA is $2\times$ faster per training epoch and $9\times$ more memory-efficient than GaLore on a tested six-encoder transformer with single-batch training. With further HPC optimization, CoMERA may significantly reduce the training cost of large language models.

[Arxiv](https://arxiv.org/abs/2405.14377)