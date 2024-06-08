# 针对集成 LLM 应用的提示注入攻击：探索其安全挑战与防护策略

发布时间：2024年03月02日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在集成应用中的安全问题，特别是针对提示注入攻击的分析和后果。研究通过开发一种新的黑盒提示注入攻击技术（HouYI），揭示了现有LLM应用中存在的安全漏洞，并提出了可能的防御策略。这与LLM的实际应用场景紧密相关，因此归类为LLM应用。` `人工智能`

> Prompt Injection attack against LLM-integrated Applications

# 摘要

> 大型语言模型（LLMs）因其卓越的语言处理能力而激发了丰富的应用生态，但广泛融入服务也带来了显著的安全隐患。本研究深入分析了针对集成LLM应用的提示注入攻击的复杂性和后果。我们首先对十个商业应用进行了初步分析，指出了现有攻击策略的局限。基于此，我们开发了HouYi，一种创新的黑盒提示注入攻击技术，灵感源自传统网络注入攻击。HouYi包含三个核心组件：无缝嵌入的预设提示、诱导上下文分隔的注入提示和实现攻击目的的恶意负载。通过HouYi，我们发现了如无限制LLM使用和简单提示盗窃等严重的新攻击后果。在36个集成LLM的应用上测试HouYi，发现31个易受攻击。包括Notion在内的10家供应商已确认我们的发现，这可能影响数百万用户。我们的研究不仅揭示了提示注入攻击的风险，也提出了可能的防御策略。

> Large Language Models (LLMs), renowned for their superior proficiency in language comprehension and generation, stimulate a vibrant ecosystem of applications around them. However, their extensive assimilation into various services introduces significant security risks. This study deconstructs the complexities and implications of prompt injection attacks on actual LLM-integrated applications. Initially, we conduct an exploratory analysis on ten commercial applications, highlighting the constraints of current attack strategies in practice. Prompted by these limitations, we subsequently formulate HouYi, a novel black-box prompt injection attack technique, which draws inspiration from traditional web injection attacks. HouYi is compartmentalized into three crucial elements: a seamlessly-incorporated pre-constructed prompt, an injection prompt inducing context partition, and a malicious payload designed to fulfill the attack objectives. Leveraging HouYi, we unveil previously unknown and severe attack outcomes, such as unrestricted arbitrary LLM usage and uncomplicated application prompt theft. We deploy HouYi on 36 actual LLM-integrated applications and discern 31 applications susceptible to prompt injection. 10 vendors have validated our discoveries, including Notion, which has the potential to impact millions of users. Our investigation illuminates both the possible risks of prompt injection attacks and the possible tactics for mitigation.

[Arxiv](https://arxiv.org/abs/2306.05499)