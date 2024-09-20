# VLMs 能否驾驭动作角色扮演游戏？让我们以《黑神话：悟空》为例，一探究竟。

发布时间：2024年09月19日

`Agent` `视频游戏` `人工智能`

> Can VLMs Play Action Role-Playing Games? Take Black Myth Wukong as a Study Case

# 摘要

> 近期，基于大型语言模型（LLM）的代理在多个领域取得突破，尤其在视频游戏中的应用备受瞩目。传统方法依赖游戏API获取数据，但受限于API的可用性，且无法模拟人类游戏方式。随着视觉语言模型（VLM）的兴起，代理的视觉理解能力大幅提升，能仅凭视觉输入与游戏互动。尽管如此，当前方法在动作导向任务中仍显不足，特别是在动作角色扮演游戏（ARPG）中，强化学习虽普遍但泛化能力差，训练成本高。为此，我们以ARPG“黑神话：悟空”为研究平台，探索VLM在视觉输入与复杂动作输出场景中的极限。我们设定了12个任务，其中75%聚焦战斗，并整合了数种顶尖VLM。此外，我们将发布包含游戏视频与操作日志的人类操作数据集。我们还提出了创新的VARP代理框架，包含动作规划与视觉轨迹系统，展示了在基本任务与90%简单至中等难度战斗中的成功率。本研究旨在为复杂动作游戏环境中的多模态代理应用开辟新思路。相关代码与数据集将在https://varp-agent.github.io/开放获取。

> Recently, large language model (LLM)-based agents have made significant advances across various fields. One of the most popular research areas involves applying these agents to video games. Traditionally, these methods have relied on game APIs to access in-game environmental and action data. However, this approach is limited by the availability of APIs and does not reflect how humans play games. With the advent of vision language models (VLMs), agents now have enhanced visual understanding capabilities, enabling them to interact with games using only visual inputs. Despite these advances, current approaches still face challenges in action-oriented tasks, particularly in action role-playing games (ARPGs), where reinforcement learning methods are prevalent but suffer from poor generalization and require extensive training. To address these limitations, we select an ARPG, ``Black Myth: Wukong'', as a research platform to explore the capability boundaries of existing VLMs in scenarios requiring visual-only input and complex action output. We define 12 tasks within the game, with 75% focusing on combat, and incorporate several state-of-the-art VLMs into this benchmark. Additionally, we will release a human operation dataset containing recorded gameplay videos and operation logs, including mouse and keyboard actions. Moreover, we propose a novel VARP (Vision Action Role-Playing) agent framework, consisting of an action planning system and a visual trajectory system. Our framework demonstrates the ability to perform basic tasks and succeed in 90% of easy and medium-level combat scenarios. This research aims to provide new insights and directions for applying multimodal agents in complex action game environments. The code and datasets will be made available at https://varp-agent.github.io/.

[Arxiv](https://arxiv.org/abs/2409.12889)