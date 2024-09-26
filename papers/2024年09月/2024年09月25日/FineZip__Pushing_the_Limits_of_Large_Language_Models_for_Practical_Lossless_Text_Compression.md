# FineZip：突破大型语言模型在无损文本压缩中的应用极限

发布时间：2024年09月25日

`LLM应用` `信息技术` `数据压缩`

> FineZip : Pushing the Limits of Large Language Models for Practical Lossless Text Compression

# 摘要

> 尽管语言建模与压缩紧密相连，但现代LLMs却未被用于实际文本压缩。本文深入探讨了神经网络和Transformer的压缩技术，对比了传统与LLM压缩方法。虽然LLM压缩效果显著，但效率极低。例如，LLMZip需9.5天压缩10 MB文本。为此，我们推出FineZip，结合在线记忆与动态上下文，将压缩时间缩短至4小时，提升54倍，性能媲美。FineZip还大幅提升了压缩比率，超越传统方法50%。我们首次尝试让LLM实现无损文本压缩，尽管FineZip有所突破，但LLMs仍不适用于大规模压缩。我们期待这项研究能激发未来解决此问题的创新。

> While the language modeling objective has been shown to be deeply connected with compression, it is surprising that modern LLMs are not employed in practical text compression systems. In this paper, we provide an in-depth analysis of neural network and transformer-based compression techniques to answer this question. We compare traditional text compression systems with neural network and LLM-based text compression methods. Although LLM-based systems significantly outperform conventional compression methods, they are highly impractical. Specifically, LLMZip, a recent text compression system using Llama3-8B requires 9.5 days to compress just 10 MB of text, although with huge improvements in compression ratios. To overcome this, we present FineZip - a novel LLM-based text compression system that combines ideas of online memorization and dynamic context to reduce the compression time immensely. FineZip can compress the above corpus in approximately 4 hours compared to 9.5 days, a 54 times improvement over LLMZip and comparable performance. FineZip outperforms traditional algorithmic compression methods with a large margin, improving compression ratios by approximately 50\%. With this work, we take the first step towards making lossless text compression with LLMs a reality. While FineZip presents a significant step in that direction, LLMs are still not a viable solution for large-scale text compression. We hope our work paves the way for future research and innovation to solve this problem.

[Arxiv](https://arxiv.org/abs/2409.17141)