# 大型语言模型生成与归属的最近邻推测解码法

发布时间：2024年05月29日

`RAG

理由：这篇论文介绍了一种名为“最近邻推测解码（NEST）”的半参数化语言建模方法，该方法通过令牌级检索和半参数混合分布计算，能够将真实文本片段融入模型生成，并明确其来源。这种方法特别强调了在知识密集型任务中的生成质量和归属率，以及在上下文检索增强方面的表现。这与RAG（Retrieval-Augmented Generation）模型的概念相符，即通过检索增强生成过程，提高语言模型的性能和效率。因此，这篇论文应归类于RAG。` `知识检索`

> Nearest Neighbor Speculative Decoding for LLM Generation and Attribution

# 摘要

> 大型语言模型（LLMs）常产生幻觉且无法为其生成内容提供来源归属。半参数化模型如kNN-LM尝试通过在非参数数据存储中寻找最邻近匹配来优化LM对特定提示的输出，但这些模型推理速度慢且生成的文本不流畅。本文提出的最近邻推测解码（NEST）是一种创新的半参数化语言建模方法，它能将任意长度的真实文本片段融入模型生成，并明确其来源。NEST在每次推理时进行令牌级检索，计算半参数混合分布，并识别语料库中有潜力的文本片段延续。通过近似推测解码过程，NEST既可接受检索到的片段前缀，也可生成新令牌。这种方法显著提升了基础LM在多种知识密集型任务中的生成质量和归属率，超越了传统kNN-LM，并在上下文检索增强方面表现出色。此外，NEST还大幅加快了生成速度，在Llama-2-Chat 70B上应用时推理时间加速达1.8倍。

> Large language models (LLMs) often hallucinate and lack the ability to provide attribution for their generations. Semi-parametric LMs, such as kNN-LM, approach these limitations by refining the output of an LM for a given prompt using its nearest neighbor matches in a non-parametric data store. However, these models often exhibit slow inference speeds and produce non-fluent texts. In this paper, we introduce Nearest Neighbor Speculative Decoding (NEST), a novel semi-parametric language modeling approach that is capable of incorporating real-world text spans of arbitrary length into the LM generations and providing attribution to their sources. NEST performs token-level retrieval at each inference step to compute a semi-parametric mixture distribution and identify promising span continuations in a corpus. It then uses an approximate speculative decoding procedure that accepts a prefix of the retrieved span or generates a new token. NEST significantly enhances the generation quality and attribution rate of the base LM across a variety of knowledge-intensive tasks, surpassing the conventional kNN-LM method and performing competitively with in-context retrieval augmentation. In addition, NEST substantially improves the generation speed, achieving a 1.8x speedup in inference time when applied to Llama-2-Chat 70B.

![大型语言模型生成与归属的最近邻推测解码法](../../../paper_images/2405.19325/NEST.png)

![大型语言模型生成与归属的最近邻推测解码法](../../../paper_images/2405.19325/x1.png)

![大型语言模型生成与归属的最近邻推测解码法](../../../paper_images/2405.19325/x2.png)

![大型语言模型生成与归属的最近邻推测解码法](../../../paper_images/2405.19325/x3.png)

![大型语言模型生成与归属的最近邻推测解码法](../../../paper_images/2405.19325/x4.png)

![大型语言模型生成与归属的最近邻推测解码法](../../../paper_images/2405.19325/x5.png)

[Arxiv](https://arxiv.org/abs/2405.19325)