# 数据集分解：利用可变序列长度课程加速大型语言模型训练

发布时间：2024年05月21日

`LLM理论

这篇论文主要探讨了大型语言模型（LLMs）在训练过程中的效率和性能问题，特别是针对固定长度令牌序列的训练方法的改进。论文提出了一种新的数据集分解技术，旨在优化长序列的预训练效率，并通过实验验证了其方法在提升性能方面的有效性。这一研究关注的是LLM训练过程中的理论和方法改进，因此属于LLM理论分类。` `机器学习`

> Dataset Decomposition: Faster LLM Training with Variable Sequence Length Curriculum

# 摘要

> 大型语言模型（LLMs）通常在固定长度令牌序列的数据集上训练，这些数据集通过随机连接不同长度的文档并分割成固定长度的序列来创建。但这种方法可能导致序列内跨文档的注意力，既非理想学习信号，也非计算高效。此外，长序列训练因注意力成本的二次增长而变得不切实际。本研究提出了一种创新的数据集分解技术，采用可变序列长度训练，将数据集分解为多个桶，每个桶包含来自单一文档的相同长度序列。训练时，我们采用可变序列长度和批次大小，从所有桶中按课程采样。与传统的concat-and-chunk方法相比，我们的方法在每步训练中产生的注意力成本与文档长度成正比，大幅节省了训练时间。我们以与基线方法相同的成本，训练了一个8k上下文长度的1B模型，实验表明，我们的方法在标准语言评估和长上下文基准上显著提升了性能，达到目标精度的速度是基线的三倍。此方法不仅优化了长序列的预训练效率，还随着数据集规模的增加，有效扩展了性能。最后，我们揭示了训练大型语言模型中一个关键但较少被研究的方面：序列长度的分布和课程，这对性能产生了显著影响。

> Large language models (LLMs) are commonly trained on datasets consisting of fixed-length token sequences. These datasets are created by randomly concatenating documents of various lengths and then chunking them into sequences of a predetermined target length. However, this method of concatenation can lead to cross-document attention within a sequence, which is neither a desirable learning signal nor computationally efficient. Additionally, training on long sequences becomes computationally prohibitive due to the quadratic cost of attention. In this study, we introduce dataset decomposition, a novel variable sequence length training technique, to tackle these challenges. We decompose a dataset into a union of buckets, each containing sequences of the same size extracted from a unique document. During training, we use variable sequence length and batch size, sampling simultaneously from all buckets with a curriculum. In contrast to the concat-and-chunk baseline, which incurs a fixed attention cost at every step of training, our proposed method incurs a penalty proportional to the actual document lengths at each step, resulting in significant savings in training time. We train an 8k context-length 1B model at the same cost as a 2k context-length model trained with the baseline approach. Experiments on a web-scale corpus demonstrate that our approach significantly enhances performance on standard language evaluations and long-context benchmarks, reaching target accuracy 3x faster compared to the baseline. Our method not only enables efficient pretraining on long sequences but also scales effectively with dataset size. Lastly, we shed light on a critical yet less studied aspect of training large language models: the distribution and curriculum of sequence lengths, which results in a non-negligible difference in performance.

[Arxiv](https://arxiv.org/abs/2405.13226)