# 朝着高性能 LLM 服务迈进：基于模拟来确定最优并行度的方法

发布时间：2024年11月26日

`LLM应用` `计算机系统` `语言模型服务`

> Toward High-Performance LLM Serving: A Simulation-Based Approach for Identifying Optimal Parallelism

# 摘要

> 高效服务大型语言模型（LLMs）已变得极为关键。LLMs 常借助数据、管道和张量并行等技术在多台设备上运行。每种并行方式在计算、内存和通信开销之间均存在权衡，致使确定最优并行执行方案颇具挑战。而且，输入工作负载也会对并行策略产生影响。像文章摘要这类有长提示的任务属于计算密集型，而像代码生成这种生成长度长的任务往往是内存密集型；这些不同特点造就了各异的最优执行方案。鉴于通过实际部署来探寻最优方案成本过高，我们推出了 APEX，这是一款 LLM 服务系统模拟器，能够高效确定最优并行执行方案。APEX 捕捉到了迭代级批处理的复杂特性，这是在最前沿的 LLM 服务系统中广泛运用的技术。APEX 借助 LLMs 的重复结构来缩减设计空间，即便扩展至万亿规模的模型，仍能维持相似的模拟开销。APEX 支持众多的 LLMs、设备集群等，还能通过其高级模板轻松拓展。我们用 CPU 运行 APEX 模拟，并使用 8 个 H100 GPU 评估所确定的最优方案，涵盖了广泛的 LLMs 和输入工作负载。我们表明，就端到端服务延迟而言，APEX 能找到比启发式方案快达 4.42 倍的最优执行方案。APEX 还报告了 LLM 服务系统中使用的一系列指标，如每个输出令牌的时间和到第一个令牌的时间。此外，APEX 能在 15 分钟内通过 CPU 确定最优并行执行方案。这比在 GPU 集群上利用云服务进行实际部署快 71 倍，成本效益高出 1234 倍。APEX 一经被认可将开源。

> Serving Large Language Models (LLMs) efficiently has become crucial. LLMs are often served with multiple devices using techniques like data, pipeline, and tensor parallelisms. Each parallelism presents trade-offs between computation, memory, and communication overhead, making it challenging to determine the optimal parallel execution plan. Moreover, input workloads also impact parallelism strategies. Tasks with long prompts like article summarization are compute-intensive, while tasks with long generation lengths like code generation are often memory-intensive; these differing characteristics result in distinct optimal execution plans. Since searching for the optimal plan via actual deployment is prohibitively expensive, we propose APEX, an LLM serving system simulator that efficiently identifies an optimal parallel execution plan. APEX captures the complex characteristics of iteration-level batching, a technique widely used in SOTA LLM serving systems. APEX leverages the repetitive structure of LLMs to reduce design space, maintaining a similar simulation overhead, even when scaling to trillion scale models. APEX supports a wide range of LLMs, device clusters, etc., and it can be easily extended through its high-level templates. We run APEX simulations using a CPU and evaluate the identified optimal plans using 8 H100 GPUs, encompassing a wide range of LLMs and input workloads. We show that APEX can find optimal execution plans that are up to 4.42x faster than heuristic plans in terms of end-to-end serving latency. APEX also reports a set of metrics used in LLM serving systems, such as time per output token and time to first token. Furthermore, APEX can identify an optimal parallel execution plan within 15 minutes using a CPU. This is 71x faster and 1234x more cost-effective than actual deployment on a GPU cluster using cloud services. APEX will be open-sourced upon acceptance.

[Arxiv](https://arxiv.org/abs/2411.17651)