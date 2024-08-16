# P/D-Serve：高效服务大规模分解式大型语言模型

发布时间：2024年08月15日

`LLM应用` `人工智能` `云计算`

> P/D-Serve: Serving Disaggregated Large Language Model at Scale

# 摘要

> 在数以万计的xPU设备上高效运行分散式大型语言模型面临多重挑战。首先，简单混合处理所有提示无法应对多样性问题，需精细组织以优化P/D处理和动态调整比例。其次，工作负载估算不准确导致预填充阶段频繁超时。再者，固定块的D2D KVCache传输未能充分利用RDMA技术。为此，我们提出了P/D-Serve系统，它遵循MLOps原则，通过精细P/D组织、按需转发和优化D2D传输，显著提升了E2E性能。该系统已在数万台NPU上稳定运行超八个月，实现了吞吐量、响应时间和传输效率的大幅提升，相较于传统聚合LLM，其吞吐量更是翻了六倍多。

> Serving disaggregated large language models (LLMs) over tens of thousands of xPU devices (GPUs or NPUs) with reliable performance faces multiple challenges. 1) Ignoring the diversity (various prefixes and tidal requests), treating all the prompts in a mixed pool is inadequate. To facilitate the similarity per scenario and minimize the inner mismatch on P/D (prefill and decoding) processing, fine-grained organization is required, dynamically adjusting P/D ratios for better performance. 2) Due to inaccurate estimation on workload (queue status or maintained connections), the global scheduler easily incurs unnecessary timeouts in prefill. 3) Block-fixed device-to-device (D2D) KVCache transfer over cluster-level RDMA (remote direct memory access) fails to achieve desired D2D utilization as expected. To overcome previous problems, this paper proposes an end-to-end system P/D-Serve, complying with the paradigm of MLOps (machine learning operations), which models end-to-end (E2E) P/D performance and enables: 1) fine-grained P/D organization, mapping the service with RoCE (RDMA over converged ethernet) as needed, to facilitate similar processing and dynamic adjustments on P/D ratios; 2) on-demand forwarding upon rejections for idle prefill, decoupling the scheduler from regular inaccurate reports and local queues, to avoid timeouts in prefill; and 3) efficient KVCache transfer via optimized D2D access. P/D-Serve is implemented upon Ascend and MindSpore, has been deployed over tens of thousands of NPUs for more than eight months in commercial use, and further achieves 60\%, 42\% and 46\% improvements on E2E throughput, time-to-first-token (TTFT) SLO (service level objective) and D2D transfer time. As the E2E system with optimizations, P/D-Serve achieves 6.7x increase on throughput, compared with aggregated LLMs.

[Arxiv](https://arxiv.org/abs/2408.08147)