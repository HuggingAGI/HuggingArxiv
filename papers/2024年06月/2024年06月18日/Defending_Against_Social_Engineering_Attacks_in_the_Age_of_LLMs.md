# 在大型语言模型盛行的当下，如何有效防御社会工程攻击？

发布时间：2024年06月18日

`Agent

理由：这篇论文主要探讨了大型语言模型（LLMs）在数字欺骗检测和防范中的应用，特别是在社交工程（CSE）攻击中的角色。论文中提到的ConvoSentinel系统是一种防御机制，它利用LLMs的能力来提升检测精度，并增强对恶意意图的识别。这表明论文关注的是如何利用LLMs作为智能代理来增强网络安全，因此属于Agent分类。虽然论文中也涉及了LLMs的应用，但其核心在于开发和利用一个系统（ConvoSentinel）来作为防御机制，这与LLM应用分类中的直接应用LLMs解决问题有所不同，更强调的是系统作为智能代理的功能。` `网络安全` `社交工程`

> Defending Against Social Engineering Attacks in the Age of LLMs

# 摘要

> 随着大型语言模型（LLMs）的普及，检测和防范数字欺骗变得更加复杂，因为这些模型能够模仿人类对话并助长基于聊天的社交工程（CSE）攻击。本研究深入探讨了LLMs在CSE攻击中的双重角色：既是攻击的推动者，也是防御的盾牌。我们创建了一个名为SEConvo的新数据集，模拟了学术和招聘领域的CSE场景，以探究LLMs在这些情境中的潜在风险。研究发现，尽管LLMs能生成逼真的CSE内容，但其自身的检测能力却不足，增加了防御成本。为此，我们设计了ConvoSentinel，一种模块化的防御系统，它通过在消息和对话层面提升检测精度，实现了更高的适应性和成本效益。ConvoSentinel中的检索增强模块通过比对数据库中的类似对话，有效识别恶意意图，全面提升了CSE检测的效率。本研究表明，在网络安全领域，我们需要更先进的策略来充分利用LLMs的潜力。

> The proliferation of Large Language Models (LLMs) poses challenges in detecting and mitigating digital deception, as these models can emulate human conversational patterns and facilitate chat-based social engineering (CSE) attacks. This study investigates the dual capabilities of LLMs as both facilitators and defenders against CSE threats. We develop a novel dataset, SEConvo, simulating CSE scenarios in academic and recruitment contexts, and designed to examine how LLMs can be exploited in these situations. Our findings reveal that, while off-the-shelf LLMs generate high-quality CSE content, their detection capabilities are suboptimal, leading to increased operational costs for defense. In response, we propose ConvoSentinel, a modular defense pipeline that improves detection at both the message and the conversation levels, offering enhanced adaptability and cost-effectiveness. The retrieval-augmented module in ConvoSentinel identifies malicious intent by comparing messages to a database of similar conversations, enhancing CSE detection at all stages. Our study highlights the need for advanced strategies to leverage LLMs in cybersecurity.

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/data_generation.png)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/ambiguity_std_max_pie.jpg)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/max_ambiguity_charts.jpg)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/ambiguity_attack_success.jpg)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/deceived_scenario.jpg)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/framework.jpg)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/early_stage_results.png)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/single_llm_length_distribution.jpg)

![在大型语言模型盛行的当下，如何有效防御社会工程攻击？](../../../paper_images/2406.12263/si_distribution.jpg)

[Arxiv](https://arxiv.org/abs/2406.12263)