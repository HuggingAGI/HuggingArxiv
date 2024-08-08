# EnJa：针对大型语言模型的集成越狱技术

发布时间：2024年08月07日

`LLM应用` `网络安全` `人工智能安全`

> EnJa: Ensemble Jailbreak on Large Language Models

# 摘要

> 随着 LLM 在安全关键领域的应用日益广泛，其对恶意提示的脆弱性——这些提示能绕过安全机制——引起了广泛关注。尽管有对齐技术保护，但 LLM 仍可能被精心设计的恶意提示攻破，生成违规内容。现有攻击手段包括提示级绕过策略和令牌级对抗方法。我们提出 Ensemble Jailbreak 概念，整合两类攻击为更强大的混合策略。具体而言，EnJa 攻击通过提示级手段隐藏恶意指令，借助梯度攻击提升成功率，并利用模板连接器融合两类攻击。实验显示，EnJa 在多个对齐模型上表现卓越，以更少查询达到顶尖攻击效果，远超单一攻击手段。

> As Large Language Models (LLMs) are increasingly being deployed in safety-critical applications, their vulnerability to potential jailbreaks -- malicious prompts that can disable the safety mechanism of LLMs -- has attracted growing research attention. While alignment methods have been proposed to protect LLMs from jailbreaks, many have found that aligned LLMs can still be jailbroken by carefully crafted malicious prompts, producing content that violates policy regulations. Existing jailbreak attacks on LLMs can be categorized into prompt-level methods which make up stories/logic to circumvent safety alignment and token-level attack methods which leverage gradient methods to find adversarial tokens. In this work, we introduce the concept of Ensemble Jailbreak and explore methods that can integrate prompt-level and token-level jailbreak into a more powerful hybrid jailbreak attack. Specifically, we propose a novel EnJa attack to hide harmful instructions using prompt-level jailbreak, boost the attack success rate using a gradient-based attack, and connect the two types of jailbreak attacks via a template-based connector. We evaluate the effectiveness of EnJa on several aligned models and show that it achieves a state-of-the-art attack success rate with fewer queries and is much stronger than any individual jailbreak.

[Arxiv](https://arxiv.org/abs/2408.03603)