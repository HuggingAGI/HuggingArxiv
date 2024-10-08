# TidalDecode：通过位置持久稀疏注意力，实现 LLM 的快速精准解码

发布时间：2024年10月07日

`LLM理论` `人工智能`

> TidalDecode: Fast and Accurate LLM Decoding with Position Persistent Sparse Attention

# 摘要

> 大型语言模型（LLM）在众多 NLP 任务中取得了显著进展，尤其是长上下文模型在处理复杂输入时表现突出。然而，随着 Transformer 架构中键值（KV）缓存需求的增加，内存压力在解码阶段尤为明显，成为一大瓶颈。现有稀疏注意力机制虽旨在缓解此问题，但存在两大缺陷：一是难以准确识别关键标记，二是忽视了连续层间标记选择的空间连贯性，导致性能下降和额外开销。为此，我们提出了 TidalDecode，一种简单高效的算法和系统，通过位置持久稀疏注意力实现快速准确的 LLM 解码。TidalDecode 不仅利用了现有稀疏注意力方法中标记的空间一致性，还引入了少量全注意力层来精准识别高关注度标记，其余层则采用预选标记进行稀疏注意力。这一设计不仅大幅降低了标记选择的开销，还确保了生成结果的高质量。实验表明，TidalDecode 在保持与全注意力方法相当生成性能的同时，将 LLM 解码延迟降低了高达 2.1 倍。

> Large language models (LLMs) have driven significant advancements across diverse NLP tasks, with long-context models gaining prominence for handling extended inputs. However, the expanding key-value (KV) cache size required by Transformer architectures intensifies the memory constraints, particularly during the decoding phase, creating a significant bottleneck. Existing sparse attention mechanisms designed to address this bottleneck have two limitations: (1) they often fail to reliably identify the most relevant tokens for attention, and (2) they overlook the spatial coherence of token selection across consecutive Transformer layers, which can lead to performance degradation and substantial overhead in token selection. This paper introduces TidalDecode, a simple yet effective algorithm and system for fast and accurate LLM decoding through position persistent sparse attention. TidalDecode leverages the spatial coherence of tokens selected by existing sparse attention methods and introduces a few token selection layers that perform full attention to identify the tokens with the highest attention scores, while all other layers perform sparse attention with the pre-selected tokens. This design enables TidalDecode to substantially reduce the overhead of token selection for sparse attention without sacrificing the quality of the generated results. Evaluation on a diverse set of LLMs and tasks shows that TidalDecode closely matches the generative performance of full attention methods while reducing the LLM decoding latency by up to 2.1x.

[Arxiv](https://arxiv.org/abs/2410.05076)