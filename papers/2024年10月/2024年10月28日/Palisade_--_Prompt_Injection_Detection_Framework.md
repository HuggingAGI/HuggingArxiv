# Palisade——提示注入检测框架

发布时间：2024年10月28日

`LLM应用` `人工智能` `网络安全`

> Palisade -- Prompt Injection Detection Framework

# 摘要

> 大型语言模型（LLM）的出现标志着人工智能的一个里程碑，改变了机器理解和生成人类语言的方式。然而，LLM 容易受到恶意提示注入攻击，精心设计的输入会以意想不到的方式操纵模型的行为，损害系统完整性并导致错误结果。传统的检测方法依赖于静态的、基于规则的方法，这些方法往往无法应对复杂的威胁，如异常令牌序列和别名替换，导致适应性有限，误报率和漏报率较高。本文提出了一种基于 NLP 的新型提示注入检测方法，通过分层输入筛选过程强调准确性和优化。在这个框架中，提示在到达目标模型之前要经过三个不同的层——基于规则的层、ML 分类器层和配套的 LLM 层，从而将恶意交互的风险降至最低。测试表明，ML 分类器在各个层中实现了最高的准确率，但多层框架通过减少漏报提高了整体检测准确率。虽然这增加了误报，但它将忽略真正注入提示的风险降至最低，从而优先考虑安全性。这种多层检测方法突出了 LLM 的漏洞，并为未来的研究提供了一个全面的框架，促进了人类和 AI 系统之间的安全交互。

> The advent of Large Language Models LLMs marks a milestone in Artificial Intelligence, altering how machines comprehend and generate human language. However, LLMs are vulnerable to malicious prompt injection attacks, where crafted inputs manipulate the models behavior in unintended ways, compromising system integrity and causing incorrect outcomes. Conventional detection methods rely on static, rule-based approaches, which often fail against sophisticated threats like abnormal token sequences and alias substitutions, leading to limited adaptability and higher rates of false positives and false negatives.This paper proposes a novel NLP based approach for prompt injection detection, emphasizing accuracy and optimization through a layered input screening process. In this framework, prompts are filtered through three distinct layers rule-based, ML classifier, and companion LLM before reaching the target model, thereby minimizing the risk of malicious interaction.Tests show the ML classifier achieves the highest accuracy among individual layers, yet the multi-layer framework enhances overall detection accuracy by reducing false negatives. Although this increases false positives, it minimizes the risk of overlooking genuine injected prompts, thus prioritizing security.This multi-layered detection approach highlights LLM vulnerabilities and provides a comprehensive framework for future research, promoting secure interactions between humans and AI systems.

[Arxiv](https://arxiv.org/abs/2410.21146)