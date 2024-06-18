# 深呼吸：利用哨兵令牌提升大型语言模型的语言建模性能

发布时间：2024年06月16日

`LLM应用

这篇论文摘要描述了一种改进大型语言模型（LLMs）处理长篇上下文信息的方法。通过引入特殊标记和调整注意力掩码，该方法增强了LLMs在理解和总结文本块内信息的能力，从而提高了在语言建模和跨领域任务中的性能。这种方法直接应用于LLMs的实际操作中，以提升其处理长文本上下文的能力，因此属于LLM应用类别。` `文本分析`

> Taking a Deep Breath: Enhancing Language Modeling of Large Language Models with Sentinel Tokens

# 摘要

> 大型语言模型（LLMs）在多任务中表现出色，成为生活中的得力助手。但基于Transformer的LLMs在处理长篇上下文时，因减少计算负担而丢失信息，导致性能受损。为此，我们提出了一种简便高效的方法，让LLMs“深呼吸”，学会总结文本块内的信息。我们先将文本切分为多个块，并在每个块尾添加特殊标记<SR>，然后调整注意力掩码，将块信息融入<SR>。这样，LLMs不仅能理解单个标记的历史信息，还能通过<SR>聚合块的语义。实验证明，我们的方法在语言建模和跨领域任务中表现卓越。

> Large language models (LLMs) have shown promising efficacy across various tasks, becoming powerful tools in numerous aspects of human life. However, Transformer-based LLMs suffer a performance degradation when modeling long-term contexts due to they discard some information to reduce computational overhead. In this work, we propose a simple yet effective method to enable LLMs to take a deep breath, encouraging them to summarize information contained within discrete text chunks. Specifically, we segment the text into multiple chunks and insert special token <SR> at the end of each chunk. We then modify the attention mask to integrate the chunk's information into the corresponding <SR> token. This facilitates LLMs to interpret information not only from historical individual tokens but also from the <SR> token, aggregating the chunk's semantic information. Experiments on language modeling and out-of-domain downstream tasks validate the superiority of our approach.

![深呼吸：利用哨兵令牌提升大型语言模型的语言建模性能](../../../paper_images/2406.10985/x1.png)

![深呼吸：利用哨兵令牌提升大型语言模型的语言建模性能](../../../paper_images/2406.10985/x2.png)

[Arxiv](https://arxiv.org/abs/2406.10985)