# [为实现结合移动操作的交互式物体搜索，我们提出了一种基于语言引导的动态场景图方法。该方法利用语言信息构建动态场景图，以高效指导机器人在复杂环境中进行目标物体搜索和交互。](https://arxiv.org/abs/2403.08605)

发布时间：2024年03月13日

`Agent` `机器人` `移动操作` `环境规划`

> Language-Grounded Dynamic Scene Graphs for Interactive Object Search with Mobile Manipulation

> 为了让移动操作机器人充分发挥潜力，必须使其能独立在未知的广阔环境中执行长远规划任务。尽管LLMs展现出了在各类任务上的出色推理能力，但现有研究大多聚焦于已知环境，并侧重单一的导航或操作任务。本研究引入了一项名为MoMa-LLM的新颖方案，它将语言模型嵌入到由开放式词汇场景图构建并随环境探索实时更新的结构化表达之中，并紧密结合了一个面向对象的动作空间。这一零样本、开放式词汇且易于拓展的方法适用于多种移动操作和家庭机器人任务。我们在大规模真实室内环境中设计了一项创新的语义互动搜索任务，验证了MoMa-LLM的有效性。通过深入的模拟和实际试验，我们表明MoMa-LLM相较于传统基线和最先进技术大大提升了搜索效率，同时适用于更高层次的抽象任务。相关代码已开放获取，网址为http://moma-llm.cs.uni-freiburg.de。

> To fully leverage the capabilities of mobile manipulation robots, it is imperative that they are able to autonomously execute long-horizon tasks in large unexplored environments. While large language models (LLMs) have shown emergent reasoning skills on arbitrary tasks, existing work primarily concentrates on explored environments, typically focusing on either navigation or manipulation tasks in isolation. In this work, we propose MoMa-LLM, a novel approach that grounds language models within structured representations derived from open-vocabulary scene graphs, dynamically updated as the environment is explored. We tightly interleave these representations with an object-centric action space. The resulting approach is zero-shot, open-vocabulary, and readily extendable to a spectrum of mobile manipulation and household robotic tasks. We demonstrate the effectiveness of MoMa-LLM in a novel semantic interactive search task in large realistic indoor environments. In extensive experiments in both simulation and the real world, we show substantially improved search efficiency compared to conventional baselines and state-of-the-art approaches, as well as its applicability to more abstract tasks. We make the code publicly available at http://moma-llm.cs.uni-freiburg.de.

[Arxiv](https://arxiv.org/abs/2403.08605)