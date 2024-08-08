# 通过检索助力生成，提升代码注释的质量

发布时间：2024年08月07日

`RAG` `软件开发` `人工智能`

> Improving Retrieval-Augmented Code Comment Generation by Retrieving for Generation

# 摘要

> 代码注释生成旨在自动从源代码中提取高质量注释，这一领域已有多年的研究。最新研究通过结合信息检索技术和神经生成模型，提出了检索增强的注释生成（RACG）方法，并取得了显著成果。然而，以往的检索器与生成器是独立构建的，这导致检索到的示例不一定最有利于注释生成，限制了方法的性能。为此，我们提出了一种新的训练策略，使检索器能够从生成器的反馈中学习，从而检索出更有助于提升注释质量的示例。具体而言，在训练中，我们通过检索器获取前k个示例并计算其检索分数，同时利用生成器计算基于这些示例的生成损失。通过将高检索分数的示例与低生成损失的示例对齐，检索器能够学会选择最优示例。基于此策略，我们开发了名为JOINTCOM的新RACG方法，并在两个真实数据集上进行了测试。实验结果显示，JOINTCOM在多个指标上显著超越了现有最先进方法。此外，人工评估也证实了JOINTCOM生成的注释在自然性、信息量和实用性方面均优于其他方法。

> Code comment generation aims to generate high-quality comments from source code automatically and has been studied for years. Recent studies proposed to integrate information retrieval techniques with neural generation models to tackle this problem, i.e., Retrieval-Augmented Comment Generation (RACG) approaches, and achieved state-of-the-art results. However, the retrievers in previous work are built independently of their generators. This results in that the retrieved exemplars are not necessarily the most useful ones for generating comments, limiting the performance of existing approaches. To address this limitation, we propose a novel training strategy to enable the retriever to learn from the feedback of the generator and retrieve exemplars for generation. Specifically, during training, we use the retriever to retrieve the top-k exemplars and calculate their retrieval scores, and use the generator to calculate a generation loss for the sample based on each exemplar. By aligning high-score exemplars retrieved by the retriever with low-loss exemplars observed by the generator, the retriever can learn to retrieve exemplars that can best improve the quality of the generated comments. Based on this strategy, we propose a novel RACG approach named JOINTCOM and evaluate it on two real-world datasets, JCSD and PCSD. The experimental results demonstrate that our approach surpasses the state-of-the-art baselines by 7.3% to 30.0% in terms of five metrics on the two datasets. We also conduct a human evaluation to compare JOINTCOM with the best-performing baselines. The results indicate that JOINTCOM outperforms the baselines, producing comments that are more natural, informative, and useful.

[Arxiv](https://arxiv.org/abs/2408.03623)