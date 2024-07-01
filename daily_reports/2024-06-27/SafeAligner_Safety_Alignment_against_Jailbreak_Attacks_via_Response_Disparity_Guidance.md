# SafeAligner：利用响应差异指导，确保模型安全对齐，抵御越狱攻击
发布时间：2024年06月26日

`模型安全`
> SafeAligner: Safety Alignment against Jailbreak Attacks via Response Disparity Guidance
>
> 随着大型语言模型（LLMs）的迅猛发展，如何在不损害其效能的前提下确保其安全已成为研究的重中之重。然而，现有的防御策略在面对越狱攻击（即试图绕过安全措施的行为）时，往往因适应性不足、通用性受限及成本高昂而显得力不从心。为此，我们推出了SafeAligner，一种在解码阶段实施的新策略，旨在强化对越狱攻击的防御。我们首先构建了两个专精模型：哨兵模型，专注于提升安全性；入侵者模型，则致力于生成更具风险的回应。SafeAligner巧妙利用这两模型间安全水平的差异，精准区分有害与有益的令牌，通过调整目标模型的输出令牌分布，引导安全对齐。大量实验证明，SafeAligner能有效提升有益令牌的出现概率，同时降低有害令牌的频率，确保安全对齐的同时，几乎不牺牲模型的通用性。
>
> https://arxiv.org/abs/2406.18118


<hr />

- 论文原文: [https://arxiv.org/abs/2406.18118](https://arxiv.org/abs/2406.18118)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1