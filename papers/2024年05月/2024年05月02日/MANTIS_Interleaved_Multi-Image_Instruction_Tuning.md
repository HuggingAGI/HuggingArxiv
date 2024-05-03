# MANTIS：交错式多图像指令优化

发布时间：2024年05月02日

`分类：LLM应用` `计算机视觉`

> MANTIS: Interleaved Multi-Image Instruction Tuning

# 摘要

> 近年来，众多大型多模态模型（LMMs）在处理单图像视觉语言任务上展现出了卓越的能力。但它们在处理多图像视觉语言任务上的表现尚需精进。目前，多图像LMMs如OpenFlamingo、Emu、Idefics等，主要通过在海量网络中的噪声交织图像-文本数据上进行预训练来提升其多图像处理能力，这种方法既不高效也不尽如人意。本文提出了一种新方法，即通过学术级资源的指令调优来构建强大的多图像LMMs。我们精心打造了Mantis-Instruct，内含14个多图像数据集中的721K实例，旨在涵盖共指、推理、比较、时间理解等多种多图像技能。我们将Mantis-Instruct与多个单图像视觉-语言数据集结合，训练出能够处理任何交织图像-文本输入的模型Mantis。在五个多图像基准和八个单图像基准上的评估结果显示，Mantis-8B仅需36小时的16xA100-40G学术级资源，就能在所有多图像基准上达到最先进的性能，并且平均领先于现有的最佳多图像LMM Idefics2-8B 9个百分点。Mantis在保留和非保留评估基准上的表现同样出色。此外，Mantis在单图像基准上的表现也证明了其在单图像性能上与CogVLM和Emu2不相上下。这些结果特别振奋人心，因为它们表明低成本的指令调优在构建多图像LMMs方面，确实比大规模预训练更为有效。

> The recent years have witnessed a great array of large multimodal models (LMMs) to effectively solve single-image vision language tasks. However, their abilities to solve multi-image visual language tasks is yet to be improved. The existing multi-image LMMs (e.g. OpenFlamingo, Emu, Idefics, etc) mostly gain their multi-image ability through pre-training on hundreds of millions of noisy interleaved image-text data from web, which is neither efficient nor effective. In this paper, we aim at building strong multi-image LMMs via instruction tuning with academic-level resources. Therefore, we meticulously construct Mantis-Instruct containing 721K instances from 14 multi-image datasets. We design Mantis-Instruct to cover different multi-image skills like co-reference, reasoning, comparing, temporal understanding. We combine Mantis-Instruct with several single-image visual-language datasets to train our model Mantis to handle any interleaved image-text inputs. We evaluate the trained Mantis on five multi-image benchmarks and eight single-image benchmarks. Though only requiring academic-level resources (i.e. 36 hours on 16xA100-40G), Mantis-8B can achieve state-of-the-art performance on all the multi-image benchmarks and beats the existing best multi-image LMM Idefics2-8B by an average of 9 absolute points. We observe that Mantis performs equivalently well on the held-in and held-out evaluation benchmarks. We further evaluate Mantis on single-image benchmarks and demonstrate that Mantis can maintain a strong single-image performance on par with CogVLM and Emu2. Our results are particularly encouraging as it shows that low-cost instruction tuning is indeed much more effective than intensive pre-training in terms of building multi-image LMMs.

[Arxiv](https://arxiv.org/abs/2405.01483)