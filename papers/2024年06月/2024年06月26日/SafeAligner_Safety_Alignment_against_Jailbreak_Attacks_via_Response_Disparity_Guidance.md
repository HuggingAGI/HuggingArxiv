# SafeAligner：利用响应差异指导，确保模型安全对齐，抵御越狱攻击

发布时间：2024年06月26日

`Agent

理由：这篇论文介绍了一种名为SafeAligner的新策略，用于在解码阶段增强大型语言模型（LLMs）对越狱攻击的防御能力。它通过构建两个专精模型（哨兵模型和入侵者模型）并利用它们之间的安全水平差异来区分和调整输出令牌，以实现安全对齐。这种策略涉及到模型的主动防御和调整，类似于一个智能代理（Agent）的行为，因此归类为Agent。` `网络安全` `人工智能安全`

> SafeAligner: Safety Alignment against Jailbreak Attacks via Response Disparity Guidance

# 摘要

> 随着大型语言模型（LLMs）的迅猛发展，如何在不损害其效能的前提下确保其安全已成为研究的重中之重。然而，现有的防御策略在面对越狱攻击（即试图绕过安全措施的行为）时，往往因适应性不足、通用性受限及成本高昂而显得力不从心。为此，我们推出了SafeAligner，一种在解码阶段实施的新策略，旨在强化对越狱攻击的防御。我们首先构建了两个专精模型：哨兵模型，专注于提升安全性；入侵者模型，则致力于生成更具风险的回应。SafeAligner巧妙利用这两模型间安全水平的差异，精准区分有害与有益的令牌，通过调整目标模型的输出令牌分布，引导安全对齐。大量实验证明，SafeAligner能有效提升有益令牌的出现概率，同时降低有害令牌的频率，确保安全对齐的同时，几乎不牺牲模型的通用性。

> As the development of large language models (LLMs) rapidly advances, securing these models effectively without compromising their utility has become a pivotal area of research. However, current defense strategies against jailbreak attacks (i.e., efforts to bypass security protocols) often suffer from limited adaptability, restricted general capability, and high cost. To address these challenges, we introduce SafeAligner, a methodology implemented at the decoding stage to fortify defenses against jailbreak attacks. We begin by developing two specialized models: the Sentinel Model, which is trained to foster safety, and the Intruder Model, designed to generate riskier responses. SafeAligner leverages the disparity in security levels between the responses from these models to differentiate between harmful and beneficial tokens, effectively guiding the safety alignment by altering the output token distribution of the target model. Extensive experiments show that SafeAligner can increase the likelihood of beneficial tokens, while reducing the occurrence of harmful ones, thereby ensuring secure alignment with minimal loss to generality.

[Arxiv](https://arxiv.org/abs/2406.18118)