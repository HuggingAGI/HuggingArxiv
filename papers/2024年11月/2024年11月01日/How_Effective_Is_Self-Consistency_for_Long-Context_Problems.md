# 长上下文问题中，自我一致性的效果究竟如何？

发布时间：2024年11月01日

`LLM应用` `语言模型`

> How Effective Is Self-Consistency for Long-Context Problems?

# 摘要

> 自我一致性（SC）已被证实能够提升大型语言模型（LLMs）在涉及短内容的各类任务和领域中的表现。然而，这能否证明它对长上下文问题也有效呢？本研究探究了 SC 在长上下文情境中的作用，在这种情境中，LLMs 常受位置偏差的影响，难以有效利用长输入上下文中各部分的信息。我们考察了一系列设计参数，涵盖不同模型、上下文长度、提示格式以及数据集和任务的类型。我们的研究发现，SC 虽对短上下文问题有效，但在长上下文任务中却完全失效——它不仅无法缓解位置偏差，甚至还会使性能下降。我们观察到，SC 的有效性随上下文长度和模型大小而变，但基本不受提示格式或任务类型的影响。这些结果为当前 LLMs 在长上下文理解上的局限性提供了宝贵的见解，也突出了需要更精妙的方法来解决这些模型中的位置偏差问题。

> Self-consistency (SC) has been demonstrated to enhance the performance of large language models (LLMs) across various tasks and domains involving short content. However, does this evidence support its effectiveness for long-context problems? This study examines the role of SC in long-context scenarios, where LLMs often struggle with position bias, hindering their ability to utilize information effectively from all parts of their long input context. We examine a range of design parameters, including different models, context lengths, prompt formats, and types of datasets and tasks. Our findings demonstrate that SC, while effective for short-context problems, fundamentally fails for long-context tasks -- not only does it fail to mitigate position bias, but it can also actively degrade performance. We observe that the effectiveness of SC varies with context length and model size but remains mainly unaffected by prompt format or task type. These results provide valuable insight into the limitations of current LLMs in long-context understanding and highlight the need for more sophisticated approaches to address position bias in these models.

[Arxiv](https://arxiv.org/abs/2411.01101)