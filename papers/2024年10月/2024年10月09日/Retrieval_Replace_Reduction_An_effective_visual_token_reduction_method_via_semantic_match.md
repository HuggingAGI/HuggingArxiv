# 检索替换减少：一种通过语义匹配实现视觉标记高效减少的方法

发布时间：2024年10月09日

`LLM应用` `人工智能` `计算机视觉`

> Retrieval Replace Reduction: An effective visual token reduction method via semantic match

# 摘要

> 多模态大型语言模型 (MLLM) 虽在多种任务中表现出色，但处理超长多模态输入时面临计算和内存瓶颈，限制了其扩展性。本文提出 \textbf{TRSM} (\textbf{T}oken \textbf{R}eduction via \textbf{S}emantic \textbf{M}atch) 方法，通过语义匹配减少视觉标记，同时保持 MLLM 性能。受人类处理多模态任务的启发，TRSM 利用一种模态的语义信息匹配另一种模态的相关语义，从而减少视觉标记。具体而言，我们用文本提示作为查询向量，从视觉提示中检索最相似向量并合并到文本标记中。实验显示，应用于 LLaVA-1.5 时，TRSM 将视觉标记压缩 20\%，在多样视觉问答和推理任务中表现相当。

> Multimodal large language models (MLLMs) have demonstrated strong performance across various tasks without requiring training from scratch. However, they face significant computational and memory constraints, particularly when processing multimodal inputs that exceed context length, limiting their scalability. In this paper, we introduce a new approach, \textbf{TRSM} (\textbf{T}oken \textbf{R}eduction via \textbf{S}emantic \textbf{M}atch), which effectively reduces the number of visual tokens without compromising MLLM performance. Inspired by how humans process multimodal tasks, TRSM leverages semantic information from one modality to match relevant semantics in another, reducing the number of visual tokens.Specifically, to retain task relevant visual tokens, we use the text prompt as a query vector to retrieve the most similar vectors from the visual prompt and merge them with the text tokens. Based on experimental results, when applied to LLaVA-1.5\cite{liu2023}, our approach compresses the visual tokens by 20\%, achieving comparable performance across diverse visual question-answering and reasoning tasks.

[Arxiv](https://arxiv.org/abs/2410.07278)