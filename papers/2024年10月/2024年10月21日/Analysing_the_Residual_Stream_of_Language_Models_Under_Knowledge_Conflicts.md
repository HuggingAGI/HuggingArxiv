# 探究语言模型在知识冲突中的残差流表现

发布时间：2024年10月21日

`LLM理论` `人工智能`

> Analysing the Residual Stream of Language Models Under Knowledge Conflicts

# 摘要

> 大型语言模型 (LLM) 虽能存储大量事实知识，但其参数知识有时会与上下文信息冲突，导致模型行为不佳，如依赖过时或错误信息。我们探讨了 LLM 能否识别这些知识冲突，并通过分析残差流来预测模型将依赖哪种知识。研究发现，LLM 能在残差流中标记冲突信号，通过探测中间激活可准确检测。这使我们能在不改动输入或模型参数的情况下，提前发现冲突。此外，残差流在模型依赖上下文或参数知识时呈现不同模式，可用于预测冲突时的模型行为，避免意外答案。我们的分析揭示了 LLM 内部处理知识冲突的方式，为控制知识选择过程提供了新思路。

> Large language models (LLMs) can store a significant amount of factual knowledge in their parameters. However, their parametric knowledge may conflict with the information provided in the context. Such conflicts can lead to undesirable model behaviour, such as reliance on outdated or incorrect information. In this work, we investigate whether LLMs can identify knowledge conflicts and whether it is possible to know which source of knowledge the model will rely on by analysing the residual stream of the LLM. Through probing tasks, we find that LLMs can internally register the signal of knowledge conflict in the residual stream, which can be accurately detected by probing the intermediate model activations. This allows us to detect conflicts within the residual stream before generating the answers without modifying the input or model parameters. Moreover, we find that the residual stream shows significantly different patterns when the model relies on contextual knowledge versus parametric knowledge to resolve conflicts. This pattern can be employed to estimate the behaviour of LLMs when conflict happens and prevent unexpected answers before producing the answers. Our analysis offers insights into how LLMs internally manage knowledge conflicts and provides a foundation for developing methods to control the knowledge selection processes.

[Arxiv](https://arxiv.org/abs/2410.16090)