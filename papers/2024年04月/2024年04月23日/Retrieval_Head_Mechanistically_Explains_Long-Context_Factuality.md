# 检索头技术深入阐释了长篇文本上下文的真实性

发布时间：2024年04月23日

`LLM理论` `信息检索`

> Retrieval Head Mechanistically Explains Long-Context Factuality

# 摘要

> 尽管长文本语言模型近期取得了进步，但变换器模型如何从长文本中任意位置提取相关信息仍是一个谜。本文致力于解答这一难题。我们对多种模型进行了深入研究，发现一种特殊的注意力机制——我们称之为“检索头”，在信息检索中扮演了关键角色。这些检索头具有以下特点：(1) 普遍性：所有具备长文本处理能力的模型都配备了检索头；(2) 稀缺性：在所有注意力头中，只有不到5%是检索头；(3) 固有性：即使在短文本预训练的模型中，检索头已经存在，且随着上下文长度的增加，这些头依然负责信息检索；(4) 动态性：以 Llama-2 7B 为例，无论上下文如何变化，总有12个检索头专注于所需信息，而其他检索头则根据不同上下文激活；(5) 因果关联：完全移除检索头会导致信息检索失败和产生幻觉，而随机移除非检索头则不会影响模型的检索功能。此外，我们发现检索头对“思维链”（CoT）推理有显著影响，这种推理需要模型频繁回顾问题和已生成的上下文。而对于那些模型直接利用内在知识生成答案的任务，检索头的影响则较小。这些发现揭示了模型内部哪个部分负责从输入标记中提取信息。我们期望这些见解能够推动未来在减少幻觉、提升推理能力和优化KV缓存方面的研究。

> Despite the recent progress in long-context language models, it remains elusive how transformer-based models exhibit the capability to retrieve relevant information from arbitrary locations within the long context. This paper aims to address this question. Our systematic investigation across a wide spectrum of models reveals that a special type of attention heads are largely responsible for retrieving information, which we dub retrieval heads. We identify intriguing properties of retrieval heads:(1) universal: all the explored models with long-context capability have a set of retrieval heads; (2) sparse: only a small portion (less than 5\%) of the attention heads are retrieval. (3) intrinsic: retrieval heads already exist in models pretrained with short context. When extending the context length by continual pretraining, it is still the same set of heads that perform information retrieval. (4) dynamically activated: take Llama-2 7B for example, 12 retrieval heads always attend to the required information no matter how the context is changed. The rest of the retrieval heads are activated in different contexts. (5) causal: completely pruning retrieval heads leads to failure in retrieving relevant information and results in hallucination, while pruning random non-retrieval heads does not affect the model's retrieval ability. We further show that retrieval heads strongly influence chain-of-thought (CoT) reasoning, where the model needs to frequently refer back the question and previously-generated context. Conversely, tasks where the model directly generates the answer using its intrinsic knowledge are less impacted by masking out retrieval heads. These observations collectively explain which internal part of the model seeks information from the input tokens. We believe our insights will foster future research on reducing hallucination, improving reasoning, and compressing the KV cache.

[Arxiv](https://arxiv.org/abs/2404.15574)