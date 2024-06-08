# 《独步江湖：软提示调优、LoRA 与情境学习在安全隐私领域的较量》

发布时间：2023年10月17日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在处理私有数据时的隐私和安全问题，并评估了多种技术（如LoRA、SPT和ICL）在面对特定攻击时的性能。虽然涉及到了一些技术细节和理论分析，但其核心关注点在于LLMs在实际应用中的安全性和隐私保护，因此更适合归类于LLM应用。` `隐私保护`

> Last One Standing: A Comparative Analysis of Security and Privacy of Soft Prompt Tuning, LoRA, and In-Context Learning

# 摘要

> 大型语言模型（LLMs）极大地推动了自然语言处理领域的发展，带来了前所未有的应用和用户体验。然而，要发挥其最大潜力，往往需要借助私有数据进行优化，这无疑增加了隐私和安全的风险。目前，已有多种技术如低秩适应（LoRA）、软提示调优（SPT）和情境学习（ICL）被提出用于LLMs的私有数据适应，但这些技术的隐私和安全性能比较尚未得到深入探讨。本研究针对这一问题，评估了LoRA、SPT和ICL在面对成员推理、后门攻击和模型窃取这三种典型攻击时的鲁棒性。研究结果揭示，没有一种技术能在隐私和安全方面完美无缺，每种技术都有其独特的优势与局限。

> Large Language Models (LLMs) are powerful tools for natural language processing, enabling novel applications and user experiences. However, to achieve optimal performance, LLMs often require adaptation with private data, which poses privacy and security challenges. Several techniques have been proposed to adapt LLMs with private data, such as Low-Rank Adaptation (LoRA), Soft Prompt Tuning (SPT), and In-Context Learning (ICL), but their comparative privacy and security properties have not been systematically investigated. In this work, we fill this gap by evaluating the robustness of LoRA, SPT, and ICL against three types of well-established attacks: membership inference, which exposes data leakage (privacy); backdoor, which injects malicious behavior (security); and model stealing, which can violate intellectual property (privacy and security). Our results show that there is no silver bullet for privacy and security in LLM adaptation and each technique has different strengths and weaknesses.

[Arxiv](https://arxiv.org/abs/2310.11397)