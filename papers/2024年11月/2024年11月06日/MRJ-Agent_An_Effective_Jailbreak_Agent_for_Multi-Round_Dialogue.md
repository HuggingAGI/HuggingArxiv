# MRJ-Agent：一种用于多轮对话的有效越狱代理

发布时间：2024年11月06日

`Agent` `语言模型` `多轮对话`

> MRJ-Agent: An Effective Jailbreak Agent for Multi-Round Dialogue

# 摘要

> 大型语言模型（LLMs）在知识储备和理解能力方面表现出色，但在遭受越狱攻击时，它们也被证明容易产生非法或不道德的反应。为确保其在关键应用中的负责任部署，了解 LLMs 的安全能力和漏洞至关重要。以前的工作主要集中在单轮对话中的越狱，忽略了多轮对话中潜在的越狱风险，而多轮对话是人类与 LLMs 交互并从中提取信息的重要方式。一些研究越来越关注多轮对话中与越狱相关的风险。这些努力通常涉及使用手工制作的模板或提示工程技术。然而，由于多轮对话的固有复杂性，它们的越狱性能有限。为了解决这个问题，我们提出了一种新颖的多轮对话越狱代理，强调了在识别和减轻 LLMs 对人类价值观构成的潜在威胁时隐秘性的重要性。我们提出了一种风险分解策略，将风险分布在多轮查询中，并利用心理策略来增强攻击强度。大量实验表明，我们提出的方法超过了其他攻击方法，并达到了最先进的攻击成功率。我们将提供相应的代码和数据集以供未来研究。代码即将发布。

> Large Language Models (LLMs) demonstrate outstanding performance in their reservoir of knowledge and understanding capabilities, but they have also been shown to be prone to illegal or unethical reactions when subjected to jailbreak attacks. To ensure their responsible deployment in critical applications, it is crucial to understand the safety capabilities and vulnerabilities of LLMs. Previous works mainly focus on jailbreak in single-round dialogue, overlooking the potential jailbreak risks in multi-round dialogues, which are a vital way humans interact with and extract information from LLMs. Some studies have increasingly concentrated on the risks associated with jailbreak in multi-round dialogues. These efforts typically involve the use of manually crafted templates or prompt engineering techniques. However, due to the inherent complexity of multi-round dialogues, their jailbreak performance is limited. To solve this problem, we propose a novel multi-round dialogue jailbreaking agent, emphasizing the importance of stealthiness in identifying and mitigating potential threats to human values posed by LLMs. We propose a risk decomposition strategy that distributes risks across multiple rounds of queries and utilizes psychological strategies to enhance attack strength. Extensive experiments show that our proposed method surpasses other attack methods and achieves state-of-the-art attack success rate. We will make the corresponding code and dataset available for future research. The code will be released soon.

[Arxiv](https://arxiv.org/abs/2411.03814)