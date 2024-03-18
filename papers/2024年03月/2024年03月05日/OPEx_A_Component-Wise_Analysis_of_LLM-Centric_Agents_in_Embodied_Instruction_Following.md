# OPEx研究针对具身指令跟随任务中以大型语言模型（LLM）为核心的智能体，对其进行深入的组件级分析。

发布时间：2024年03月05日

`Agent`

> OPEx: A Component-Wise Analysis of LLM-Centric Agents in Embodied Instruction Following

> 具身学习中的具身指令跟随(EIF)任务至关重要，它要求智能体通过第一人称视角与环境互动，实现对自然语言指令的执行。近期，采用大型语言模型(LLMs)并聚焦于框架中心化方法的趋势在EIF及其它具身学习任务中取得了性能突破。然而，对于从视觉感知至动作执行等不同环节对任务表现的具体影响，尚缺乏系统性的认知。为此，我们提出了一套全面的框架——OPEx，该框架明确了解决具身学习任务必备的三大核心组件：观察模块、规划模块和执行模块。经过广泛而深入的评估，我们揭示了各组件如何具体作用于EIF任务的表现。同时，我们还在该领域进行了创新尝试，将多智能体对话策略应用于TextWorld平台，进而提升了任务性能。研究结果显示，以LLM为核心的设计极大地优化了EIF任务成果，识别出视觉感知和底层动作执行是制约性能的关键瓶颈，并证实了通过整合多智能体框架强化LLMs能更上一层楼地提升性能。

> Embodied Instruction Following (EIF) is a crucial task in embodied learning, requiring agents to interact with their environment through egocentric observations to fulfill natural language instructions. Recent advancements have seen a surge in employing large language models (LLMs) within a framework-centric approach to enhance performance in embodied learning tasks, including EIF. Despite these efforts, there exists a lack of a unified understanding regarding the impact of various components-ranging from visual perception to action execution-on task performance. To address this gap, we introduce OPEx, a comprehensive framework that delineates the core components essential for solving embodied learning tasks: Observer, Planner, and Executor. Through extensive evaluations, we provide a deep analysis of how each component influences EIF task performance. Furthermore, we innovate within this space by deploying a multi-agent dialogue strategy on a TextWorld counterpart, further enhancing task performance. Our findings reveal that LLM-centric design markedly improves EIF outcomes, identify visual perception and low-level action execution as critical bottlenecks, and demonstrate that augmenting LLMs with a multi-agent framework further elevates performance.

[Arxiv](https://arxiv.org/abs/2403.03017)