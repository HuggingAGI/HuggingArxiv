# MemServe：弹性内存池支持的分解式LLM服务上下文缓存方案

发布时间：2024年06月25日

`LLM应用

理由：这篇论文主要讨论了大型语言模型服务的技术优化，特别是通过开发MemServe系统来优化性能，包括上下文缓存和解耦推理技术的应用。这些内容直接关联到大型语言模型的实际应用层面，涉及系统架构设计和性能优化，因此属于LLM应用分类。` `云计算` `分布式系统`

> MemServe: Context Caching for Disaggregated LLM Serving with Elastic Memory Pool

# 摘要

> 大型语言模型服务已进化为有状态系统，通过上下文缓存和解耦推理技术优化性能。这种转变要求新的架构设计。我们开发的MemServe系统，巧妙融合了请求间与请求内的优化，并创新性地引入了MemPool——一个弹性内存池，有效管理分布式内存和KV缓存。借助MemPool API，MemServe首次实现了上下文缓存与解耦推理的结合，并由全局调度器通过全局提示树的局部感知策略提升缓存利用率。实测数据显示，MemServe大幅缩短了作业完成时间和首次响应时间。

> Large language model (LLM) serving has transformed from stateless to stateful systems, utilizing techniques like context caching and disaggregated inference. These optimizations extend the lifespan and domain of the KV cache, necessitating a new architectural approach. We present MemServe, a unified system that integrates both inter-request and intra-request optimizations. MemServe introduces MemPool, an elastic memory pool managing distributed memory and KV caches across serving instances. Using MemPool APIs, MemServe combines context caching with disaggregated inference for the first time, supported by a global scheduler that enhances cache reuse through a global prompt tree-based locality-aware policy. Tests show that MemServe significantly improves job completion time and time-to-first-time.

[Arxiv](https://arxiv.org/abs/2406.17565)