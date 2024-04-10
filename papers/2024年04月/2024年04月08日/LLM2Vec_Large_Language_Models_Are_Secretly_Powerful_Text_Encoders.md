# LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。

发布时间：2024年04月08日

`LLM应用` `文本嵌入`

> LLM2Vec: Large Language Models Are Secretly Powerful Text Encoders

# 摘要

> 目前，大型解码器主导型语言模型（LLM）在NLP领域的各种任务和评估基准中占据领先地位。尽管如此，人们对于使用这些模型进行文本嵌入——这一需要丰富上下文表示的任务——的接受速度却相当缓慢。本研究提出了LLM2Vec，这是一种简洁的无监督方法，能够将任何解码器型LLM转化为高效的文本编码器。LLM2Vec由三个简洁的步骤构成：首先，启动双向注意力机制；其次，进行掩码下一个词预测；最后，实施无监督对比学习。我们选取了三个参数量从1.3亿到7亿不等的流行LLM，通过将LLM2Vec应用于这些模型，并对它们在英文单词和序列级别的任务上的表现进行评估，证明了LLM2Vec的有效性。在单词级别的任务上，我们的表现大幅超越了仅使用编码器的模型，并在大规模文本嵌入基准测试（MTEB）中创造了无监督学习领域的新纪录。此外，结合有监督对比学习后的LLM2Vec，在MTEB上的表现更是达到了仅利用公开数据训练的模型中的最先进水平。我们通过大量实证结果和深入分析证实，LLM能够以参数高效的方式被有效转换为通用文本编码器，无需依赖昂贵的模型调整或GPT-4合成数据。

> Large decoder-only language models (LLMs) are the state-of-the-art models on most of today's NLP tasks and benchmarks. Yet, the community is only slowly adopting these models for text embedding tasks, which require rich contextualized representations. In this work, we introduce LLM2Vec, a simple unsupervised approach that can transform any decoder-only LLM into a strong text encoder. LLM2Vec consists of three simple steps: 1) enabling bidirectional attention, 2) masked next token prediction, and 3) unsupervised contrastive learning. We demonstrate the effectiveness of LLM2Vec by applying it to 3 popular LLMs ranging from 1.3B to 7B parameters and evaluate the transformed models on English word- and sequence-level tasks. We outperform encoder-only models by a large margin on word-level tasks and reach a new unsupervised state-of-the-art performance on the Massive Text Embeddings Benchmark (MTEB). Moreover, when combining LLM2Vec with supervised contrastive learning, we achieve state-of-the-art performance on MTEB among models that train only on publicly available data. Our strong empirical results and extensive analysis demonstrate that LLMs can be effectively transformed into universal text encoders in a parameter-efficient manner without the need for expensive adaptation or synthetic GPT-4 generated data.

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x1.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x2.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x3.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x4.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x5.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x6.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x7.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x8.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x9.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x10.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x11.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x12.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x13.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x14.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x15.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x16.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x17.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x18.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x19.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x20.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x21.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x22.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x23.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x24.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x25.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x26.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x27.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x28.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x29.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x30.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x31.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x32.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x33.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x34.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x35.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x36.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x37.png)

![LLM2Vec：大型语言模型，潜藏着强大的文本编码能力。](../../../paper_images/2404.05961/x38.png)

[Arxiv](https://arxiv.org/abs/2404.05961)