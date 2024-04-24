# 专家路由器：通过精准的提示分类，优化语言模型的推理效率。

发布时间：2024年04月22日

`LLM应用` `产业界`

> Expert Router: Orchestrating Efficient Language Model Inference through Prompt Classification

# 摘要

> 大型语言模型（LLMs）因其广泛的适用性和实用性，在科研和产业界备受青睐。但要在大规模部署中实现高效吞吐和低延迟，却面临着巨大挑战，这主要源于LLMs对计算和内存资源的高需求。为克服这一难题，我们设计了“专家路由器”（Expert Router），一个旨在高效协同多个专家模型的系统，以提升模型的扩展能力。专家路由器采用并行推理架构，通过中央路由网关，利用聚类算法智能分配请求。这一策略能够将请求均匀分配至各个LLMs，大幅提升系统的整体处理能力。在多达1000名用户的并发测试中，我们从用户和基础设施两个维度对系统进行了深入评估。测试结果证明，专家路由器在应对高负载情境时表现出色，尤其在用户数量众多时，能够有效提升吞吐率。

> Large Language Models (LLMs) have experienced widespread adoption across scientific and industrial domains due to their versatility and utility for diverse tasks. Nevertheless, deploying and serving these models at scale with optimal throughput and latency remains a significant challenge, primarily because of the high computational and memory demands associated with LLMs. To tackle this limitation, we introduce Expert Router, a system designed to orchestrate multiple expert models efficiently, thereby enhancing scalability. Expert Router is a parallel inference system with a central routing gateway that distributes incoming requests using a clustering method. This approach effectively partitions incoming requests among available LLMs, maximizing overall throughput. Our extensive evaluations encompassed up to 1,000 concurrent users, providing comprehensive insights into the system's behavior from user and infrastructure perspectives. The results demonstrate Expert Router's effectiveness in handling high-load scenarios and achieving higher throughput rates, particularly under many concurrent users.

[Arxiv](https://arxiv.org/abs/2404.15153)