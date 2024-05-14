# 记忆迷宫：专为盲人设计的情景驱动基准与视觉语言导航模型，旨在通过模拟真实环境挑战，提升导航辅助技术的精准性与实用性。

发布时间：2024年05月11日

`Agent

这篇论文主要讨论了视觉语言导航（VLN）机器人在辅助盲人导航方面的应用，特别是在处理源自人类记忆的导航指令时的挑战。论文提出了一个新的基准Memory-Maze，并开发了一种新的VLN模型，该模型利用大型语言模型（LLM）来解析指令并生成机器人控制的Python代码。这个模型旨在提高机器人在现实世界中导航的能力，特别是在处理复杂和非标准化的指令时。因此，这篇论文更符合Agent分类，因为它关注的是一个具体的智能代理（Agent）在特定任务（盲人导航）中的应用和改进。` `盲人辅助` `机器人导航`

> Memory-Maze: Scenario Driven Benchmark and Visual Language Navigation Model for Guiding Blind People

# 摘要

> 视觉语言导航（VLN）机器人能够通过执行旁观者提供的路线指令来辅助盲人导航，即便环境未知。然而，现有模型在处理盲人导航指令时显得力不从心，因为这些指令源自人类记忆，常伴有停顿、错误和细节遗漏。为此，我们推出了Memory-Maze基准，模拟盲人导航场景，并提供来自人类记忆的路线指令。通过现场和在线的旁观者研究，我们收集了自然语言指令，发现现场指令更为详尽且措辞多样。我们还提出了一种新的VLN模型，利用LLM解析指令并生成机器人控制的Python代码，显著优于现有最先进模型。我们强调，在将VLN技术应用于实际场景时，必须考虑到现实世界与传统研究环境之间的差异。

> Visual Language Navigation (VLN) powered navigation robots have the potential to guide blind people by understanding and executing route instructions provided by sighted passersby. This capability allows robots to operate in environments that are often unknown a priori. Existing VLN models are insufficient for the scenario of navigation guidance for blind people, as they need to understand routes described from human memory, which frequently contain stutters, errors, and omission of details as opposed to those obtained by thinking out loud, such as in the Room-to-Room dataset. However, currently, there is no benchmark that simulates instructions that were obtained from human memory in environments where blind people navigate. To this end, we present our benchmark, Memory-Maze, which simulates the scenario of seeking route instructions for guiding blind people. Our benchmark contains a maze-like structured virtual environment and novel route instruction data from human memory. To collect natural language instructions, we conducted two studies from sighted passersby onsite and annotators online. Our analysis demonstrates that instructions data collected onsite were more lengthy and contained more varied wording. Alongside our benchmark, we propose a VLN model better equipped to handle the scenario. Our proposed VLN model uses Large Language Models (LLM) to parse instructions and generate Python codes for robot control. We further show that the existing state-of-the-art model performed suboptimally on our benchmark. In contrast, our proposed method outperformed the state-of-the-art model by a fair margin. We found that future research should exercise caution when considering VLN technology for practical applications, as real-world scenarios have different characteristics than ones collected in traditional settings.

[Arxiv](https://arxiv.org/abs/2405.07060)