# Agent Smith：仅需一张图片，便能迅速让百万计的多模态大型语言模型（LLM）代理陷入崩溃，其速度呈指数级增长。

发布时间：2024年02月13日

`Agent` `人工智能安全` `多智能体系统`

> Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast

# 摘要

> 一款多模态的大型语言模型（MLLM）智能体能够接收指令、捕捉图像、从记忆库中检索历史信息，并自主选择使用何种工具。然而，对抗性图像或提示已被发现能够使MLLM智能体越狱，引发不预期的行为。本研究揭露了在多智能体环境中一个更为严重的安全隐患——传染性越狱。这种攻击方式仅需对单个智能体进行越狱操作，随后无需进一步干预，几乎所有智能体都会迅速被感染，并展现出有害行为。为了证明传染性越狱的可能性，我们构建了包含多达百万个LLaVA-1.5智能体的多智能体环境，并通过随机配对聊天作为多智能体互动的概念验证。研究结果显示，仅需将一张（传染性的）对抗性图像植入任意一个智能体的记忆库中，就足以触发传染性越狱。我们进一步提出了一个简单的原理，用以判断一种防御机制是否能够有效遏制传染性越狱的蔓延，但如何设计出既实用又符合该原理的防御措施，仍是一个亟待解决的问题。项目详情可访问我们的网页 https://sail-sg.github.io/Agent-Smith/。

> A multimodal large language model (MLLM) agent can receive instructions, capture images, retrieve histories from memory, and decide which tools to use. Nonetheless, red-teaming efforts have revealed that adversarial images/prompts can jailbreak an MLLM and cause unaligned behaviors. In this work, we report an even more severe safety issue in multi-agent environments, referred to as infectious jailbreak. It entails the adversary simply jailbreaking a single agent, and without any further intervention from the adversary, (almost) all agents will become infected exponentially fast and exhibit harmful behaviors. To validate the feasibility of infectious jailbreak, we simulate multi-agent environments containing up to one million LLaVA-1.5 agents, and employ randomized pair-wise chat as a proof-of-concept instantiation for multi-agent interaction. Our results show that feeding an (infectious) adversarial image into the memory of any randomly chosen agent is sufficient to achieve infectious jailbreak. Finally, we derive a simple principle for determining whether a defense mechanism can provably restrain the spread of infectious jailbreak, but how to design a practical defense that meets this principle remains an open question to investigate. Our project page is available at https://sail-sg.github.io/Agent-Smith/.

[Arxiv](https://arxiv.org/abs/2402.08567)