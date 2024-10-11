# COMMA：一个多模态多代理的交流基准

发布时间：2024年10月09日

`Agent` `人工智能` `多模态系统`

> COMMA: A Communicative Multimodal Multi-Agent Benchmark

# 摘要

> 多模态代理在大型基础模型上的快速发展，却忽略了其在协作任务中基于语言的沟通潜力。这导致了对其实际应用中有效性的理解存在关键空白，尤其是在与人类互动时。现有基准未能充分评估代理间沟通和协作的关键方面，特别是在信息不对等且需协同完成复杂任务的场景中。为此，我们推出了一款新基准，旨在通过语言沟通全面评估多模态多代理系统的协作性能。该基准涵盖多种场景，从四个关键维度评估代理能力。测试结果显示，包括GPT-4o在内的顶尖模型在代理间协作中表现不佳，仅在有人类参与时才略胜随机基线。

> The rapid advances of multi-modal agents built on large foundation models have largely overlooked their potential for language-based communication between agents in collaborative tasks. This oversight presents a critical gap in understanding their effectiveness in real-world deployments, particularly when communicating with humans. Existing agentic benchmarks fail to address key aspects of inter-agent communication and collaboration, particularly in scenarios where agents have unequal access to information and must work together to achieve tasks beyond the scope of individual capabilities. To fill this gap, we introduce a novel benchmark designed to evaluate the collaborative performance of multimodal multi-agent systems through language communication. Our benchmark features a variety of scenarios, providing a comprehensive evaluation across four key categories of agentic capability in a communicative collaboration setting. By testing both agent-agent and agent-human collaborations using open-source and closed-source models, our findings reveal surprising weaknesses in state-of-the-art models, including proprietary models like GPT-4o. These models struggle to outperform even a simple random agent baseline in agent-agent collaboration and only surpass the random baseline when a human is involved.

[Arxiv](https://arxiv.org/abs/2410.07553)