# 掌握上下文压缩技巧，提升基于知识的视觉问答效率

发布时间：2024年09月11日

`LLM应用` `人工智能` `视觉问答`

> Learning to Compress Contexts for Efficient Knowledge-based Visual Question Answering

# 摘要

> 多模态大型语言模型（MLLM）在视觉问答（VQA）中表现出色，但在基于知识的VQA（KB-VQA）中，由于缺乏人类常识和专业知识，需要依赖外部信息。尽管如RAVQA-v2等研究尝试通过利用更多输入信息来提升性能，但忽略了输入量增加导致的推理效率下降问题。为此，我们提出RACC，通过压缩和聚合检索到的上下文，生成紧凑的KV缓存，以高效适应下游MLLM，实现高效推理。RACC在OK-VQA上达到62.9%的SOTA性能，并显著减少推理延迟。实验证明，RACC不仅兼容多种MLLM，还能处理多样的知识源。

> Multimodal Large Language Models (MLLMs) have demonstrated great zero-shot performance on visual question answering (VQA). However, when it comes to knowledge-based VQA (KB-VQA), MLLMs may lack human commonsense or specialized domain knowledge to answer such questions and require obtaining necessary information from external knowledge sources. Previous works like Retrival-Augmented VQA-v2 (RAVQA-v2) focus on utilizing as much input information, such as image-based textual descriptions and retrieved knowledge, as possible to improve performance, but they all overlook the issue that with the number of input tokens increasing, inference efficiency significantly decreases, which contradicts the demands of practical applications. To address this issue, we propose Retrieval-Augmented MLLM with Compressed Contexts (RACC). RACC learns to compress and aggregate retrieved contexts, from which it generates a compact modulation in the form of Key-Value (KV) cache. This modulation is then used to adapt the downstream frozen MLLM, thereby achieving effective and efficient inference. RACC achieves a state-of-the-art (SOTA) performance of 62.9% on OK-VQA. Moreover, it significantly reduces inference latency by 22.0%-59.7% compared to the prominent RAVQA-v2. Abundant experiments show RACC's broad applicability. It is compatible with various off-the-shelf MLLMs and can also handle different knowledge sources including textual and multimodal documents.

[Arxiv](https://arxiv.org/abs/2409.07331)