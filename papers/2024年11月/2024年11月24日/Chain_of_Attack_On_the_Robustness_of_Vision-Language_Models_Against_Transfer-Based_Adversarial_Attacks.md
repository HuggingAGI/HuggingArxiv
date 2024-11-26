# 《链状攻击：论视觉语言模型抵御基于转移的对抗性攻击的鲁棒性》

发布时间：2024年11月24日

`LLM应用` `计算机视觉`

> Chain of Attack: On the Robustness of Vision-Language Models Against Transfer-Based Adversarial Attacks

# 摘要

> 预训练的视觉语言模型（VLMs）在图像与自然语言理解领域，比如图像字幕生成和响应生成方面，表现出众。随着VLMs的实际应用愈发广泛，其潜在的安全和鲁棒性问题引发担忧，对手可能会绕过系统，通过恶意攻击致使这些模型生成有害内容。故而，评估开源VLMs抵御对抗性攻击的鲁棒性备受关注，其中基于转移的攻击是典型的黑箱攻击策略。然而，现有的多数基于转移的攻击都忽视了视觉与文本模态间语义关联的重要性，致使对抗性示例的生成和攻击效果欠佳。为解决此问题，我们提出了攻击链（CoA），它借助一系列中间攻击步骤，基于多模态语义更新来迭代增强对抗性示例的生成，达成了出色的对抗转移性和效率。此外，还进一步提出了统一的攻击成功率计算方法用于自动逃避评估。在最真实且高风险的场景下开展的大量实验表明，我们的攻击策略仅通过黑箱攻击就能有效误导模型生成目标响应，无需知晓受害模型的任何信息。我们论文中的综合鲁棒性评估为VLMs的漏洞提供了洞察，并为未来模型开发的安全考量提供了参考。

> Pre-trained vision-language models (VLMs) have showcased remarkable performance in image and natural language understanding, such as image captioning and response generation. As the practical applications of vision-language models become increasingly widespread, their potential safety and robustness issues raise concerns that adversaries may evade the system and cause these models to generate toxic content through malicious attacks. Therefore, evaluating the robustness of open-source VLMs against adversarial attacks has garnered growing attention, with transfer-based attacks as a representative black-box attacking strategy. However, most existing transfer-based attacks neglect the importance of the semantic correlations between vision and text modalities, leading to sub-optimal adversarial example generation and attack performance. To address this issue, we present Chain of Attack (CoA), which iteratively enhances the generation of adversarial examples based on the multi-modal semantic update using a series of intermediate attacking steps, achieving superior adversarial transferability and efficiency. A unified attack success rate computing method is further proposed for automatic evasion evaluation. Extensive experiments conducted under the most realistic and high-stakes scenario, demonstrate that our attacking strategy can effectively mislead models to generate targeted responses using only black-box attacks without any knowledge of the victim models. The comprehensive robustness evaluation in our paper provides insight into the vulnerabilities of VLMs and offers a reference for the safety considerations of future model developments.

[Arxiv](https://arxiv.org/abs/2411.15720)