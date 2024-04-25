# 一款人机协作工具，通过少量示例，将单一的大型语言模型代理培养成为网络的一部分。

发布时间：2024年04月24日

`Agent` `人工智能` `软件开发`

> A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples

# 摘要

> 单个大型语言模型（LLM）在应对复杂任务时，其能力有所局限。通过构建大型语言模型代理网络（LAN），将多个LLM代理互联，可以有效提升整体性能。但搭建LAN是一项耗时耗力的工作。本文提出了EasyLAN，这是一个辅助开发者构建LAN的人机协作工具。EasyLAN首先根据任务描述创建一个只包含单个代理的初始网络。然后，通过少量训练样本，EasyLAN更新网络，模拟输出与基准真相之间的差异，并诊断错误成因。通过策略性的设计，这些错误得到针对性的解决。用户可以选择介入EasyLAN的工作流程，或直接对LAN进行调整。随着迭代优化，LAN逐步从一个单一代理发展成为一个由多个LLM代理构成的网络。实验结果显示，开发者能够迅速搭建出性能优异的LAN。

> The capabilities of a single large language model (LLM) agent for solving a complex task are limited. Connecting multiple LLM agents to a network can effectively improve overall performance. However, building an LLM agent network (LAN) requires a substantial amount of time and effort. In this paper, we introduce EasyLAN, a human-computer collaborative tool that helps developers construct LANs. EasyLAN initially generates a LAN containing only one agent based on the description of the desired task. Subsequently, EasyLAN leverages a few training examples to update the LAN. For each example, EasyLAN models the gap between the output and the ground truth and identifies the causes of the errors. These errors are addressed through carefully designed strategies. Users can intervene in EasyLAN's workflow or directly modify the LAN. Eventually, the LAN evolves from a single agent to a network of LLM agents. The experimental results indicate that developers can rapidly construct LANs with good performance.

[Arxiv](https://arxiv.org/abs/2404.15974)