# Tastle 是一种技术，通过干扰大型语言模型以实现针对目标系统的自动越狱攻击。

发布时间：2024年03月13日

`LLM应用` `人工智能` `安全测试`

> Tastle: Distract Large Language Models for Automatic Jailbreak Attack

# 摘要

> 近年来，LLMs取得了显著的进步，在公开前已付出了巨大努力以确保其行为符合人类价值观，主要目标在于保证其有益、诚实及无害。然而，即便是精心校准的LLMs也无法幸免于诸如越狱之类的恶意操控，从而引发意料之外的行为。所谓越狱，即刻意构造能够规避LLM安全限制的恶意提示，进而生成未经审查的有害内容。此前已有研究尝试采用不同越狱方法对LLMs进行红队测试，但面临着效果与规模化上的难题。为此，我们创新提出了Tastle这一针对LLMs自动红队测试的黑盒越狱框架。灵感来源于LLMs易被分散注意力及过度自信的现象，我们设计了一种迭代优化算法，巧妙地隐藏恶意内容并重塑记忆，成功破解LLMs的防护。广泛的越狱实验证明了该框架在开放源码和专有LLMs上具备卓越的有效性、可扩展性和迁移性。同时，我们也评估了现有越狱防御手段对抗我们攻击的有效程度，并着重指出研发更高效实用的防御策略的急迫性。

> Large language models (LLMs) have achieved significant advances in recent days. Extensive efforts have been made before the public release of LLMs to align their behaviors with human values. The primary goal of alignment is to ensure their helpfulness, honesty and harmlessness. However, even meticulously aligned LLMs remain vulnerable to malicious manipulations such as jailbreaking, leading to unintended behaviors. The jailbreak is to intentionally develop a malicious prompt that escapes from the LLM security restrictions to produce uncensored detrimental contents. Previous works explore different jailbreak methods for red teaming LLMs, yet they encounter challenges regarding to effectiveness and scalability. In this work, we propose Tastle, a novel black-box jailbreak framework for automated red teaming of LLMs. We designed malicious content concealing and memory reframing with an iterative optimization algorithm to jailbreak LLMs, motivated by the research about the distractibility and over-confidence phenomenon of LLMs. Extensive experiments of jailbreaking both open-source and proprietary LLMs demonstrate the superiority of our framework in terms of effectiveness, scalability and transferability. We also evaluate the effectiveness of existing jailbreak defense methods against our attack and highlight the crucial need to develop more effective and practical defense strategies.

[Arxiv](https://arxiv.org/abs/2403.08424)