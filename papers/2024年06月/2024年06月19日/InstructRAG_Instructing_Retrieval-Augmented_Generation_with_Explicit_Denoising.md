# InstructRAG：利用显式去噪技术指导检索增强生成过程

发布时间：2024年06月19日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）模型中的问题，即检索器的不完善或语料库的噪声可能导致的误导或错误信息。论文提出了一种新的方法InstructRAG，通过自我合成的理由让语言模型明确学习去噪，从而提升生成准确性。这种方法特别关注于RAG框架内的改进，因此属于RAG分类。` `知识密集型任务`

> InstructRAG: Instructing Retrieval-Augmented Generation with Explicit Denoising

# 摘要

> 检索增强生成（RAG）展现出提升语言模型准确性和事实性的潜力，但检索器的不完善或语料库的噪声可能导致检索内容中出现误导或错误信息，严重影响生成质量。现有RAG方法通常直接预测答案，忽略了潜在的噪声输入，这种隐式去噪过程难以解释和验证。获取显式去噪监督则需耗费大量人力。为此，我们提出InstructRAG，通过自我合成的理由让语言模型明确学习去噪——首先，我们让模型解释如何从检索文档中得出正确答案，这些理由随后既可用于显式去噪的上下文学习，也可作为微调数据。与传统RAG相比，InstructRAG无需额外监督，便于验证预测答案，显著提升生成准确性。实验显示，InstructRAG在多个知识密集型基准上超越现有方法，平均提升8.3%。分析表明，随着检索文档增多，InstructRAG保持稳健的去噪能力，展现出强大的泛化性。

> Retrieval-augmented generation (RAG) has shown promising potential to enhance the accuracy and factuality of language models (LMs). However, imperfect retrievers or noisy corpora can introduce misleading or even erroneous information to the retrieved contents, posing a significant challenge to the generation quality. Existing RAG methods typically address this challenge by directly predicting final answers despite potentially noisy inputs, resulting in an implicit denoising process that is difficult to interpret and verify. On the other hand, the acquisition of explicit denoising supervision is often costly, involving significant human efforts. In this work, we propose InstructRAG, where LMs explicitly learn the denoising process through self-synthesized rationales -- First, we instruct the LM to explain how the ground-truth answer is derived from retrieved documents. Then, these rationales can be used either as demonstrations for in-context learning of explicit denoising or as supervised fine-tuning data to train the model. Compared to standard RAG approaches, InstructRAG requires no additional supervision, allows for easier verification of the predicted answers, and effectively improves generation accuracy. Experiments show InstructRAG consistently outperforms existing RAG methods in both training-free and trainable scenarios, achieving a relative improvement of 8.3% over the best baseline method on average across five knowledge-intensive benchmarks. Extensive analysis indicates that InstructRAG scales well with increased numbers of retrieved documents and consistently exhibits robust denoising ability even in out-of-domain datasets, demonstrating strong generalizability.

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x1.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x2.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x3.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x4.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x5.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x6.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x7.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x8.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x9.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x10.png)

![InstructRAG：利用显式去噪技术指导检索增强生成过程](../../../paper_images/2406.13629/x11.png)

[Arxiv](https://arxiv.org/abs/2406.13629)