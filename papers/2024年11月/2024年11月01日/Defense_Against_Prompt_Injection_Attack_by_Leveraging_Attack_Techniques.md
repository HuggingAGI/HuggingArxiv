# 借助攻击技术抵御提示注入攻击

发布时间：2024年11月01日

`LLM应用` `网络安全`

> Defense Against Prompt Injection Attack by Leveraging Attack Techniques

# 摘要

> 随着技术的发展，大型语言模型（LLMs）在各类自然语言处理（NLP）任务中表现出色，为微软 Copilot 等 LLM 集成应用注入了强大动力。然而，LLMs 持续演进的同时，新的漏洞，尤其是提示注入攻击也随之出现。此类攻击诱使 LLMs 偏离原始输入指令，转而执行注入在数据内容（如检索结果）中的攻击者指令。近期的攻击手段借助 LLMs 遵循指令的能力以及无法分辨数据内容中注入指令的弱点，实现了较高的攻击成功率（ASR）。对比攻击和防御方法时，我们饶有兴趣地发现它们有着相似的设计目标，即引导模型忽略无用指令，执行有用指令。于是，我们提出一个直观的问题：这些攻击技术能否用于防御？在本文中，我们逆转提示注入方法的意图，基于先前的无训练攻击方法开发新的防御手段，通过重复攻击流程，但采用原始输入指令而非注入指令。我们的综合实验表明，我们的防御技术优于现有的无训练防御方法，取得了前沿的成果。

> With the advancement of technology, large language models (LLMs) have achieved remarkable performance across various natural language processing (NLP) tasks, powering LLM-integrated applications like Microsoft Copilot. However, as LLMs continue to evolve, new vulnerabilities, especially prompt injection attacks arise. These attacks trick LLMs into deviating from the original input instructions and executing the attacker's instructions injected in data content, such as retrieved results. Recent attack methods leverage LLMs' instruction-following abilities and their inabilities to distinguish instructions injected in the data content, and achieve a high attack success rate (ASR). When comparing the attack and defense methods, we interestingly find that they share similar design goals, of inducing the model to ignore unwanted instructions and instead to execute wanted instructions. Therefore, we raise an intuitive question: Could these attack techniques be utilized for defensive purposes? In this paper, we invert the intention of prompt injection methods to develop novel defense methods based on previous training-free attack methods, by repeating the attack process but with the original input instruction rather than the injected instruction. Our comprehensive experiments demonstrate that our defense techniques outperform existing training-free defense approaches, achieving state-of-the-art results.

[Arxiv](https://arxiv.org/abs/2411.00459)