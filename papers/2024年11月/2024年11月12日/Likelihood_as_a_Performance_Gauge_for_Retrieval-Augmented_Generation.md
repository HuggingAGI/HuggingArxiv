# 似然性作为检索增强生成的性能指标

发布时间：2024年11月12日

`RAG` `语言模型`

> Likelihood as a Performance Gauge for Retrieval-Augmented Generation

# 摘要

> 最近的工作发现，大型语言模型的检索增强生成容易受到上下文中检索文档顺序的影响。然而，缺乏深入分析限制了这种现象在实践中的提示工程中的使用。在这项研究中，我们认为可能性可作为语言模型性能的有效衡量标准。通过在两个问答数据集上对各种最先进的语言模型进行实验，我们揭示了在语料库级别和实例级别答案准确性与问题可能性之间的相关性。此外，我们发现问题可能性还可以指示上下文中与任务相关信息的位置。基于这些发现，我们提出了两种使用问题可能性作为衡量标准来选择和构建提示的方法，从而获得更好的性能。我们通过实验证明了它们的有效性。此外，我们基于可能性的方法是高效的，因为它们只需要计算输入的可能性，与需要生成响应的启发式提示工程方法相比，需要的语言模型传递次数要少得多。我们的分析加深了我们对输入提示如何影响模型性能的理解，并为高效的提示优化提供了一个有前途的方向。

> Recent work finds that retrieval-augmented generation with large language models is prone to be influenced by the order of retrieved documents in the context. However, the lack of in-depth analysis limits the use of this phenomenon for prompt engineering in practice. In this study, we posit that likelihoods serve as an effective gauge for language model performance. Through experiments on two question-answering datasets with a variety of state-of-the-art language models, we reveal correlations between answer accuracy and the likelihood of the question at both the corpus level and the instance level. In addition, we find that question likelihood can also indicate the position of the task-relevant information in the context. Based on these findings, we propose two methods that use question likelihood as a gauge for selecting and constructing prompts that lead to better performance. We demonstrate their effectiveness with experiments. In addition, our likelihood-based methods are efficient, as they only need to compute the likelihood of the input, requiring much fewer language model passes than heuristic prompt engineering methods that require generating responses. Our analysis deepens our understanding of how input prompts affect model performance and provides a promising direction for efficient prompt optimization.

[Arxiv](https://arxiv.org/abs/2411.07773)