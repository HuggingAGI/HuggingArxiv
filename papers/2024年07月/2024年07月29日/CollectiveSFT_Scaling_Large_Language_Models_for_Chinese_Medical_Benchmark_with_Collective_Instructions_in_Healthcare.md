# CollectiveSFT：利用集体指令，扩展大型语言模型以适应中文医疗领域的基准测试

发布时间：2024年07月29日

`LLM应用`

> CollectiveSFT: Scaling Large Language Models for Chinese Medical Benchmark with Collective Instructions in Healthcare

# 摘要

> 随着大型语言模型的飞速发展，众多评估其能力的基准应运而生。本研究深入探讨了中文综合医学基准 (CMB)，揭示了监督微调 (SFT) 中数据集的多样性与分布对提升模型性能的关键作用。尤为引人注目的是，我们训练的较小模型竟能与大型模型媲美，这充分证明了无论模型规模如何，多样且均衡的数据集都能显著优化性能。研究进一步表明，通过精心挑选和多样化的数据集，即使是小型模型也能实现卓越性能。我们的方法通过融合多元化的教学内容，有效规避了数据质量参差不齐的问题。实验结果强调，更广泛、更丰富的训练数据能大幅提升模型在各类医学场景中的泛化与应用能力，从而凸显了数据集质量与多样性在微调过程中的核心地位。

> The rapid progress in Large Language Models (LLMs) has prompted the creation of numerous benchmarks to evaluate their capabilities.This study focuses on the Comprehensive Medical Benchmark in Chinese (CMB), showcasing how dataset diversity and distribution in supervised fine-tuning (SFT) may enhance LLM performance.Remarkably, We successfully trained a smaller base model to achieve scores comparable to larger models, indicating that a diverse and well-distributed dataset can optimize performance regardless of model size.This study suggests that even smaller models may reach high performance levels with carefully curated and varied datasets.By integrating a wide range of instructional content, our approach addresses potential issues such as data quality inconsistencies. Our results imply that a broader spectrum of training data may enhance a model's ability to generalize and perform effectively across different medical scenarios, highlighting the importance of dataset quality and diversity in fine-tuning processes.

[Arxiv](https://arxiv.org/abs/2407.19705)