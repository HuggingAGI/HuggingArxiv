# 一种人机协作工具，通过少量示例将单一的大型语言模型训练成为网络的一部分。

发布时间：2024年04月24日

`Agent` `人工智能`

> A Human-Computer Collaborative Tool for Training a Single Large Language Model Agent into a Network through Few Examples

# 摘要

> 单个大型语言模型（LLM）在处理复杂任务时力有未逮。通过构建大型语言模型代理网络（LAN），将多个LLM代理互联，可以有效提升整体效能。但搭建LAN是一项耗时耗力的工作。本文提出了EasyLAN，这是一个辅助开发者构建LAN的人机协作工具。EasyLAN根据用户对任务的描述，首先创建一个只包含单个代理的初始网络。然后，通过少量训练样本，EasyLAN对网络进行迭代优化，分析输出与标准答案之间的差异，找出并纠正错误。用户可以参与EasyLAN的工作流程，或直接对LAN进行编辑。通过这种方式，LAN逐步从一个单一代理发展成为一个由多个LLM代理组成的网络。实验数据显示，使用EasyLAN，开发者能够迅速搭建出性能优异的LAN。

> The capabilities of a single large language model (LLM) agent for solving a complex task are limited. Connecting multiple LLM agents to a network can effectively improve overall performance. However, building an LLM agent network (LAN) requires a substantial amount of time and effort. In this paper, we introduce EasyLAN, a human-computer collaborative tool that helps developers construct LANs. EasyLAN initially generates a LAN containing only one agent based on the description of the desired task. Subsequently, EasyLAN leverages a few training examples to update the LAN. For each example, EasyLAN models the gap between the output and the ground truth and identifies the causes of the errors. These errors are addressed through carefully designed strategies. Users can intervene in EasyLAN's workflow or directly modify the LAN. Eventually, the LAN evolves from a single agent to a network of LLM agents. The experimental results indicate that developers can rapidly construct LANs with good performance.

[Arxiv](https://arxiv.org/abs/2404.15974)