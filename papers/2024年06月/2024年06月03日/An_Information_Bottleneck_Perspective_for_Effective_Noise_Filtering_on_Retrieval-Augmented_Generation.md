# 在检索增强生成过程中，从信息瓶颈视角出发，有效过滤噪声是提升效果的关键。

发布时间：2024年06月03日

`RAG

这篇论文主要讨论了检索增强生成（RAG）模型在处理噪声数据时的挑战，并提出了一种基于信息瓶颈理论的解决方案来优化噪声过滤过程。这种方法旨在通过优化互信息来确保提取的内容与目标输出高度相关，同时最小化检索段落的信息量。因此，这篇论文的内容与RAG模型的应用和改进紧密相关，属于RAG分类。` `问答系统` `数据处理`

> An Information Bottleneck Perspective for Effective Noise Filtering on Retrieval-Augmented Generation

# 摘要

> 检索增强生成将大型语言模型的能力与广泛语料库中的相关信息相结合，但面对现实世界的噪声数据时仍显力不从心。近期，一种解决方案是通过训练过滤模块来提取相关内容，但噪声压缩效果并不理想。本文提出将信息瓶颈理论应用于检索增强生成，通过优化互信息来精炼噪声过滤过程，确保压缩内容与目标输出高度相关，同时与检索段落的信息量最小化。我们还推导了信息瓶颈理论的公式，以支持其在综合评估、数据选择和奖励构建中的应用。实验证明，该方法在多个问答数据集上显著提升了答案的准确性与简洁性，实现了2.5%的压缩率。

> Retrieval-augmented generation integrates the capabilities of large language models with relevant information retrieved from an extensive corpus, yet encounters challenges when confronted with real-world noisy data. One recent solution is to train a filter module to find relevant content but only achieve suboptimal noise compression. In this paper, we propose to introduce the information bottleneck theory into retrieval-augmented generation. Our approach involves the filtration of noise by simultaneously maximizing the mutual information between compression and ground output, while minimizing the mutual information between compression and retrieved passage. In addition, we derive the formula of information bottleneck to facilitate its application in novel comprehensive evaluations, the selection of supervised fine-tuning data, and the construction of reinforcement learning rewards. Experimental results demonstrate that our approach achieves significant improvements across various question answering datasets, not only in terms of the correctness of answer generation but also in the conciseness with $2.5\%$ compression rate.

![在检索增强生成过程中，从信息瓶颈视角出发，有效过滤噪声是提升效果的关键。](../../../paper_images/2406.01549/x1.png)

![在检索增强生成过程中，从信息瓶颈视角出发，有效过滤噪声是提升效果的关键。](../../../paper_images/2406.01549/x2.png)

[Arxiv](https://arxiv.org/abs/2406.01549)