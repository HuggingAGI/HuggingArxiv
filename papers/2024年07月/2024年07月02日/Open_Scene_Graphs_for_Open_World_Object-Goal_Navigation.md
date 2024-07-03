# 开放场景图助力开放世界中的对象目标导航

发布时间：2024年07月02日

`Agent` `机器人` `人工智能`

> Open Scene Graphs for Open World Object-Goal Navigation

# 摘要

> 我们如何打造能在开放世界中进行语义导航的机器人，比如在新环境中寻找特定物品？基础模型虽具备丰富的知识和泛化能力，但还需一个恰当的场景表示来构建完整的机器人系统。我们采用 Open Scene Graphs (OSGs)，这是一种结合拓扑与语义的表示方法，能有效组织并保留开放场景信息，并可根据不同环境灵活调整。我们将基础模型与 OSGs 融合进 OpenSearch 系统，使其能在自然语言指引下，搜索任意指定物品，并在多变的环境和实体中实现零-shot 泛化。OSGs 与大型语言模型的结合，提升了对象目标导航的鲁棒性，超越了现有 LLM 方法。通过模拟与实境测试，我们证实了 OpenSearch 在多样环境、机器人及新指令中的广泛适用性。

> How can we build robots for open-world semantic navigation tasks, like searching for target objects in novel scenes? While foundation models have the rich knowledge and generalisation needed for these tasks, a suitable scene representation is needed to connect them into a complete robot system. We address this with Open Scene Graphs (OSGs), a topo-semantic representation that retains and organises open-set scene information for these models, and has a structure that can be configured for different environment types. We integrate foundation models and OSGs into the OpenSearch system for Open World Object-Goal Navigation, which is capable of searching for open-set objects specified in natural language, while generalising zero-shot across diverse environments and embodiments. Our OSGs enhance reasoning with Large Language Models (LLM), enabling robust object-goal navigation outperforming existing LLM approaches. Through simulation and real-world experiments, we validate OpenSearch's generalisation across varied environments, robots and novel instructions.

[Arxiv](https://arxiv.org/abs/2407.02473)