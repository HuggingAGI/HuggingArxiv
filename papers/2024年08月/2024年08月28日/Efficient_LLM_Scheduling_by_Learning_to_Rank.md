# 学习排序以优化 LLM 调度效率

发布时间：2024年08月28日

`LLM应用` `信息技术` `人工智能`

> Efficient LLM Scheduling by Learning to Rank

# 摘要

> 在大语言模型（LLM）推理中，请求的输出长度通常被视为未知。这导致多数服务系统采用先到先服务（FCFS）策略，引发队头阻塞，降低吞吐量和服务质量。本文中，我们挑战这一假设，证明尽管无法精确预测每个请求的生成长度，但通过学习排序，可以预测一批请求中输出长度的相对顺序。这一排序信息对请求调度至关重要。基于此，我们设计了一种新型调度器，能更优地实现最短作业优先（SJF）调度。结合最先进的LLM服务系统，我们在多个关键应用中实现了显著性能提升：聊天机器人服务延迟降低2.8倍，合成数据生成吞吐量提升6.5倍。代码已公开于https://github.com/hao-ai-lab/vllm-ltr.git。

> In Large Language Model (LLM) inference, the output length of an LLM request is typically regarded as not known a priori. Consequently, most LLM serving systems employ a simple First-come-first-serve (FCFS) scheduling strategy, leading to Head-Of-Line (HOL) blocking and reduced throughput and service quality. In this paper, we reexamine this assumption -- we show that, although predicting the exact generation length of each request is infeasible, it is possible to predict the relative ranks of output lengths in a batch of requests, using learning to rank. The ranking information offers valuable guidance for scheduling requests. Building on this insight, we develop a novel scheduler for LLM inference and serving that can approximate the shortest-job-first (SJF) schedule better than existing approaches. We integrate this scheduler with the state-of-the-art LLM serving system and show significant performance improvement in several important applications: 2.8x lower latency in chatbot serving and 6.5x higher throughput in synthetic data generation. Our code is available at https://github.com/hao-ai-lab/vllm-ltr.git

[Arxiv](https://arxiv.org/abs/2408.15792)