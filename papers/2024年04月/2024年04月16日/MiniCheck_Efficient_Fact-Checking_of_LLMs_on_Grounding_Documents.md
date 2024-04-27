# MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。

发布时间：2024年04月16日

`LLM应用` `事实核查`

> MiniCheck: Efficient Fact-Checking of LLMs on Grounding Documents

# 摘要

> 在自然语言处理领域，判断大型语言模型（LLM）的输出是否能够以证据为基础，对于检索增强生成、摘要、文档驱动对话等任务至关重要。现行的“事实核查”方法通常涉及使用LLM对模型生成的每个信息片段与潜在证据进行逐一核对，这一过程计算成本高昂，需多次调用LLM来核实单一回复。本研究展示了如何以400倍的成本降低，构建出性能媲美GPT-4的小型模型。我们通过利用GPT-4创建合成训练数据，生成既真实又具挑战性的事实错误案例，并通过结构化生成流程来实现。在这些数据上的训练使模型学会核实声明中的每项事实，并识别跨句的信息整合。为了评估，我们将现有的数据集整合成一个新的基准测试集LLM-AggreFact，该数据集来源于最近关于LLM生成的事实核查和证据基础研究。我们的最佳系统MiniCheck-FT5（参数量为7.7亿）在同等规模的系统中表现最优，且达到了GPT-4的准确度。我们公开了LLM-AggreFact、数据合成代码以及模型。

> Recognizing if LLM output can be grounded in evidence is central to many tasks in NLP: retrieval-augmented generation, summarization, document-grounded dialogue, and more. Current approaches to this kind of "fact-checking" are based on verifying each piece of a model generation against potential evidence using an LLM. However, this process can be very computationally expensive, requiring many calls to LLMs to check a single response. In this work, we show how to build small models that have GPT-4-level performance but for 400x lower cost. We do this by constructing synthetic training data with GPT-4, which involves creating realistic yet challenging instances of factual errors via a structured generation procedure. Training on this data teaches models to check each fact in the claim and recognize synthesis of information across sentences. For evaluation, we unify pre-existing datasets into a benchmark LLM-AggreFact, collected from recent work on fact-checking and grounding LLM generations. Our best system MiniCheck-FT5 (770M parameters) outperforms all systems of comparable size and reaches GPT-4 accuracy. We release LLM-AggreFact, code for data synthesis, and models.

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x1.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x2.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x3.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x4.png)

![MiniCheck：一种高效的事实核查工具，专为在基础文档上验证大型语言模型（LLMs）的真实性而设计。](../../../paper_images/2404.10774/x5.png)

[Arxiv](https://arxiv.org/abs/2404.10774)