# Agent Security Bench (ASB): 为基于 LLM 的代理中的攻击与防御提供形式化定义和基准测试

发布时间：2024年10月03日

`Agent` `网络安全` `人工智能`

> Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents

# 摘要

> 尽管基于 LLM 的代理能够通过外部工具和记忆机制解决复杂任务，但也可能带来严重安全风险。现有文献对这些代理的攻防评估并不全面。为此，我们推出了 Agent Security Bench (ASB)，一个综合框架，涵盖 10 个场景、10 个代理、400 多种工具、23 种攻防方法和 8 个评估指标。基于 ASB，我们测试了 10 种提示注入攻击、一种记忆中毒攻击、一种新颖的 Plan-of-Thought 后门攻击、一种混合攻击及 10 种防御措施，涉及 13 个 LLM 骨干网络，总计近 90,000 个测试案例。结果显示，代理在系统提示、用户提示处理、工具使用和记忆检索等阶段存在关键漏洞，最高平均攻击成功率达 84.30%，而当前防御措施效果有限，凸显了代理安全领域的重要研究方向。代码详见 https://github.com/agiresearch/ASB。

> Although LLM-based agents, powered by Large Language Models (LLMs), can use external tools and memory mechanisms to solve complex real-world tasks, they may also introduce critical security vulnerabilities. However, the existing literature does not comprehensively evaluate attacks and defenses against LLM-based agents. To address this, we introduce Agent Security Bench (ASB), a comprehensive framework designed to formalize, benchmark, and evaluate the attacks and defenses of LLM-based agents, including 10 scenarios (e.g., e-commerce, autonomous driving, finance), 10 agents targeting the scenarios, over 400 tools, 23 different types of attack/defense methods, and 8 evaluation metrics. Based on ASB, we benchmark 10 prompt injection attacks, a memory poisoning attack, a novel Plan-of-Thought backdoor attack, a mixed attack, and 10 corresponding defenses across 13 LLM backbones with nearly 90,000 testing cases in total. Our benchmark results reveal critical vulnerabilities in different stages of agent operation, including system prompt, user prompt handling, tool usage, and memory retrieval, with the highest average attack success rate of 84.30\%, but limited effectiveness shown in current defenses, unveiling important works to be done in terms of agent security for the community. Our code can be found at https://github.com/agiresearch/ASB.

[Arxiv](https://arxiv.org/abs/2410.02644)