# 《独步江湖：软提示调优、LoRA 与情境学习在安全隐私领域的较量》

发布时间：2023年10月17日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在处理私有数据时的隐私和安全问题，并系统地评估了多种技术（如LoRA、SPT和ICL）在面对特定攻击时的表现。这些内容更偏向于理论分析和评估，而不是具体的应用实例或Agent的设计与实现。因此，将其归类为LLM理论是合适的。` `隐私保护`

> Last One Standing: A Comparative Analysis of Security and Privacy of Soft Prompt Tuning, LoRA, and In-Context Learning

# 摘要

> 大型语言模型（LLMs）极大地推动了自然语言处理领域的发展，带来了前所未有的应用和用户体验。然而，要充分发挥其潜力，往往需要利用私有数据进行优化，这无疑增加了隐私和安全的风险。目前，已有多种技术如低秩适应（LoRA）、软提示调整（SPT）和情境学习（ICL）被提出用于处理这一问题，但它们在隐私和安全方面的表现尚未得到全面评估。本研究针对这一问题，系统地考察了LoRA、SPT和ICL在面对成员推理、后门攻击和模型窃取这三种典型攻击时的表现。研究结果揭示，每种技术在隐私和安全方面都有其独特的优势与局限，目前尚无一种技术能完美解决所有问题。

> Large Language Models (LLMs) are powerful tools for natural language processing, enabling novel applications and user experiences. However, to achieve optimal performance, LLMs often require adaptation with private data, which poses privacy and security challenges. Several techniques have been proposed to adapt LLMs with private data, such as Low-Rank Adaptation (LoRA), Soft Prompt Tuning (SPT), and In-Context Learning (ICL), but their comparative privacy and security properties have not been systematically investigated. In this work, we fill this gap by evaluating the robustness of LoRA, SPT, and ICL against three types of well-established attacks: membership inference, which exposes data leakage (privacy); backdoor, which injects malicious behavior (security); and model stealing, which can violate intellectual property (privacy and security). Our results show that there is no silver bullet for privacy and security in LLM adaptation and each technique has different strengths and weaknesses.

[Arxiv](https://arxiv.org/abs/2310.11397)