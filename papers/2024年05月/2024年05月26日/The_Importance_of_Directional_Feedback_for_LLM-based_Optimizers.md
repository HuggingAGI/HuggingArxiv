# 在基于LLM的优化器中，方向性反馈的重要性不容忽视。

发布时间：2024年05月26日

`Agent

理由：这篇论文探讨了大型语言模型（LLMs）作为交互式优化器的应用，特别是在接收方向性反馈时展现出的优化能力。这种应用涉及到模型与环境的交互，通过自然语言和数值反馈来解决问题，这符合Agent的定义，即一个能够感知环境并采取行动以达到目标的系统。因此，这篇论文更适合归类为Agent。` `优化算法`

> The Importance of Directional Feedback for LLM-based Optimizers

# 摘要

> 我们探索了大型语言模型（LLMs）作为交互式优化器的潜力，通过自然语言和数值反馈在文本空间中解决最大化问题。借鉴经典优化理论，我们将反馈分为方向性和非方向性，其中方向性反馈是自然语言空间中一阶反馈的扩展。我们发现，当接收到方向性反馈时，LLMs展现出卓越的优化能力。基于此，我们开发了一种新型LLM优化器，它能够从历史优化记录中提取方向性反馈，实现迭代中的稳定提升。实证研究显示，无论是最大化数学函数还是优化诗歌创作提示，我们的LLM优化器都比现有技术更为稳定和高效。

> We study the potential of using large language models (LLMs) as an interactive optimizer for solving maximization problems in a text space using natural language and numerical feedback. Inspired by the classical optimization literature, we classify the natural language feedback into directional and non-directional, where the former is a generalization of the first-order feedback to the natural language space. We find that LLMs are especially capable of optimization when they are provided with {directional feedback}. Based on this insight, we design a new LLM-based optimizer that synthesizes directional feedback from the historical optimization trace to achieve reliable improvement over iterations. Empirically, we show our LLM-based optimizer is more stable and efficient in solving optimization problems, from maximizing mathematical functions to optimizing prompts for writing poems, compared with existing techniques.

![在基于LLM的优化器中，方向性反馈的重要性不容忽视。](../../../paper_images/2405.16434/x1.png)

![在基于LLM的优化器中，方向性反馈的重要性不容忽视。](../../../paper_images/2405.16434/x2.png)

![在基于LLM的优化器中，方向性反馈的重要性不容忽视。](../../../paper_images/2405.16434/x3.png)

![在基于LLM的优化器中，方向性反馈的重要性不容忽视。](../../../paper_images/2405.16434/x4.png)

[Arxiv](https://arxiv.org/abs/2405.16434)