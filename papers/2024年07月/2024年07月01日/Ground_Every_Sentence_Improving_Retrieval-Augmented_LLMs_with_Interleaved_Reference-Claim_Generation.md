# 每一句都夯实：通过交错引用与声明生成，提升检索增强型大型语言模型的性能

发布时间：2024年07月01日

`RAG` `问答系统` `知识密集型任务`

> Ground Every Sentence: Improving Retrieval-Augmented LLMs with Interleaved Reference-Claim Generation

# 摘要

> RAG 在知识密集型任务中广泛用于提升 LLM 性能。近期，ATG 通过提供引用支持模型响应，增强了生成内容可信度。传统方法多采用粗粒度归属，存在可验证性不足和核查时间成本高的问题。本文提出的 ReClaim 方法，通过细粒度引用，在长篇问答中为每个答案句子提供精确引用，实验证明其有效性。

> Retrieval-Augmented Generation (RAG) has been widely adopted to enhance Large Language Models (LLMs) in knowledge-intensive tasks. Recently, Attributed Text Generation (ATG) has attracted growing attention, which provides citations to support the model's responses in RAG, so as to enhance the credibility of LLM-generated content and facilitate verification. Prior methods mainly adopt coarse-grained attributions, linking to passage-level references or providing paragraph-level citations. However, these methods still fall short in verifiability and require certain time costs for fact checking. This paper proposes a fine-grained ATG method called ReClaim(Refer & Claim), which alternates the generation of references and answers step by step. Unlike traditional coarse-grained attribution, ReClaim allows the model to add sentence-level fine-grained citations to each answer sentence in long-form question-answering tasks. Our experiments encompass various training and inference methods and multiple LLMs, verifying the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2407.01796)