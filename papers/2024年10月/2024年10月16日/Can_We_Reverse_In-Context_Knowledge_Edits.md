# 上下文知识编辑能否被逆转？

发布时间：2024年10月16日

`LLM应用` `网络安全` `人工智能`

> Can We Reverse In-Context Knowledge Edits?

# 摘要

> In-context knowledge editing (IKE) 能在不改参数、零成本的情况下，高效修改大型语言模型 (LLM) 的输出。但这种技术也可能被滥用，比如暗中插入错误信息或冒犯性内容。为了应对这一风险，我们研究了如何检测和反转 IKE 编辑。实验证明，即使在黑箱环境下，仅凭下一个标记的前 10 个输出概率，也能以高准确率 (F1 > 80\%) 检测到 IKE 编辑。我们还创新性地引入了反转 IKE 编辑的任务，通过特别调整的反转标记，成功恢复了原始输出，准确率超过 80\%。特别是连续反转标记，对未编辑提示的影响极小。通过深入分析输出分布、注意力模式和标记排名，我们揭示了 IKE 对 LLM 的影响及反转标记的缓解作用。这项研究为提升 LLM 的透明度和可信度，抵御潜在滥用，迈出了重要一步。

> In-context knowledge editing (IKE) enables efficient modification of large language model (LLM) outputs without parameter changes and at zero-cost. However, it can be misused to manipulate responses opaquely, e.g., insert misinformation or offensive content. Such malicious interventions could be incorporated into high-level wrapped APIs where the final input prompt is not shown to end-users. To address this issue, we investigate the detection and reversal of IKE-edits. First, we demonstrate that IKE-edits can be detected with high accuracy (F1 > 80\%) using only the top-10 output probabilities of the next token, even in a black-box setting, e.g. proprietary LLMs with limited output information. Further, we introduce the novel task of reversing IKE-edits using specially tuned reversal tokens. We explore using both continuous and discrete reversal tokens, achieving over 80\% accuracy in recovering original, unedited outputs across multiple LLMs. Our continuous reversal tokens prove particularly effective, with minimal impact on unedited prompts. Through analysis of output distributions, attention patterns, and token rankings, we provide insights into IKE's effects on LLMs and how reversal tokens mitigate them. This work represents a significant step towards enhancing LLM resilience against potential misuse of in-context editing, improving their transparency and trustworthiness.

[Arxiv](https://arxiv.org/abs/2410.12586)