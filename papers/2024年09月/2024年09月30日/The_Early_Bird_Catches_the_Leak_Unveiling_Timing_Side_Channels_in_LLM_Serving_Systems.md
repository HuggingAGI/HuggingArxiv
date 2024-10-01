# 早起的鸟儿捉到漏洞：揭秘 LLM 服务系统中的时间侧通道

发布时间：2024年09月30日

`LLM应用` `网络安全` `人工智能`

> The Early Bird Catches the Leak: Unveiling Timing Side Channels in LLM Serving Systems

# 摘要

> 大型语言模型 (LLM) 的广泛应用，使得优化其推理性能成为迫切需求。当前技术主要通过算法和硬件改进来减少延迟和提高吞吐量，却忽视了多用户环境中的隐私问题。我们首次发现，共享缓存和 GPU 内存分配导致的时间侧通道，可被利用来推断机密系统提示和其他用户的提示，这与传统计算系统的安全挑战相似，凸显了 LLM 服务基础设施中信息泄露的紧迫性。本文介绍了针对 LLM 部署中固有时间侧通道的新攻击策略，特别是针对增强推理性能的键值 (KV) 缓存和语义缓存。我们利用时间测量和分类模型检测缓存命中，使攻击者能高精度推断私人提示，并提出逐字搜索算法，高效恢复缓存中的共享提示前缀，展示窃取系统提示和同行用户提示的可行性。对流行 LLM 服务的黑盒测试表明，这种隐私风险真实存在且后果严重。我们的研究强调，必须采取强有力的措施来保护 LLM 系统免受这些新兴威胁。

> The wide deployment of Large Language Models (LLMs) has given rise to strong demands for optimizing their inference performance. Today's techniques serving this purpose primarily focus on reducing latency and improving throughput through algorithmic and hardware enhancements, while largely overlooking their privacy side effects, particularly in a multi-user environment. In our research, for the first time, we discovered a set of new timing side channels in LLM systems, arising from shared caches and GPU memory allocations, which can be exploited to infer both confidential system prompts and those issued by other users. These vulnerabilities echo security challenges observed in traditional computing systems, highlighting an urgent need to address potential information leakage in LLM serving infrastructures. In this paper, we report novel attack strategies designed to exploit such timing side channels inherent in LLM deployments, specifically targeting the Key-Value (KV) cache and semantic cache widely used to enhance LLM inference performance. Our approach leverages timing measurements and classification models to detect cache hits, allowing an adversary to infer private prompts with high accuracy. We also propose a token-by-token search algorithm to efficiently recover shared prompt prefixes in the caches, showing the feasibility of stealing system prompts and those produced by peer users. Our experimental studies on black-box testing of popular online LLM services demonstrate that such privacy risks are completely realistic, with significant consequences. Our findings underscore the need for robust mitigation to protect LLM systems against such emerging threats.

[Arxiv](https://arxiv.org/abs/2409.20002)