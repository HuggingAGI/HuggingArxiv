# 指令驱动游戏引擎：扑克实战解析

发布时间：2024年10月17日

`LLM应用` `游戏开发` `人工智能`

> Instruction-Driven Game Engine: A Poker Case Study

# 摘要

> IDGE 项目旨在通过 LLM 遵循自由形式的游戏描述并生成游戏过程，实现游戏开发的民主化。用户只需通过自然语言指令即可创建游戏，大大降低了开发门槛。我们将 IDGE 的学习过程视为下一状态预测任务，模型根据玩家动作自回归地预测游戏状态。游戏状态的计算必须精确，以避免轻微错误破坏游戏体验。为解决稳定性和多样性之间的挑战，我们采用课程训练方式，逐步增加复杂场景的接触。初步成果是开发了支持多种扑克变体并允许个性化新游戏的扑克 IDGE。这项工作为未来游戏创建和玩法的变革奠定了基础。

> The Instruction-Driven Game Engine (IDGE) project aims to democratize game development by enabling a large language model (LLM) to follow free-form game descriptions and generate game-play processes. The IDGE allows users to create games simply by natural language instructions, which significantly lowers the barrier for game development. We approach the learning process for IDGEs as a Next State Prediction task, wherein the model autoregressively predicts the game states given player actions. The computation of game states must be precise; otherwise, slight errors could corrupt the game-play experience. This is challenging because of the gap between stability and diversity. To address this, we train the IDGE in a curriculum manner that progressively increases its exposure to complex scenarios. Our initial progress lies in developing an IDGE for Poker, which not only supports a wide range of poker variants but also allows for highly individualized new poker games through natural language inputs. This work lays the groundwork for future advancements in transforming how games are created and played.

[Arxiv](https://arxiv.org/abs/2410.13441)