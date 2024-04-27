# MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。

发布时间：2024年04月16日

`分类：LLM应用

这篇论文的摘要主要讨论了如何提高大型语言模型（LLM）在事实核查任务中的效率和准确性。它提出了一种新的方法，通过生成合成训练数据和结构化生成流程来训练一个小型模型，该模型在性能上可以与大型模型相媲美，但成本降低了400倍。此外，论文还介绍了一个新的基准集LLM-AggreFact，用于评估模型在事实核查任务上的表现。这些内容都与LLM的应用相关，因此将这篇论文归类为LLM应用。` `事实核查`

> MiniCheck: Efficient Fact-Checking of LLMs on Grounding Documents

# 摘要

> 在自然语言处理领域，判断大型语言模型（LLM）的输出是否能够依据证据是至关重要的，这涉及到检索增强生成、摘要、文档驱动对话等多个任务。现行的“事实核查”方法主要依赖于使用LLM对模型生成的内容逐项与潜在证据进行核对，但这一过程计算成本极高，需要多次调用LLM来核实单一回复。本研究展示了如何以400倍的成本降低，构建出性能媲美GPT-4的小型模型。我们通过利用GPT-4生成合成训练数据，创造性地构建出既真实又具有挑战性的事实错误案例，并通过结构化生成流程来实现。在这些数据上训练的模型学会了检查声明中的每个事实，并能够识别跨句的信息整合。为了评估，我们将现有的数据集整合成一个新的基准集LLM-AggreFact，它来源于近期关于LLM生成的事实核查和证据基础的研究。我们的最佳系统MiniCheck-FT5（参数量为7.7亿）在同等规模的系统中表现最优，并达到了GPT-4的准确度。我们还发布了LLM-AggreFact基准集、数据合成的代码以及模型。

> Recognizing if LLM output can be grounded in evidence is central to many tasks in NLP: retrieval-augmented generation, summarization, document-grounded dialogue, and more. Current approaches to this kind of "fact-checking" are based on verifying each piece of a model generation against potential evidence using an LLM. However, this process can be very computationally expensive, requiring many calls to LLMs to check a single response. In this work, we show how to build small models that have GPT-4-level performance but for 400x lower cost. We do this by constructing synthetic training data with GPT-4, which involves creating realistic yet challenging instances of factual errors via a structured generation procedure. Training on this data teaches models to check each fact in the claim and recognize synthesis of information across sentences. For evaluation, we unify pre-existing datasets into a benchmark LLM-AggreFact, collected from recent work on fact-checking and grounding LLM generations. Our best system MiniCheck-FT5 (770M parameters) outperforms all systems of comparable size and reaches GPT-4 accuracy. We release LLM-AggreFact, code for data synthesis, and models.

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x1.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x2.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x3.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x4.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x5.png)

[Arxiv](https://arxiv.org/abs/2404.10774)