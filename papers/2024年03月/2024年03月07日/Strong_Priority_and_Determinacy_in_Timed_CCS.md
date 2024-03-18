# [针对定时进程演算（Timed CCS）中体现的强优先级与确定性进行深入探讨，揭示其内在机制与影响。步骤 1 翻译：Strong Priority and Determinacy in Timed Calculus of Communicating Systems (CCS)步骤 2 翻译：在通信系统计时演算（Timed CCS）中，强优先级与确定性的概念具有重要价值。本研究致力于阐述并剖析这两个特性在处理实时交互过程中的作用及其对系统行为的深刻影响。](https://arxiv.org/abs/2403.04618)

发布时间：2024年03月07日

`LLM理论`

> Strong Priority and Determinacy in Timed CCS

> 我们在经典过程代数优先级理论基础上，创新性地提出了“顺序构造性简化”这一调度机制，以揭示同步编程的核心理念。此策略独到之处在于确保多播并发通信的确定性构造。特别是在加入了时钟与优先级拓展的CCS技术环境中，我们针对一类被称作“结构连贯”的大量进程，论证了其在构造性简化下的汇合属性。更进一步，我们发现在满足特定语法约束，即“可枢轴化”条件下，前缀、求和、并行组合、限制和隐藏等运算符都能够保持结构连贯性。这一发现使得我们的研究范围超越了仅在无优先级经典CCS理论中汇合的进程类别。

> Building on the classical theory of process algebra with priorities, we identify a new scheduling mechanism, called "sequentially constructive reduction" which is designed to capture the essence of synchronous programming. The distinctive property of this evaluation strategy is to achieve determinism-by-construction for multi-cast concurrent communication. In particular, it permits us to model shared memory multi-threading with reaction to absence as it lies at the core of the programming language Esterel. In the technical setting of CCS extended by clocks and priorities, we prove for a large class of processes, which we call "structurally coherent" the confluence property for constructive reductions. We further show that under some syntactic restrictions, called "pivotable" the operators of prefix, summation, parallel composition, restriction and hiding preserve structural coherence. This covers a strictly larger class of processes compared to those that are confluent in Milner's classical theory of CCS without priorities.

[Arxiv](https://arxiv.org/abs/2403.04618)