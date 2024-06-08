# 《独步江湖：软提示调优、LoRA 与情境学习在安全隐私领域的较量》

发布时间：2023年10月17日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在应用中的隐私和安全问题，特别是针对LoRA、SPT和ICL等技术在面对成员推理、后门攻击和模型窃取等攻击时的表现。虽然涉及了一些技术细节，但其核心关注点在于评估这些技术在实际应用中的隐私和安全性能，因此更适合归类于LLM应用。` `隐私保护`

> Last One Standing: A Comparative Analysis of Security and Privacy of Soft Prompt Tuning, LoRA, and In-Context Learning

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域展现出巨大潜力，推动了创新应用和用户体验的发展。然而，要充分发挥其性能，往往需要借助私有数据进行优化，这无疑增加了隐私和安全的风险。目前，已有如低秩适应（LoRA）、软提示调优（SPT）和情境学习（ICL）等技术尝试解决这一问题，但它们在隐私和安全方面的表现尚未得到全面评估。本研究针对LoRA、SPT和ICL，考察了它们在面对成员推理、后门攻击和模型窃取这三种典型攻击时的表现，揭示了各自在隐私和安全方面的优势与不足。研究结果表明，没有一种技术能完美解决LLM调整中的隐私和安全问题，每种方法都有其特定的适用场景和局限性。

> Large Language Models (LLMs) are powerful tools for natural language processing, enabling novel applications and user experiences. However, to achieve optimal performance, LLMs often require adaptation with private data, which poses privacy and security challenges. Several techniques have been proposed to adapt LLMs with private data, such as Low-Rank Adaptation (LoRA), Soft Prompt Tuning (SPT), and In-Context Learning (ICL), but their comparative privacy and security properties have not been systematically investigated. In this work, we fill this gap by evaluating the robustness of LoRA, SPT, and ICL against three types of well-established attacks: membership inference, which exposes data leakage (privacy); backdoor, which injects malicious behavior (security); and model stealing, which can violate intellectual property (privacy and security). Our results show that there is no silver bullet for privacy and security in LLM adaptation and each technique has different strengths and weaknesses.

[Arxiv](https://arxiv.org/abs/2310.11397)