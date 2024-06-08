# 针对集成LLM的应用程序的提示注入攻击：探索安全漏洞与防御策略

发布时间：2024年03月02日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在实际应用中的安全问题，特别是针对提示注入攻击的分析和后果。研究通过开发一种新的黑盒提示注入攻击方法（HouYI），并在多个商业应用上进行了测试，揭示了这些应用在面对此类攻击时的脆弱性。因此，这篇论文的内容更偏向于LLM在实际应用中的安全问题，属于LLM应用分类。` `人工智能`

> Prompt Injection attack against LLM-integrated Applications

# 摘要

> 大型语言模型（LLMs）因其卓越的语言处理能力而激发了丰富的应用生态，但广泛融入服务也带来了显著的安全隐患。本研究深入分析了针对实际LLM集成应用的提示注入攻击的复杂性和后果。首先，我们对十个商业应用进行了初步分析，指出了现有攻击策略的局限性。基于这些发现，我们开发了HouYi，一种创新的黑盒提示注入攻击方法，灵感源自传统网络注入技术。HouYi包含三个核心组件：无缝嵌入的预设提示、诱导上下文隔离的注入提示和实现攻击目的的恶意内容。通过HouYi，我们发现了新的严重攻击后果，如无限制的LLM滥用和简单的提示窃取。我们在36个集成LLM的应用上测试了HouYi，发现31个易受攻击。包括Notion在内的10家供应商已确认我们的发现，这可能影响数百万用户。我们的研究不仅揭示了提示注入攻击的风险，也提出了可能的防御策略。

> Large Language Models (LLMs), renowned for their superior proficiency in language comprehension and generation, stimulate a vibrant ecosystem of applications around them. However, their extensive assimilation into various services introduces significant security risks. This study deconstructs the complexities and implications of prompt injection attacks on actual LLM-integrated applications. Initially, we conduct an exploratory analysis on ten commercial applications, highlighting the constraints of current attack strategies in practice. Prompted by these limitations, we subsequently formulate HouYi, a novel black-box prompt injection attack technique, which draws inspiration from traditional web injection attacks. HouYi is compartmentalized into three crucial elements: a seamlessly-incorporated pre-constructed prompt, an injection prompt inducing context partition, and a malicious payload designed to fulfill the attack objectives. Leveraging HouYi, we unveil previously unknown and severe attack outcomes, such as unrestricted arbitrary LLM usage and uncomplicated application prompt theft. We deploy HouYi on 36 actual LLM-integrated applications and discern 31 applications susceptible to prompt injection. 10 vendors have validated our discoveries, including Notion, which has the potential to impact millions of users. Our investigation illuminates both the possible risks of prompt injection attacks and the possible tactics for mitigation.

[Arxiv](https://arxiv.org/abs/2306.05499)