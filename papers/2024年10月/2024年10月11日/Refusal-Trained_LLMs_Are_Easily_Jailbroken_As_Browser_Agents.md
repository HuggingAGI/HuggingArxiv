# 经过拒绝训练的 LLM 在作为浏览器代理时，容易被破解。

发布时间：2024年10月11日

`Agent` `网络安全` `人工智能`

> Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents

# 摘要

> 出于安全考虑，大型语言模型 (LLM) 被训练为拒绝有害指令，如协助危险活动。我们探讨了一个关键问题：聊天环境中强制的安全拒绝，能否在非聊天和代理场景中同样有效？与聊天机器人不同，配备通用工具的 LLM 代理能直接影响现实世界，因此拒绝有害指令尤为重要。我们重点研究了通过浏览器操纵信息的 LLM 代理。为此，我们推出了浏览器代理红队测试工具包 (BrowserART)，这是一个专为测试浏览器代理设计的综合套件，包含 100 种与浏览器相关的有害行为。实证研究表明，尽管作为聊天机器人的 LLM 拒绝有害指令，但代理并未拒绝。此外，针对聊天设置中拒绝训练的 LLM 的攻击方法，同样适用于浏览器代理。通过人类重写，基于 GPT-4o 和 o1-preview 的浏览器代理分别尝试了 98 和 63 种有害行为。我们公开了 BrowserART，并呼吁各方合作，提升代理安全性。

> For safety reasons, large language models (LLMs) are trained to refuse harmful user instructions, such as assisting dangerous activities. We study an open question in this work: does the desired safety refusal, typically enforced in chat contexts, generalize to non-chat and agentic use cases? Unlike chatbots, LLM agents equipped with general-purpose tools, such as web browsers and mobile devices, can directly influence the real world, making it even more crucial to refuse harmful instructions. In this work, we primarily focus on red-teaming browser agents, LLMs that manipulate information via web browsers. To this end, we introduce Browser Agent Red teaming Toolkit (BrowserART), a comprehensive test suite designed specifically for red-teaming browser agents. BrowserART is consist of 100 diverse browser-related harmful behaviors (including original behaviors and ones sourced from HarmBench [Mazeika et al., 2024] and AirBench 2024 [Zeng et al., 2024b]) across both synthetic and real websites. Our empirical study on state-of-the-art browser agents reveals that, while the backbone LLM refuses harmful instructions as a chatbot, the corresponding agent does not. Moreover, attack methods designed to jailbreak refusal-trained LLMs in the chat settings transfer effectively to browser agents. With human rewrites, GPT-4o and o1-preview-based browser agents attempted 98 and 63 harmful behaviors (out of 100), respectively. We publicly release BrowserART and call on LLM developers, policymakers, and agent developers to collaborate on improving agent safety

[Arxiv](https://arxiv.org/abs/2410.13886)