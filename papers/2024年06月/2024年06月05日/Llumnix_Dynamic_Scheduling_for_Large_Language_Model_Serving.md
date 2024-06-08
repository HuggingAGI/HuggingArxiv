# Llumnix：大型语言模型服务的动态调度策略

发布时间：2024年06月05日

`Agent

这篇论文介绍了一个名为 Llumnix 的系统，该系统通过实时跨模型实例重新调度来优化大型语言模型（LLMs）的推理服务。这种系统设计类似于操作系统中的上下文切换，能够优化负载均衡、隔离资源并区分请求优先级，以确保服务水平目标（SLO）的达成。论文中提到的 Llumnix 系统通过高效的实时迁移机制，在动态调度中统一处理多种场景，显著提升了尾部延迟，加速了高优先级请求，并节省了成本。这种系统的开发和应用属于 Agent 的范畴，因为它涉及创建和管理智能代理以优化和控制 LLMs 的服务。` `云计算` `服务调度`

> Llumnix: Dynamic Scheduling for Large Language Model Serving

# 摘要

> 大型语言模型（LLMs）的推理服务是其在日常生活中发挥潜力的关键。然而，由于请求的异构性和不可预测性，以及LLMs的动态执行特性，高效服务仍是一大挑战。现有系统难以应对这些问题，导致排队延迟严重、尾部延迟差和SLO违规。我们推出的Llumnix系统，通过实时跨模型实例重新调度，有效应对这些挑战。它如同操作系统中的上下文切换，优化负载均衡，隔离资源，区分请求优先级，确保SLO。通过高效的实时迁移机制，Llumnix在动态调度中统一处理多种场景。评估表明，Llumnix显著提升了尾部延迟，加速了高优先级请求，同时节省了成本。该系统已在GitHub上公开。

> Inference serving for large language models (LLMs) is the key to unleashing their potential in people's daily lives. However, efficient LLM serving remains challenging today because the requests are inherently heterogeneous and unpredictable in terms of resource and latency requirements, as a result of the diverse applications and the dynamic execution nature of LLMs. Existing systems are fundamentally limited in handling these characteristics and cause problems such as severe queuing delays, poor tail latencies, and SLO violations.
  We introduce Llumnix, an LLM serving system that reacts to such heterogeneous and unpredictable requests by runtime rescheduling across multiple model instances. Similar to context switching across CPU cores in modern operating systems, Llumnix reschedules requests to improve load balancing and isolation, mitigate resource fragmentation, and differentiate request priorities and SLOs. Llumnix implements the rescheduling with an efficient and scalable live migration mechanism for requests and their in-memory states, and exploits it in a dynamic scheduling policy that unifies the multiple rescheduling scenarios elegantly. Our evaluations show that Llumnix improves tail latencies by an order of magnitude, accelerates high-priority requests by up to 1.5x, and delivers up to 36% cost savings while achieving similar tail latencies, compared against state-of-the-art LLM serving systems. Llumnix is publicly available at https://github.com/AlibabaPAI/llumnix.

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x1.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x2.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x3.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x4.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x5.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x6.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x7.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x8.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x9.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x10.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x11.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x12.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x13.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x14.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x15.png)

![Llumnix：大型语言模型服务的动态调度策略](../../../paper_images/2406.03243/x16.png)

[Arxiv](https://arxiv.org/abs/2406.03243)