# 通过带有 LLM 优化器的 DSL 驱动的代码生成来提高并行程序的性能

发布时间：2024年10月21日

`LLM应用` `并行编程` `系统设计`

> Improving Parallel Program Performance Through DSL-Driven Code Generation with LLM Optimizers

# 摘要

> 摘要：在并行编程中，将计算映射到处理器并将数据分配到内存对于实现性能最大化至关重要。这些映射决策是通过性能工程师开发的称为映射器的专门低级系统代码来管理的。每个映射器都是为特定应用量身定制的，并针对底层机器架构进行了优化，这个过程需要专家花费数天的时间进行改进和调整。尽管系统研究取得了进展，但由于要做出数百万个决策以找到最佳解决方案并将其生成为代码的复杂性，自动化映射器生成仍然是一个挑战。我们引入了一种利用基于 LLM 的优化器的最新进展来进行映射器设计的方法。在不到十分钟的时间内，我们的方法自动发现的映射器在科学应用中比人类专家设计的速度快高达 1.34 倍。对于并行矩阵乘法算法，我们的映射器达到了专家设计解决方案的 1.31 倍。为了实现这一目标，我们通过引入一种特定领域语言（DSL）来简化低级代码生成的复杂性，该语言抽象了低级系统编程细节，并为 LLM 定义了一个结构化的搜索空间进行探索。为了最大限度地提高应用程序性能，我们使用 LLM 优化器来改进生成映射器代码的代理系统。因此，这种方法大大减轻了性能工程师的工作量，同时在各种应用中实现了显著的性能提升。最后，我们的结果证明了基于 LLM 的优化在系统设计中的有效性，并表明其在解决其他复杂系统挑战方面的潜力。

> 
Abstract:Mapping computations to processors and assigning data to memory are critical for maximizing performance in parallel programming. These mapping decisions are managed through the development of specialized low-level system code, called mappers, crafted by performance engineers. Each mapper is tailored to a specific application and optimized for the underlying machine architecture, a process that requires days of refinement and tuning from an expert. Despite advances in system research, automating mapper generation remains a challenge due to the complexity of making millions of decisions to find the optimal solution and generate the solution as code. We introduce an approach that leverages recent advances in LLM-based optimizers for mapper design. In under ten minutes, our method automatically discovers mappers that surpass human expert designs in scientific applications by up to 1.34X speedup. For parallel matrix multiplication algorithms, our mapper achieves up to 1.31X of the expert-designed solution. To achieve this, we simplify the complexity of low-level code generation by introducing a domain-specific language (DSL) that abstracts the low-level system programming details and defines a structured search space for LLMs to explore. To maximize the application performance, we use an LLM optimizer to improve an agentic system that generates the mapper code. As a result, this approach significantly reduces the workload for performance engineers while achieving substantial performance gains across diverse applications. Finally, our results demonstrate the effectiveness of LLM-based optimization in system design and suggest its potential for addressing other complex system challenges.
    

[Arxiv](https://arxiv.org/pdf/2410.15625)