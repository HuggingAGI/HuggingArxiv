# BlockLLM：为大型语言模型打造多租户精细化服务

发布时间：2024年04月28日

`LLM应用` `深度学习服务` `区块链`

> BlockLLM: Multi-tenant Finer-grained Serving for Large Language Models

# 摘要

> 随着大型语言模型（LLM）在多种应用中的广泛需求，深度学习服务系统的设计思路经历了一次重大变革。尤其在多租户环境下部署LLM面临着计算和内存需求高的挑战。为此，我们推出了BlockLLM，这是一款服务系统，它通过在微调后的LLM模型间共享组件，为LLM工作负载提供了一种既高效又灵活的处理方案。BlockLLM通过将模型划分为更细致的区块，实现了模型组件的复用和独立配置，优化了计算效率。系统包含一个用于存储区块的离线区块库和一个通过区块链处理请求的在线服务系统。BlockLLM展现了多重灵活性：(1) 利用区块库中的等价评估，实现了区块链的即时自适应组装；(2) 支持每个区块的批处理大小，并在各个区块级别上实施了最优的KV缓存协调；(3) 采用预测执行和本地感知的区块放置策略，以减少动态区块资源分配带来的通信开销。我们的评估结果证明，BlockLLM在减少内存和存储占用、提升计算效率方面表现卓越，与现有服务方法相比，在95%的延迟和GPU利用率上分别提升了33.5%和20.1%。

> The growing demand for Large Language Models (LLMs) across diverse applications has prompted a paradigm shift in the design of deep learning serving systems. Deploying LLMs, especially in multi-tenant environments, presents considerable challenges due to their high computational and memory demands. We present BlockLLM, a serving system that exploits the potential of sharing components among fine-tuned LLM models to offer an efficient and flexible solution for LLM workloads. BlockLLM partitions the models into finer-grained blocks to enable the reuse of model components and independent provisioning to improve the computation efficiency. BlockLLM consists of an offline block zoo, for storing the blocks, and an online system to serve the requests through chains of blocks. It offers multi-fold flexibility: (1) Adaptive assembly of block chains on-the-fly is achieved with the help of equivalence evaluation among blocks in the zoo. (2) We enable per-block batch size and configure best-effort KV cache coordination at individual block level. (3) We adopt speculative execution and locality-aware block placement to mitigate the communication costs from dynamic block resource allocation. Our evaluation demonstrates that BlockLLM reduces memory and storage footprints and improves computation efficiency, outperforming existing serving approach in 95\%ile latency and GPU utilization by 33.5\% and 20.1\%, respectively.

[Arxiv](https://arxiv.org/abs/2404.18322)