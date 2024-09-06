# 哇，这升级得真快：单轮渐强攻击 (STCA)

发布时间：2024年09月04日

`LLM应用` `人工智能安全` `网络安全`

> Well, that escalated quickly: The Single-Turn Crescendo Attack (STCA)

# 摘要

> 本文介绍了一种新颖的对抗攻击方法——单轮渐强攻击 (STCA)，专门针对大型语言模型 (LLM)。传统的多轮对抗策略通过逐步升级上下文来引出有害或争议性回应，而 STCA 则将这一过程浓缩为单次交互，通过精心设计的提示模拟扩展对话，巧妙绕过内容审核系统，生成通常会被过滤的回应。通过案例研究，我们展示了这一技术的实际应用，揭示了当前 LLM 的脆弱性，并呼吁加强安全措施。这项研究不仅为负责任的人工智能 (RAI) 安全和对抗测试提供了新视角，还为研究人员和开发者提供了实用示例。STCA 在文献中尚属首次，为该领域带来了创新贡献。

> This paper explores a novel approach to adversarial attacks on large language models (LLM): the Single-Turn Crescendo Attack (STCA). The STCA builds upon the multi-turn crescendo attack established by Mark Russinovich, Ahmed Salem, Ronen Eldan. Traditional multi-turn adversarial strategies gradually escalate the context to elicit harmful or controversial responses from LLMs. However, this paper introduces a more efficient method where the escalation is condensed into a single interaction. By carefully crafting the prompt to simulate an extended dialogue, the attack bypasses typical content moderation systems, leading to the generation of responses that would normally be filtered out. I demonstrate this technique through a few case studies. The results highlight vulnerabilities in current LLMs and underscore the need for more robust safeguards. This work contributes to the broader discourse on responsible AI (RAI) safety and adversarial testing, providing insights and practical examples for researchers and developers. This method is unexplored in the literature, making it a novel contribution to the field.

[Arxiv](https://arxiv.org/abs/2409.03131)