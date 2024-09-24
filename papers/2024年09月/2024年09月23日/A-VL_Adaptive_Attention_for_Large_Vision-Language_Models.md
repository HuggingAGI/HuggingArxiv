# A-VL：为大型视觉-语言模型量身定制的自适应注意力机制

发布时间：2024年09月23日

`LLM应用` `计算机视觉`

> A-VL: Adaptive Attention for Large Vision-Language Models

# 摘要

> 大型视觉-语言模型 (LVLM) 结合了计算机视觉和自然语言处理技术，展现出巨大的应用潜力。然而，这些模型在推理时需要大量资源。自适应注意力技术能动态减少计算冗余，提升效率。尽管现有方法显著降低了 Transformer 语言模型的内存需求，但不适用于 LVLMs。我们发现 LVLMs 从远端图像和本地文本生成响应，且不同模态的注意力模式各异。这启发我们分别管理各模态的注意力：对视觉输入，存储有用信息缓存，只计算关键部分；对语言输入，更关注本地信息。基于此，我们开发了 A-VL，一种专为 LVLM 设计的即插即用自适应注意力。在三项视觉-语言任务和五个数据集上的广泛评估表明，A-VL 在减少内存和计算负载方面优于现有方法，且不影响性能。

> The Large Vision-Language Model (LVLM) integrates computer vision and natural language processing techniques, offering substantial application potential. However, these models demand extensive resources during inference. Adaptive attention techniques can dynamically reduce computational redundancy and thus improve efficiency. Although current adaptive attention methods significantly reduce the memory requirements of Transformer-based language models, they are not tailored for LVLMs. We observe that LVLMs generate responses from both remote image tokens and local text tokens, and different modalities have different attention patterns. This observation inspires us to manage the attention for each modality separately. Specifically, for visual input, we store the cache of potentially useful information but only compute the most critical parts. For language input, we care more about local information. Based on our observation and analysis of vision-language attention patterns, we develop A-VL, a plug-and-play adaptive attention tailored for LVLM inference. Extensive evaluations on three vision-language tasks and five datasets show the effectiveness of our designs. Our approach A-VL outperforms existing adaptive attention methods in reducing memory usage and computational load without compromising performance.

[Arxiv](https://arxiv.org/abs/2409.14846)