# 拼图解谜：拆解有害问题，破解大型语言模型

发布时间：2024年10月15日

`LLM应用` `网络安全` `人工智能`

> Jigsaw Puzzles: Splitting Harmful Questions to Jailbreak Large Language Models

# 摘要

> 大型语言模型（LLM）凭借其丰富的隐性知识和强大的推理能力，在与人类互动和解决复杂问题方面表现卓越。然而，这些模型易受 jailbreak 攻击，导致生成有害内容。尽管已有研究针对单轮攻击策略以加强防御，但在多轮交互中揭示漏洞的研究仍显不足。为此，我们提出了 Jigsaw Puzzles（JSP），一种简单有效的多轮 jailbreak 策略。JSP 将问题拆分为无害片段，逐轮输入并要求 LLM 重建并回答。实验显示，JSP 成功绕过原始防护，对 5 个先进 LLM 的 189 个有害查询实现了 93.76% 的平均攻击成功率。在 GPT-4 上，JSP 更达到了 92% 的攻击成功率，且对防御策略表现出强抵抗力。请注意：本文包含冒犯性示例。

> Large language models (LLMs) have exhibited outstanding performance in engaging with humans and addressing complex questions by leveraging their vast implicit knowledge and robust reasoning capabilities. However, such models are vulnerable to jailbreak attacks, leading to the generation of harmful responses. Despite recent research on single-turn jailbreak strategies to facilitate the development of defence mechanisms, the challenge of revealing vulnerabilities under multi-turn setting remains relatively under-explored. In this work, we propose Jigsaw Puzzles (JSP), a straightforward yet effective multi-turn jailbreak strategy against the advanced LLMs. JSP splits questions into harmless fractions as the input of each turn, and requests LLMs to reconstruct and respond to questions under multi-turn interaction. Our experimental results demonstrate that the proposed JSP jailbreak bypasses original safeguards against explicitly harmful content, achieving an average attack success rate of 93.76% on 189 harmful queries across 5 advanced LLMs (Gemini-1.5-Pro, Llama-3.1-70B, GPT-4, GPT-4o, GPT-4o-mini). Moreover, JSP achieves a state-of-the-art attack success rate of 92% on GPT-4 on the harmful query benchmark, and exhibits strong resistant to defence strategies. Warning: this paper contains offensive examples.

[Arxiv](https://arxiv.org/abs/2410.11459)