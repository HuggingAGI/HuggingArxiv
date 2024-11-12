# 在上下文学习任务中比较自下而上和自上而下的引导方法

发布时间：2024年11月11日

`LLM理论` `语言模型` `可解释性`

> Comparing Bottom-Up and Top-Down Steering Approaches on In-Context Learning Tasks

# 摘要

> 大型语言模型（LLM）的可解释性研究的一个关键目标是开发出能稳健地引导模型达到期望行为的方法。为此，已经提出了两种不同的可解释性方法——“自下而上”和“自上而下”，但它们之间很少有定量的比较。我们提出了一个案例研究，比较了每个分支的代表性向量引导方法的有效性：作为自下而上方法的函数向量（FV；arXiv:2310.15213），以及作为自上而下方法的上下文向量（ICV；arXiv:2311.06668）。虽然两者都旨在捕捉广泛的上下文学习任务的紧凑表示，但我们发现它们仅在特定类型的任务上有效：ICV 在行为转变方面优于 FV，而 FV 在需要更高精度的任务中表现出色。鉴于这些发现，我们讨论了对未来引导方法评估以及对自上而下和自下而上引导的进一步研究的影响。

> A key objective of interpretability research on large language models (LLMs) is to develop methods for robustly steering models toward desired behaviors. To this end, two distinct approaches to interpretability -- ``bottom-up" and ``top-down" -- have been presented, but there has been little quantitative comparison between them. We present a case study comparing the effectiveness of representative vector steering methods from each branch: function vectors (FV; arXiv:2310.15213), as a bottom-up method, and in-context vectors (ICV; arXiv:2311.06668) as a top-down method. While both aim to capture compact representations of broad in-context learning tasks, we find they are effective only on specific types of tasks: ICVs outperform FVs in behavioral shifting, whereas FVs excel in tasks requiring more precision. We discuss the implications for future evaluations of steering methods and for further research into top-down and bottom-up steering given these findings.

[Arxiv](https://arxiv.org/abs/2411.07213)