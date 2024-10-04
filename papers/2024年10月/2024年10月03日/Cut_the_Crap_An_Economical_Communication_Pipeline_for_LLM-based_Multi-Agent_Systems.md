# 精简废话：为基于LLM的多代理系统打造经济高效的通信通道

发布时间：2024年10月03日

`Agent` `人工智能` `多智能体系统`

> Cut the Crap: An Economical Communication Pipeline for LLM-based Multi-Agent Systems

# 摘要

> 最近，基于 LLM 的智能体展示了集体智能如何显著超越个体能力，这得益于精心设计的智能体间通信结构。然而，现有多智能体系统不仅令牌开销大，经济成本也高，限制了其大规模应用。为此，我们推出了 $\texttt{AgentPrune}$，一个经济、简单且强大的多智能体通信框架，能无缝集成现有系统并修剪冗余或恶意通信。$\texttt{AgentPrune}$ 首次识别并定义了当前 LLM 多智能体系统中的 \textit{通信冗余} 问题，通过一次性修剪空间-时间消息传递图，实现了令牌经济且高效的通信结构。实验表明，$\texttt{AgentPrune}$ 不仅以 $\$5.6$ 的成本达到最先进水平，还减少了 $28.1\%\sim72.8\%$ 的令牌，并提升了 $3.5\%\sim10.8\%$ 的抗攻击性能。

> Recent advancements in large language model (LLM)-powered agents have shown that collective intelligence can significantly outperform individual capabilities, largely attributed to the meticulously designed inter-agent communication topologies. Though impressive in performance, existing multi-agent pipelines inherently introduce substantial token overhead, as well as increased economic costs, which pose challenges for their large-scale deployments. In response to this challenge, we propose an economical, simple, and robust multi-agent communication framework, termed $\texttt{AgentPrune}$, which can seamlessly integrate into mainstream multi-agent systems and prunes redundant or even malicious communication messages. Technically, $\texttt{AgentPrune}$ is the first to identify and formally define the \textit{communication redundancy} issue present in current LLM-based multi-agent pipelines, and efficiently performs one-shot pruning on the spatial-temporal message-passing graph, yielding a token-economic and high-performing communication topology. Extensive experiments across six benchmarks demonstrate that $\texttt{AgentPrune}$ \textbf{(I)} achieves comparable results as state-of-the-art topologies at merely $\$5.6$ cost compared to their $\$43.7$, \textbf{(II)} integrates seamlessly into existing multi-agent frameworks with $28.1\%\sim72.8\%\downarrow$ token reduction, and \textbf{(III)} successfully defend against two types of agent-based adversarial attacks with $3.5\%\sim10.8\%\uparrow$ performance boost.

[Arxiv](https://arxiv.org/abs/2410.02506)