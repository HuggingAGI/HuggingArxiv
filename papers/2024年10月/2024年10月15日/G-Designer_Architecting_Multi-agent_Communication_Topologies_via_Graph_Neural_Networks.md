# G-Designer：利用图神经网络构建多智能体通信网络

发布时间：2024年10月15日

`Agent` `人工智能` `多代理系统`

> G-Designer: Architecting Multi-agent Communication Topologies via Graph Neural Networks

# 摘要

> 最新研究表明，基于 LLM 的代理通过精心设计的通信拓扑，集体智能远超单一代理。然而，面对多样的高性能设计，从业者常困惑于如何为特定任务选择最佳拓扑，以避免不必要的通信开销并确保高质量解决方案。为此，我们推出了 G-Designer，一种适应性强、高效且稳健的多代理部署解决方案，能动态设计任务感知的定制通信拓扑。G-Designer 将多代理系统建模为网络，利用变分图自动编码器编码节点和任务特定虚拟节点，解码出高性能的通信拓扑。实验表明，G-Designer 在 MMLU 和 HumanEval 上表现优异，准确率分别达到 $84.50\%$ 和 $89.90\%$，且能根据任务难度调整通信协议，减少高达 $95.33\%$ 的令牌消耗，并能有效防御对抗性攻击，准确率仅下降 $0.3\%$。

> Recent advancements in large language model (LLM)-based agents have demonstrated that collective intelligence can significantly surpass the capabilities of individual agents, primarily due to well-crafted inter-agent communication topologies. Despite the diverse and high-performing designs available, practitioners often face confusion when selecting the most effective pipeline for their specific task: \textit{Which topology is the best choice for my task, avoiding unnecessary communication token overhead while ensuring high-quality solution?} In response to this dilemma, we introduce G-Designer, an adaptive, efficient, and robust solution for multi-agent deployment, which dynamically designs task-aware, customized communication topologies. Specifically, G-Designer models the multi-agent system as a multi-agent network, leveraging a variational graph auto-encoder to encode both the nodes (agents) and a task-specific virtual node, and decodes a task-adaptive and high-performing communication topology. Extensive experiments on six benchmarks showcase that G-Designer is: \textbf{(1) high-performing}, achieving superior results on MMLU with accuracy at $84.50\%$ and on HumanEval with pass@1 at $89.90\%$; \textbf{(2) task-adaptive}, architecting communication protocols tailored to task difficulty, reducing token consumption by up to $95.33\%$ on HumanEval; and \textbf{(3) adversarially robust}, defending against agent adversarial attacks with merely $0.3\%$ accuracy drop.

[Arxiv](https://arxiv.org/abs/2410.11782)