# 俄狄浦斯：大型语言模型加持的推理验证码破解者

发布时间：2024年05月13日

`Agent

理由：这篇论文介绍了一个名为Oedipus的框架，它是一个专门设计来解决推理CAPTCHAs的系统。这个框架通过将复杂任务分解为简单步骤，并利用LLMs的能力来生成子步骤和解决这些子任务，展现了一个Agent的行为特征。Agent通常指的是能够执行特定任务或解决特定问题的智能系统，而Oedipus框架正是这样的一个系统，它通过特定的方法和策略来解决CAPTCHAs这一特定问题。因此，这篇论文更符合Agent的分类，而不是RAG（检索增强生成）、LLM应用或LLM理论。RAG通常指的是一种结合检索和生成的模型，而这里并没有提到这种结合；LLM应用通常指的是将LLM用于特定应用场景，而这里Oedipus框架本身就是一个应用；LLM理论则更多关注LLM的理论基础和内部机制，而这里主要讨论的是一个解决CAPTCHAs的框架。` `网络安全` `人工智能`

> Oedipus: LLM-enchanced Reasoning CAPTCHA Solver

# 摘要

> CAPTCHAs作为抵御自动化机器人的盾牌，其设计日益精妙。最新的推理CAPTCHAs利用人类易解而AI难解的任务，强化了安全防线。随着大型语言模型（LLMs）的进步，我们探索了多模态LLMs在破解这些现代谜题上的潜力。尽管LLMs推理能力卓越，但在解决推理CAPTCHAs时仍显吃力。为此，我们推出了Oedipus框架，它通过将复杂任务分解为AI易解的简单步骤，巧妙地解决了这一难题。我们定制的CAPTCHAs领域特定语言（DSL）引导LLMs生成可行的子步骤，而思维链（CoT）方法则按序攻克这些子任务。Oedipus在解决CAPTCHAs上的成功率高达63.5%，并能适应2023年末的新设计，这促使我们思考如何设计未来的推理CAPTCHAs，以抵御AI的挑战。

> CAPTCHAs have become a ubiquitous tool in safeguarding applications from automated bots. Over time, the arms race between CAPTCHA development and evasion techniques has led to increasingly sophisticated and diverse designs. The latest iteration, reasoning CAPTCHAs, exploits tasks that are intuitively simple for humans but challenging for conventional AI technologies, thereby enhancing security measures.
  Driven by the evolving AI capabilities, particularly the advancements in Large Language Models (LLMs), we investigate the potential of multimodal LLMs to solve modern reasoning CAPTCHAs. Our empirical analysis reveals that, despite their advanced reasoning capabilities, LLMs struggle to solve these CAPTCHAs effectively. In response, we introduce Oedipus, an innovative end-to-end framework for automated reasoning CAPTCHA solving. Central to this framework is a novel strategy that dissects the complex and human-easy-AI-hard tasks into a sequence of simpler and AI-easy steps. This is achieved through the development of a Domain Specific Language (DSL) for CAPTCHAs that guides LLMs in generating actionable sub-steps for each CAPTCHA challenge. The DSL is customized to ensure that each unit operation is a highly solvable subtask revealed in our previous empirical study. These sub-steps are then tackled sequentially using the Chain-of-Thought (CoT) methodology.
  Our evaluation shows that Oedipus effectively resolves the studied CAPTCHAs, achieving an average success rate of 63.5\%. Remarkably, it also shows adaptability to the most recent CAPTCHA designs introduced in late 2023, which are not included in our initial study. This prompts a discussion on future strategies for designing reasoning CAPTCHAs that can effectively counter advanced AI solutions.

[Arxiv](https://arxiv.org/abs/2405.07496)