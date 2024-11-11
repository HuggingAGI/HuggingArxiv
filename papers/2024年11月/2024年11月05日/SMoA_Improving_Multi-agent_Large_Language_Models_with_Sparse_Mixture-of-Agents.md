# SMoA：使用稀疏的多智能体混合来改进多智能体大型语言模型

发布时间：2024年11月05日

`Agent` `多智能体系统` `语言模型`

> SMoA: Improving Multi-agent Large Language Models with Sparse Mixture-of-Agents

# 摘要

> 虽然多智能体系统已被证明能在各种任务和应用中显著提高大型语言模型（LLM）的性能，但智能体之间的密集交互可能会阻碍其效率和多样性。为了应对这些挑战，我们从稀疏智能体混合（SMoE）中获得灵感，并提出了一个稀疏智能体混合（SMoA）框架，以提高多智能体LLM的效率和多样性。与完全连接的结构不同，SMoA引入了新颖的响应选择和提前停止机制，以使各个LLM智能体之间的信息流稀疏化，在性能和效率之间取得平衡。此外，受SMoE框架中专家多样性原则的启发，以平衡专家之间的工作负载，我们为每个LLM智能体分配了不同的角色描述，促进了多样化和发散性思维。在推理、对齐和公平基准上的大量实验表明，SMoA实现了与传统智能体混合方法相当的性能，但计算成本显著降低。进一步的分析表明，SMoA更稳定，具有更大的扩展能力，并通过超参数优化具有相当大的潜力。代码和数据将在：https://github.com/David-Li0406/SMoA 提供。

> While multi-agent systems have been shown to significantly enhance the performance of Large Language Models (LLMs) across various tasks and applications, the dense interaction between scaling agents potentially hampers their efficiency and diversity. To address these challenges, we draw inspiration from the sparse mixture-of-agents (SMoE) and propose a sparse mixture-of-agents (SMoA) framework to improve the efficiency and diversity of multi-agent LLMs. Unlike completely connected structures, SMoA introduces novel Response Selection and Early Stopping mechanisms to sparsify information flows among individual LLM agents, striking a balance between performance and efficiency. Additionally, inspired by the expert diversity principle in SMoE frameworks for workload balance between experts, we assign distinct role descriptions to each LLM agent, fostering diverse and divergent thinking. Extensive experiments on reasoning, alignment, and fairness benchmarks demonstrate that SMoA achieves performance comparable to traditional mixture-of-agents approaches but with significantly lower computational costs. Further analysis reveals that SMoA is more stable, has a greater capacity to scale, and offers considerable potential through hyper-parameter optimization. Code and data will be available at: https://github.com/David-Li0406/SMoA.

[Arxiv](https://arxiv.org/abs/2411.03284)