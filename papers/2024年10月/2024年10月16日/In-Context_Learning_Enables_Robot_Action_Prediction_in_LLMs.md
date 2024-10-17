# 上下文学习让 LLM 能够预测机器人动作

发布时间：2024年10月16日

`LLM应用` `机器人` `人工智能`

> In-Context Learning Enables Robot Action Prediction in LLMs

# 摘要

> 近期，大型语言模型（LLM）在语言领域通过 in-context learning（ICL）取得了显著成就。然而，如何利用 LLM 的 ICL 能力直接预测机器人动作，仍是一个未被充分探索的领域。本文中，我们提出了 RoboPrompt 框架，使现成的纯文本 LLM 无需训练即可通过 ICL 直接预测机器人动作。首先，我们启发式地识别出剧集中的关键帧，捕捉重要时刻。接着，提取关键帧中的末端执行器动作及初始对象姿态，并将其转换为文本描述。最后，构建结构化模板，结合文本描述与任务指令形成 ICL 演示，使 LLM 在测试时能直接预测机器人动作。实验证明，RoboPrompt 在模拟与现实环境中均优于零-shot 和 ICL 基线。

> Recently, Large Language Models (LLMs) have achieved remarkable success using in-context learning (ICL) in the language domain. However, leveraging the ICL capabilities within LLMs to directly predict robot actions remains largely unexplored. In this paper, we introduce RoboPrompt, a framework that enables off-the-shelf text-only LLMs to directly predict robot actions through ICL without training. Our approach first heuristically identifies keyframes that capture important moments from an episode. Next, we extract end-effector actions from these keyframes as well as the estimated initial object poses, and both are converted into textual descriptions. Finally, we construct a structured template to form ICL demonstrations from these textual descriptions and a task instruction. This enables an LLM to directly predict robot actions at test time. Through extensive experiments and analysis, RoboPrompt shows stronger performance over zero-shot and ICL baselines in simulated and real-world settings.

[Arxiv](https://arxiv.org/abs/2410.12782)