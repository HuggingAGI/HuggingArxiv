# 超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘

发布时间：2024年06月12日

`RAG

理由：这篇论文主要关注的是多模态模型中的视觉理解和推理，特别是在高分辨率视图处理方面。它提出了一种新的框架和优化策略，通过混合适配器和可学习的查询嵌入来处理图像，以及通过相似性选择器来筛选关键的图像令牌。这些技术旨在优化图像处理，减少计算负担，并提高模型的性能。这些内容与RAG（Retrieval-Augmented Generation）模型的概念相符，因为RAG模型通常涉及对多模态数据的处理和优化，以提高模型的理解和生成能力。因此，这篇论文更适合归类于RAG。` `计算机视觉` `多模态学习`

> Beyond LLaVA-HD: Diving into High-Resolution Large Multimodal Models

# 摘要

> 高分辨率视图是大型多模态模型的基石，对视觉理解和推理至关重要。现有技术多采用简单的分辨率提升，通过全局和局部两个分支处理图像，局部分支的图像块虽与全局分支分辨率一致，但高分辨率意味着更多的局部图像块，这不仅增加了计算负担，还可能削弱全局上下文的重要性。本文针对这些问题，提出了一种创新框架和精细的优化策略。我们利用混合适配器从全局视角提取关键上下文信息，并针对局部图像块，引入可学习的查询嵌入以精简图像令牌，通过相似性选择器筛选出最关键的令牌。实证研究表明，“少即是多”，即精选的局部图像令牌能显著提升性能。在训练策略上，我们发现同时训练全局和局部模块并非最佳选择，因此提出交替训练方法，以平衡两者的学习。此外，我们还引入了一个对图像细节要求极高的数据集，以强化局部压缩层的训练。这一名为SliME的方法，在多个基准测试中展现了卓越性能，仅用200万训练数据即取得领先成果。

> Seeing clearly with high resolution is a foundation of Large Multimodal Models (LMMs), which has been proven to be vital for visual perception and reasoning. Existing works usually employ a straightforward resolution upscaling method, where the image consists of global and local branches, with the latter being the sliced image patches but resized to the same resolution as the former. This means that higher resolution requires more local patches, resulting in exorbitant computational expenses, and meanwhile, the dominance of local image tokens may diminish the global context. In this paper, we dive into the problems and propose a new framework as well as an elaborate optimization strategy. Specifically, we extract contextual information from the global view using a mixture of adapters, based on the observation that different adapters excel at different tasks. With regard to local patches, learnable query embeddings are introduced to reduce image tokens, the most important tokens accounting for the user question will be further selected by a similarity-based selector. Our empirical results demonstrate a `less is more' pattern, where \textit{utilizing fewer but more informative local image tokens leads to improved performance}. Besides, a significant challenge lies in the training strategy, as simultaneous end-to-end training of the global mining block and local compression block does not yield optimal results. We thus advocate for an alternating training way, ensuring balanced learning between global and local aspects. Finally, we also introduce a challenging dataset with high requirements for image detail, enhancing the training of the local compression layer. The proposed method, termed LMM with Sophisticated Tasks, Local image compression, and Mixture of global Experts (SliME), achieves leading performance across various benchmarks with only 2 million training data.

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x1.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x2.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x3.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x4.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x5.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x6.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x7.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x8.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x9.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x10.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x11.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x12.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x13.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x14.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x15.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x16.png)

![超越 LLaVA-HD：探索高分辨率大型多模态模型的奥秘](../../../paper_images/2406.08487/x17.png)

[Arxiv](https://arxiv.org/abs/2406.08487)