# Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整

发布时间：2024年07月17日

`LLM应用` `信息检索` `人工智能`

> Matryoshka-Adaptor: Unsupervised and Supervised Tuning for Smaller Embedding Dimensions

# 摘要

> 大型语言模型中的嵌入技术，在信息检索等应用中扮演着关键角色。尽管高维嵌入因其丰富的信息含量而性能卓越，但其高昂的计算成本和延迟却限制了实际应用。为此，我们创新性地提出了 Matryoshka-Adaptor 框架，专门用于优化 LLM 嵌入。该框架在大幅降低维度的同时，仍保持了相当的性能，显著提升了计算效率和成本效益。Matryoshka-Adaptor 能够直接调整预训练 LLM 的嵌入，并兼容各种 LLM 架构，包括那些仅能通过黑盒 API 访问的模型。无论是在无监督还是监督学习场景中，它都表现出色。在广泛的英语、多语言及多模态数据集上的严格测试表明，Matryoshka-Adaptor 带来了显著的性能提升。尤其在使用 Google 和 OpenAI 的嵌入 API 时，它实现了两到十二倍的维度缩减，且不影响多个 BEIR 数据集的性能。

> Embeddings from Large Language Models (LLMs) have emerged as critical components in various applications, particularly for information retrieval. While high-dimensional embeddings generally demonstrate superior performance as they contain more salient information, their practical application is frequently hindered by elevated computational latency and the associated higher cost. To address these challenges, we propose Matryoshka-Adaptor, a novel tuning framework designed for the customization of LLM embeddings. Matryoshka-Adaptor facilitates substantial dimensionality reduction while maintaining comparable performance levels, thereby achieving a significant enhancement in computational efficiency and cost-effectiveness. Our framework directly modifies the embeddings from pre-trained LLMs which is designed to be seamlessly integrated with any LLM architecture, encompassing those accessible exclusively through black-box APIs. Also, it exhibits efficacy in both unsupervised and supervised learning settings. A rigorous evaluation conducted across a diverse corpus of English, multilingual, and multimodal datasets consistently reveals substantial gains with Matryoshka-Adaptor. Notably, with Google and OpenAI Embedding APIs, Matryoshka-Adaptor achieves a reduction in dimensionality ranging from two- to twelve-fold without compromising performance across multiple BEIR datasets.

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x1.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x2.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x3.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x4.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x5.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x6.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x7.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x8.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x9.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x10.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x11.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x12.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x13.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x14.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x15.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x16.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x17.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x18.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x19.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x20.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x21.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x22.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x23.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x24.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x25.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x26.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x27.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x28.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x29.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x30.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x31.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x32.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x33.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x34.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x35.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x36.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x37.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x38.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x39.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x40.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x41.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x42.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x43.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x44.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x45.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x46.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x47.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x48.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x49.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x50.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x51.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x52.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x53.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x54.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x55.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x56.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x57.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x58.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x59.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x60.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x61.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x62.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x63.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x64.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x65.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x66.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x67.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x68.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x69.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x70.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x71.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x72.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x73.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x74.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x75.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x76.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x77.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x78.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x79.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x80.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x81.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x82.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x83.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x84.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x85.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x86.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x87.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x88.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x89.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x90.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x91.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x92.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x93.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x94.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x95.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x96.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x97.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x98.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x99.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x100.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x101.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x102.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x103.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x104.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x105.png)

![Matryoshka-Adaptor：实现无监督与有监督的小维度嵌入调整](../../../paper_images/2407.20243/x106.png)

[Arxiv](https://arxiv.org/abs/2407.20243)