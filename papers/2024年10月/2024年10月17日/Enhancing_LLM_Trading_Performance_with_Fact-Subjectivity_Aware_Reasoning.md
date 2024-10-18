# 利用事实与主观性意识推理，提升 LLM 在交易中的表现

发布时间：2024年10月17日

`Agent` `加密货币`

> Enhancing LLM Trading Performance with Fact-Subjectivity Aware Reasoning

# 摘要

> 尽管许多研究显示，更先进的 LLM 在数学和交易等任务上表现出色，但在加密货币交易中，更强的 LLM 却往往不如较弱的 LLM。为了探究这一反直觉现象，我们深入分析了 LLM 的交易决策推理过程。我们发现，将推理过程细分为事实和主观两部分，能显著提升利润。基于此，我们开发了多代理框架 FS-ReasoningAgent，使 LLM 能同时从事实和主观推理中学习。实验证明，该框架有效提升了 LLM 在加密货币市场的交易表现。进一步的消融研究显示，在牛市中，依赖主观新闻能带来更高回报；而在熊市中，关注事实信息则更为有利。我们的代码和数据已公开，详见 \url{https://anonymous.4open.science/r/FS-ReasoningAgent-B55F/}。

> While many studies prove more advanced LLMs perform better on tasks such as math and coding, we notice that in cryptocurrency trading, stronger LLMs work worse than weaker LLMs often. To study how this counter-intuitive phenomenon occurs, we examine the LLM reasoning processes on making trading decisions. We find that separating the reasoning process into factual and subjective components can lead to higher profits. Building on this insight, we introduce a multi-agent framework, FS-ReasoningAgent, which enables LLMs to recognize and learn from both factual and subjective reasoning. Extensive experiments demonstrate that this framework enhances LLM trading performance in cryptocurrency markets. Additionally, an ablation study reveals that relying on subjective news tends to generate higher returns in bull markets, whereas focusing on factual information yields better results in bear markets. Our code and data are available at \url{https://anonymous.4open.science/r/FS-ReasoningAgent-B55F/}.

[Arxiv](https://arxiv.org/abs/2410.12464)