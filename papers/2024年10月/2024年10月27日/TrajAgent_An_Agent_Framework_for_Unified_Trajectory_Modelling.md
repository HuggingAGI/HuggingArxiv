# TrajAgent：一个用于统一轨迹建模的代理框架

发布时间：2024年10月27日

`Agent` `公共管理`

> TrajAgent: An Agent Framework for Unified Trajectory Modelling

# 摘要

> 轨迹建模涵盖轨迹数据模式挖掘及未来预测等方面的研究，在生活服务、城市交通和公共管理等领域应用广泛。针对轨迹建模的特定问题，已涌现出众多方法。但鉴于数据的异质性和轨迹任务的多样性，达成统一的轨迹建模仍是重要且具挑战性的任务。本文中，我们提出了 TrajAgent，一个基于大型语言模型的智能体框架，用于统一各类轨迹建模任务。在 TrajAgent 里，我们首先开发了 UniEnv，这是一个具备统一数据和模型接口的执行环境，用于支持各种模型的执行与训练。以 UniEnv 为基础，我们引入了 TAgent，这是为各类轨迹任务的自动轨迹建模而设计的智能体工作流。具体而言，我们在 TAgent 中设计了 AutOpt，这是一个系统优化模块，能进一步提升集成模型的性能。输入自然语言表述的各类轨迹任务后，TrajAgent 会通过训练和执行合适的模型自动生成出色的结果。在四个真实世界数据集上的四个任务中开展的大量实验表明，TrajAgent 在统一轨迹建模方面成效显著，与基线方法相比，平均性能提升了 15.43%。

> Trajectory modeling, which includes research on trajectory data pattern mining and future prediction, has widespread applications in areas such as life services, urban transportation, and public administration. Numerous methods have been proposed to address specific problems within trajectory modelling. However, due to the heterogeneity of data and the diversity of trajectory tasks, achieving unified trajectory modelling remains an important yet challenging task. In this paper, we propose TrajAgent, a large language model-based agentic framework, to unify various trajectory modelling tasks. In TrajAgent, we first develop UniEnv, an execution environment with a unified data and model interface, to support the execution and training of various models. Building on UniEnv, we introduce TAgent, an agentic workflow designed for automatic trajectory modelling across various trajectory tasks. Specifically, we design AutOpt, a systematic optimization module within TAgent, to further improve the performance of the integrated model. With diverse trajectory tasks input in natural language, TrajAgent automatically generates competitive results via training and executing appropriate models. Extensive experiments on four tasks using four real-world datasets demonstrate the effectiveness of TrajAgent in unified trajectory modelling, achieving an average performance improvement of 15.43% over baseline methods.

[Arxiv](https://arxiv.org/abs/2410.20445)