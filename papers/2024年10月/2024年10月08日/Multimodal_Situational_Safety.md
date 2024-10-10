# 多模态情境安全

发布时间：2024年10月08日

`LLM应用` `人工智能`

> Multimodal Situational Safety

# 摘要

> 多模态大型语言模型 (MLLM) 正在飞速发展，展现出与人类及其环境互动的强大能力。然而，这种复杂性也带来了显著的安全隐患。本文首次评估并分析了名为“多模态情境安全”的新挑战，探讨了安全考量如何随用户或代理所处情境而变。我们指出，MLLM 在响应时，无论是语言还是行动，往往需在视觉上下文中评估查询的安全性。为此，我们创建了多模态情境安全基准 (MSSBench)，包含 1,820 个语言查询-图像对，其中一半安全，另一半不安全，以评估 MLLM 的情境安全性能。我们还设计了评估框架，重点分析显式安全推理、视觉理解和情境安全推理等关键方面。研究发现，当前 MLLM 在处理指令跟随中的细微安全问题时表现不佳，且难以同时应对多重情境安全挑战，这为未来研究指明了方向。此外，我们通过多代理管道协调解决安全问题，显著提升了原始 MLLM 的安全性能。更多详情请访问：mssbench.github.io。

> Multimodal Large Language Models (MLLMs) are rapidly evolving, demonstrating impressive capabilities as multimodal assistants that interact with both humans and their environments. However, this increased sophistication introduces significant safety concerns. In this paper, we present the first evaluation and analysis of a novel safety challenge termed Multimodal Situational Safety, which explores how safety considerations vary based on the specific situation in which the user or agent is engaged. We argue that for an MLLM to respond safely, whether through language or action, it often needs to assess the safety implications of a language query within its corresponding visual context. To evaluate this capability, we develop the Multimodal Situational Safety benchmark (MSSBench) to assess the situational safety performance of current MLLMs. The dataset comprises 1,820 language query-image pairs, half of which the image context is safe, and the other half is unsafe. We also develop an evaluation framework that analyzes key safety aspects, including explicit safety reasoning, visual understanding, and, crucially, situational safety reasoning. Our findings reveal that current MLLMs struggle with this nuanced safety problem in the instruction-following setting and struggle to tackle these situational safety challenges all at once, highlighting a key area for future research. Furthermore, we develop multi-agent pipelines to coordinately solve safety challenges, which shows consistent improvement in safety over the original MLLM response. Code and data: mssbench.github.io.

[Arxiv](https://arxiv.org/abs/2410.06172)