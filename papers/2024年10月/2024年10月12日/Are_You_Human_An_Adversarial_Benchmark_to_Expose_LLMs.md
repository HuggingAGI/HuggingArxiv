# “你是人类吗？”——一个对抗性基准，旨在揭示大型语言模型的真实面目。

发布时间：2024年10月12日

`LLM应用` `网络安全` `人工智能`

> Are You Human? An Adversarial Benchmark to Expose LLMs

# 摘要

> 大型语言模型 (LLM) 的模仿能力令人担忧，可能被用于诈骗和欺骗。人类有权知晓对话对象是否为 LLM。我们设计了文本提示，旨在实时揭露 LLM 的冒充行为。为此，我们发布了一个开源基准数据集，包含利用 LLM 指令机制的“隐性挑战”和测试 LLM 简单任务能力的“显性挑战”。评估显示，显性挑战在 78.4% 的情况下成功识别 LLM，而隐性挑战在 22.9% 的实例中有效。用户研究证实了方法的实用性，人类在显性挑战中表现更佳（78% 对 22% 的成功率）。我们的框架意外发现许多参与者使用 LLM 完成任务，有效检测了 AI 冒充和人类滥用 AI 工具。这项研究解决了高风险对话中实时、可靠检测 LLM 的迫切需求。

> Large Language Models (LLMs) have demonstrated an alarming ability to impersonate humans in conversation, raising concerns about their potential misuse in scams and deception. Humans have a right to know if they are conversing to an LLM. We evaluate text-based prompts designed as challenges to expose LLM imposters in real-time. To this end we compile and release an open-source benchmark dataset that includes 'implicit challenges' that exploit an LLM's instruction-following mechanism to cause role deviation, and 'exlicit challenges' that test an LLM's ability to perform simple tasks typically easy for humans but difficult for LLMs. Our evaluation of 9 leading models from the LMSYS leaderboard revealed that explicit challenges successfully detected LLMs in 78.4% of cases, while implicit challenges were effective in 22.9% of instances. User studies validate the real-world applicability of our methods, with humans outperforming LLMs on explicit challenges (78% vs 22% success rate). Our framework unexpectedly revealed that many study participants were using LLMs to complete tasks, demonstrating its effectiveness in detecting both AI impostors and human misuse of AI tools. This work addresses the critical need for reliable, real-time LLM detection methods in high-stakes conversations.

[Arxiv](https://arxiv.org/abs/2410.09569)