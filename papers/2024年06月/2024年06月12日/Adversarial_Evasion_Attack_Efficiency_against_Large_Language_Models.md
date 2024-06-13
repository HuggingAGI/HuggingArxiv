# 大型语言模型面临的对抗性逃避攻击效率挑战

发布时间：2024年06月12日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在面对对抗性例子时的脆弱性，并分析了不同类型的扰动对模型的影响。研究特别关注了对抗攻击的有效性、效率及实用性，这对于制定防御策略和训练更健壮的LLMs以应用于智能文本分类具有重要意义。因此，这篇论文的内容更偏向于LLM的实际应用层面，即如何提高模型在实际应用中的鲁棒性和安全性，而不是理论研究或Agent、RAG相关的研究。` `文本分类` `情感分析`

> Adversarial Evasion Attack Efficiency against Large Language Models

# 摘要

> 大型语言模型（LLMs）虽在文本分类中表现出色，但其脆弱性不容小觑。面对对抗性例子，它们的抵抗力不足，因此探究不同扰动类型对模型的影响至关重要，并需评估普通用户是否能通过少量扰动和查询轻易复制这些攻击。本研究针对五种LLMs在情感分类任务上，分析了三种对抗攻击的有效性、效率及实用性。研究发现，字级攻击虽更有效，但字符级及更受限的攻击更实用，所需扰动和查询更少。这些差异在制定对抗防御策略、训练更健壮的LLMs以应用于智能文本分类时，必须予以考虑。

> Large Language Models (LLMs) are valuable for text classification, but their vulnerabilities must not be disregarded. They lack robustness against adversarial examples, so it is pertinent to understand the impacts of different types of perturbations, and assess if those attacks could be replicated by common users with a small amount of perturbations and a small number of queries to a deployed LLM. This work presents an analysis of the effectiveness, efficiency, and practicality of three different types of adversarial attacks against five different LLMs in a sentiment classification task. The obtained results demonstrated the very distinct impacts of the word-level and character-level attacks. The word attacks were more effective, but the character and more constrained attacks were more practical and required a reduced number of perturbations and queries. These differences need to be considered during the development of adversarial defense strategies to train more robust LLMs for intelligent text classification applications.

[Arxiv](https://arxiv.org/abs/2406.08050)