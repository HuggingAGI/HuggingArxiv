# 差异隐私主动学习：在有效数据选择与隐私保护之间找到平衡

发布时间：2024年10月01日

`LLM理论` `机器学习` `数据隐私`

> Differentially Private Active Learning: Balancing Effective Data Selection and Privacy

# 摘要

> 主动学习 (AL) 通过迭代选择、标注和训练最有信息量的数据，广泛用于优化机器学习中的数据标注。然而，AL 与差分隐私 (DP) 的结合在标准学习设置中仍未得到充分探索。本研究引入差分隐私主动学习 (DP-AL)，解决了这一空白。我们发现，简单地将 DP-SGD 训练整合到 AL 中会面临隐私预算分配和数据利用的挑战。为此，我们提出步骤放大，通过优化数据点在训练中的参与度来提高数据利用效率。此外，我们研究了在隐私约束下不同获取函数的效果，发现许多常用函数变得不切实际。实验表明，DP-AL 能提升特定数据集和模型架构的性能，但也揭示了 AL 在隐私约束环境中的局限性，强调了隐私、模型准确性和数据选择准确性之间的权衡。

> Active learning (AL) is a widely used technique for optimizing data labeling in machine learning by iteratively selecting, labeling, and training on the most informative data. However, its integration with formal privacy-preserving methods, particularly differential privacy (DP), remains largely underexplored. While some works have explored differentially private AL for specialized scenarios like online learning, the fundamental challenge of combining AL with DP in standard learning settings has remained unaddressed, severely limiting AL's applicability in privacy-sensitive domains. This work addresses this gap by introducing differentially private active learning (DP-AL) for standard learning settings. We demonstrate that naively integrating DP-SGD training into AL presents substantial challenges in privacy budget allocation and data utilization. To overcome these challenges, we propose step amplification, which leverages individual sampling probabilities in batch creation to maximize data point participation in training steps, thus optimizing data utilization. Additionally, we investigate the effectiveness of various acquisition functions for data selection under privacy constraints, revealing that many commonly used functions become impractical. Our experiments on vision and natural language processing tasks show that DP-AL can improve performance for specific datasets and model architectures. However, our findings also highlight the limitations of AL in privacy-constrained environments, emphasizing the trade-offs between privacy, model accuracy, and data selection accuracy.

[Arxiv](https://arxiv.org/abs/2410.00542)