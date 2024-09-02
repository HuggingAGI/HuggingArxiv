# 采用全流水线分布式Transformer技术，我们成功训练了超长上下文语言模型。

发布时间：2024年08月29日

`LLM理论` `生物学`

> Training Ultra Long Context Language Model with Fully Pipelined Distributed Transformer

# 摘要

> 在自然语言处理和计算生物学领域，具备长上下文能力的大型语言模型（LLM）对于复杂任务至关重要，如文本生成和蛋白质序列分析。然而，直接在极长上下文上训练这些模型需要大量GPU资源和内存，成本高昂且复杂。本文提出全流水线分布式变换器（FPDT），旨在高效训练长上下文LLM，实现极端硬件效率。对于GPT和Llama模型，我们实现了在相同硬件上训练序列长度提升16倍。借助专用序列块流水线设计，我们能在4个GPU上训练200万序列长度的8B LLM，同时保持55%以上的MFU。FPDT独立于现有训练技术，已在多种LLM模型中证明其高效性。

> Large Language Models (LLMs) with long context capabilities are integral to complex tasks in natural language processing and computational biology, such as text generation and protein sequence analysis. However, training LLMs directly on extremely long contexts demands considerable GPU resources and increased memory, leading to higher costs and greater complexity. Alternative approaches that introduce long context capabilities via downstream finetuning or adaptations impose significant design limitations. In this paper, we propose Fully Pipelined Distributed Transformer (FPDT) for efficiently training long-context LLMs with extreme hardware efficiency. For GPT and Llama models, we achieve a 16x increase in sequence length that can be trained on the same hardware compared to current state-of-the-art solutions. With our dedicated sequence chunk pipeline design, we can now train 8B LLM with 2 million sequence length on only 4 GPUs, while also maintaining over 55% of MFU. Our proposed FPDT is agnostic to existing training techniques and is proven to work efficiently across different LLM models.

[Arxiv](https://arxiv.org/abs/2408.16978)