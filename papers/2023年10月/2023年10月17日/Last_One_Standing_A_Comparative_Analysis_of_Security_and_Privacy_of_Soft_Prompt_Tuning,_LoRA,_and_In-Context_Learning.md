# 《独步江湖：软提示调优、LoRA 与情境学习在安全隐私领域的较量》

发布时间：2023年10月17日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在微调过程中面临的隐私和安全挑战，并系统地比较了不同的微调技术（如LoRA、SPT和ICL）在应对特定攻击（成员推理、后门攻击和模型窃取）时的表现。这些内容更多地涉及LLM的理论层面，即如何理解和改进LLM在隐私和安全方面的性能，而不是直接的应用或特定的Agent或RAG模型。因此，将其归类为LLM理论是合适的。` `隐私保护`

> Last One Standing: A Comparative Analysis of Security and Privacy of Soft Prompt Tuning, LoRA, and In-Context Learning

# 摘要

> 大型语言模型（LLMs）为自然语言处理开辟了新天地，但为了发挥其最大潜力，往往需要借助私有数据进行微调，这无疑给隐私和安全带来了挑战。尽管已有如低秩适应（LoRA）、软提示调优（SPT）和情境学习（ICL）等技术尝试解决这一问题，但它们在隐私和安全方面的表现尚未有系统的比较。本研究针对这一空白，评估了LoRA、SPT和ICL在面对成员推理、后门攻击和模型窃取这三种攻击时的表现。结果显示，没有哪种技术能完美解决隐私和安全问题，每种技术都有其独特的优势与局限。

> Large Language Models (LLMs) are powerful tools for natural language processing, enabling novel applications and user experiences. However, to achieve optimal performance, LLMs often require adaptation with private data, which poses privacy and security challenges. Several techniques have been proposed to adapt LLMs with private data, such as Low-Rank Adaptation (LoRA), Soft Prompt Tuning (SPT), and In-Context Learning (ICL), but their comparative privacy and security properties have not been systematically investigated. In this work, we fill this gap by evaluating the robustness of LoRA, SPT, and ICL against three types of well-established attacks: membership inference, which exposes data leakage (privacy); backdoor, which injects malicious behavior (security); and model stealing, which can violate intellectual property (privacy and security). Our results show that there is no silver bullet for privacy and security in LLM adaptation and each technique has different strengths and weaknesses.

[Arxiv](https://arxiv.org/abs/2310.11397)