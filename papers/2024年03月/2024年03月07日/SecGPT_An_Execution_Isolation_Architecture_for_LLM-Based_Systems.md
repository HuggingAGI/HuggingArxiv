# [SecGPT是一种专为基于大型语言模型（LLM）的系统设计的执行隔离架构，旨在确保其安全性和稳定性。]

发布时间：2024年03月07日

`Agent`

> SecGPT: An Execution Isolation Architecture for LLM-Based Systems

> 如今，类似ChatGPT这样的大型语言模型扩展系统开始支持第三方应用，它们巧妙运用LLMs的自然语言自动化执行机制，让应用及互动过程皆可通过自然语言定义并接入用户数据，彼此间可自由交流互动。然而，这种生态系统的开放性类似于早期计算平台，因缺乏有效的隔离措施，加上第三方应用可信度不定及自然语言接口的模糊性，使得现有设计潜藏安全隐患与隐私风险。为此，本论文提出名为SecGPT的LLM系统架构，旨在减轻第三方应用执行带来的安全和隐私隐患。SecGPT创新之处在于对应用执行进行隔离，并对其外部交互进行精确调解。我们通过多种实例攻击检验SecGPT的有效性，结果显示SecGPT成功抵御了大量存在于非隔离LLM系统中的安全、隐私和安全问题。值得一提的是，在大部分测试查询中，SecGPT引入的安全增强仅带来不超过0.3倍的性能开销。为了进一步推动相关领域的研究进展，我们已将SecGPT源代码公开在https://github.com/llm-platform-security/SecGPT网站上。

> Large language models (LLMs) extended as systems, such as ChatGPT, have begun supporting third-party applications. These LLM apps leverage the de facto natural language-based automated execution paradigm of LLMs: that is, apps and their interactions are defined in natural language, provided access to user data, and allowed to freely interact with each other and the system. These LLM app ecosystems resemble the settings of earlier computing platforms, where there was insufficient isolation between apps and the system. Because third-party apps may not be trustworthy, and exacerbated by the imprecision of the natural language interfaces, the current designs pose security and privacy risks for users. In this paper, we propose SecGPT, an architecture for LLM-based systems that aims to mitigate the security and privacy issues that arise with the execution of third-party apps. SecGPT's key idea is to isolate the execution of apps and more precisely mediate their interactions outside of their isolated environments. We evaluate SecGPT against a number of case study attacks and demonstrate that it protects against many security, privacy, and safety issues that exist in non-isolated LLM-based systems. The performance overhead incurred by SecGPT to improve security is under 0.3x for three-quarters of the tested queries. To foster follow-up research, we release SecGPT's source code at https://github.com/llm-platform-security/SecGPT.

[Arxiv](https://arxiv.org/abs/2403.04960)