# 自信标记路由学习

发布时间：2024年10月17日

`LLM应用` `人工智能` `风险管理`

> Learning to Route with Confidence Tokens

# 摘要

> 大型语言模型（LLM）在多项任务中表现出色，并逐渐应用于实际场景。然而，在高风险环境下，判断 LLM 输出的可靠性尤为关键。根据答案的可信度，系统可选择将问题转交给专家，或采取安全措施。我们探讨了 LLM 在指示答案置信度方面的能力，以及这种置信度如何提升下游任务的准确性。为此，我们提出了 Self-REF，一种轻量级训练策略，帮助 LLM 可靠地表达答案的置信度。Self-REF 引入了置信度标记，便于提取置信度分数。与传统方法相比，实验表明，置信度标记在下游任务中显著提升了性能。

> Large language models (LLMs) have demonstrated impressive performance on several tasks and are increasingly deployed in real-world applications. However, especially in high-stakes settings, it becomes vital to know when the output of an LLM may be unreliable. Depending on whether an answer is trustworthy, a system can then choose to route the question to another expert, or otherwise fall back on a safe default behavior. In this work, we study the extent to which LLMs can reliably indicate confidence in their answers, and how this notion of confidence can translate into downstream accuracy gains. We propose Self-REF, a lightweight training strategy to teach LLMs to express confidence in whether their answers are correct in a reliable manner. Self-REF introduces confidence tokens into the LLM, from which a confidence score can be extracted. Compared to conventional approaches such as verbalizing confidence and examining token probabilities, we demonstrate empirically that confidence tokens show significant improvements in downstream routing and rejection learning tasks.

[Arxiv](https://arxiv.org/abs/2410.13284)