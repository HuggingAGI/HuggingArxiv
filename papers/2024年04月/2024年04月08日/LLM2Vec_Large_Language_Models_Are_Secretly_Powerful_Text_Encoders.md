# LLM2Vec：大型语言模型，悄然成为强大的文本编码利器

发布时间：2024年04月08日

`LLM应用` `文本嵌入`

> LLM2Vec: Large Language Models Are Secretly Powerful Text Encoders

# 摘要

> 在当今的自然语言处理领域，大型解码器主导的语言模型（LLMs）已成为最先进的技术。尽管如此，人们对于将这些模型应用于文本嵌入任务——这需要丰富的上下文化理解——的接受速度仍然较慢。本研究提出了LLM2Vec，一种简洁的无监督方法，能够将任何解码器类型的LLM转变为出色的文本编码器。LLM2Vec包含三个简易步骤：首先，实现双向注意力机制；其次，进行掩码下一个词预测；最后，采用无监督对比学习方法。我们选取了三款流行的LLM，参数量从13亿到70亿不等，并在英文单词和序列级任务上对转换后的模型进行了评估，证明了LLM2Vec的有效性。在单词级任务上，我们的表现大幅超越了仅使用编码器的模型，并在大规模文本嵌入基准测试（MTEB）中创造了无监督学习的新高度。更进一步，结合有监督对比学习后，我们的模型在MTEB上的表现达到了仅使用公开数据训练的模型中的最先进水平。我们扎实的实验成果和深入的分析证实，LLMs能够以高效的方式被转化为通用文本编码器，无需进行昂贵的调整或依赖GPT-4生成的合成数据。

> Large decoder-only language models (LLMs) are the state-of-the-art models on most of today's NLP tasks and benchmarks. Yet, the community is only slowly adopting these models for text embedding tasks, which require rich contextualized representations. In this work, we introduce LLM2Vec, a simple unsupervised approach that can transform any decoder-only LLM into a strong text encoder. LLM2Vec consists of three simple steps: 1) enabling bidirectional attention, 2) masked next token prediction, and 3) unsupervised contrastive learning. We demonstrate the effectiveness of LLM2Vec by applying it to 3 popular LLMs ranging from 1.3B to 7B parameters and evaluate the transformed models on English word- and sequence-level tasks. We outperform encoder-only models by a large margin on word-level tasks and reach a new unsupervised state-of-the-art performance on the Massive Text Embeddings Benchmark (MTEB). Moreover, when combining LLM2Vec with supervised contrastive learning, we achieve state-of-the-art performance on MTEB among models that train only on publicly available data. Our strong empirical results and extensive analysis demonstrate that LLMs can be effectively transformed into universal text encoders in a parameter-efficient manner without the need for expensive adaptation or synthetic GPT-4 generated data.

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x1.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x2.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x3.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x4.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x5.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x6.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x7.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x8.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x9.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x10.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x11.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x12.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x13.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x14.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x15.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x16.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x17.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x18.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x19.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x20.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x21.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x22.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x23.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x24.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x25.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x26.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x27.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x28.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x29.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x30.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x31.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x32.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x33.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x34.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x35.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x36.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x37.png)

![LLM2Vec：大型语言模型，悄然成为强大的文本编码利器](../../../paper_images/2404.05961/x38.png)

[Arxiv](https://arxiv.org/abs/2404.05961)