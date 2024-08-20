# 探索分布式Transformer模型的通信奥秘

发布时间：2024年08月19日

`LLM理论` `计算机科学`

> Demystifying the Communication Characteristics for Distributed Transformer Models

# 摘要

> 基于transformer的深度学习模型，如LLMs、视觉transformer等，已彻底改变多个领域。尽管分布式训练推动了这些进步，但通信仍是瓶颈。本文探讨了transformer模型在多节点/多GPU训练中的通信模式，以GPT模型为例。通过分析通信日志，我们发现需进一步优化小消息通信，并揭示了序列长度、吞吐量、模型大小与优化间的关联，为框架和中间件优化指明了方向。

> Deep learning (DL) models based on the transformer architecture have revolutionized many DL applications such as large language models (LLMs), vision transformers, audio generation, and time series prediction. Much of this progress has been fueled by distributed training, yet distributed communication remains a substantial bottleneck to training progress. This paper examines the communication behavior of transformer models - that is, how different parallelism schemes used in multi-node/multi-GPU DL Training communicate data in the context of transformers. We use GPT-based language models as a case study of the transformer architecture due to their ubiquity. We validate the empirical results obtained from our communication logs using analytical models. At a high level, our analysis reveals a need to optimize small message point-to-point communication further, correlations between sequence length, per-GPU throughput, model size, and optimizations used, and where to potentially guide further optimizations in framework and HPC middleware design and optimization.

[Arxiv](https://arxiv.org/abs/2408.10197)