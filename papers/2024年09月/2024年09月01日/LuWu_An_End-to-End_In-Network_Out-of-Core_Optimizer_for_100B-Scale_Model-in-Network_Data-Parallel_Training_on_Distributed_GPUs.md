# LuWu：一款端到端网络内核外优化工具，专为分布式GPU上的100亿级模型-网络数据并行训练设计。

发布时间：2024年09月01日

`LLM理论` `计算机科学` `高性能计算`

> LuWu: An End-to-End In-Network Out-of-Core Optimizer for 100B-Scale Model-in-Network Data-Parallel Training on Distributed GPUs

# 摘要

> 大型语言模型的最新进展为全球带来了广阔的应用前景。随着模型规模的不断扩大，多GPU训练成为必要，而数据并行因其简单高效的特点成为主流的分布式训练策略。尽管当前系统通过模型分片实现了内存高效训练，但在具有高带宽的商用GPU集群上，由于集体操作与GPU计算的严重干扰以及CPU优化器的沉重开销，现有系统未能充分利用GPU资源。近期研究提出了网络内聚合以减轻网络压力，但与模型分片不兼容。为此，我们创新性地提出了LuWu，一种网络内优化器，能够在分布式GPU上高效训练100B规模的模型。LuWu保持了与模型分片数据并行相似的通信模式，但通过集中的网络内优化器执行，实现了优化器状态和参数的卸载，以及集体通信的SmartNIC-SmartSwitch协同优化。实验表明，在8节点集群上训练175B模型时，LuWu的性能比现有最先进系统提升了3.98倍。

> The recent progress made in large language models (LLMs) has brought tremendous application prospects to the world. The growing model size demands LLM training on multiple GPUs, while data parallelism is the most popular distributed training strategy due to its simplicity, efficiency, and scalability. Current systems adopt the model-sharded data parallelism to enable memory-efficient training, however, existing model-sharded data-parallel systems fail to efficiently utilize GPU on a commodity GPU cluster with 100 Gbps (or 200 Gbps) inter-GPU bandwidth due to 1) severe interference between collective operation and GPU computation and 2) heavy CPU optimizer overhead. Recent works propose in-network aggregation (INA) to relieve the network bandwidth pressure in data-parallel training, but they are incompatible with model sharding due to the network design. To this end, we propose LuWu, a novel in-network optimizer that enables efficient model-in-network data-parallel training of a 100B-scale model on distributed GPUs. Such new data-parallel paradigm keeps a similar communication pattern as model-sharded data parallelism but with a centralized in-network optimizer execution. The key idea is to offload the entire optimizer states and parameters from GPU workers onto an in-network optimizer node and to offload the entire collective communication from GPU-implemented NCCL to SmartNIC-SmartSwitch co-optimization. The experimental results show that LuWu outperforms the state-of-the-art training system by 3.98x when training on a 175B model on an 8-worker cluster.

[Arxiv](https://arxiv.org/abs/2409.00918)