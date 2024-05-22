# 稀疏自编码器为语言模型中的电路识别提供了可扩展且可靠的解决方案。

发布时间：2024年05月21日

`LLM理论

理由：这篇论文主要探讨了在大规模语言模型中如何高效发现可解释电路的方法，通过使用离散稀疏自编码器来解决计算复杂性和超参数敏感性问题。这种方法涉及对模型内部机制的深入分析和解释，特别是在注意力头的表示和计算参与方面。因此，这项工作更偏向于对LLM的理论研究，即如何理解和解释这些模型的内部工作机制，而不是直接的应用或Agent的设计。此外，虽然文中提到了在特定任务上的应用，但其核心贡献在于理论方法的创新和解释性的提升，这进一步支持了其归类为LLM理论。` `机器学习`

> Sparse Autoencoders Enable Scalable and Reliable Circuit Identification in Language Models

# 摘要

> 本文提出了一种利用离散稀疏自编码器在大规模语言模型中高效发现可解释电路的方法。该方法克服了现有技术的两大难题：计算复杂性和超参数敏感性。我们通过在精心挑选的正负样本上训练模型，确保模型仅能准确预测正样本的下一个词，从而优化了训练过程。我们推测，注意力头输出的学习表示能够揭示何时该头参与特定计算。通过将这些表示转换为整数码，并分析每个头中正样本特有的代码重叠，我们能够直接识别出参与电路的注意力头，无需进行耗时的消融实验或架构调整。在间接对象识别、大于比较和文档字符串完成这三个任务上，我们的方法不仅在恢复真实电路的精确度和召回率上超越了现有技术，还将运行时间从数小时缩短至几秒。尤为重要的是，每个任务我们仅需5-10个文本示例即可获得稳健的模型表示。这一发现为大规模语言模型的机制解释性研究开辟了新路径，展示了离散稀疏自编码器的巨大潜力。

> This paper introduces an efficient and robust method for discovering interpretable circuits in large language models using discrete sparse autoencoders. Our approach addresses key limitations of existing techniques, namely computational complexity and sensitivity to hyperparameters. We propose training sparse autoencoders on carefully designed positive and negative examples, where the model can only correctly predict the next token for the positive examples. We hypothesise that learned representations of attention head outputs will signal when a head is engaged in specific computations. By discretising the learned representations into integer codes and measuring the overlap between codes unique to positive examples for each head, we enable direct identification of attention heads involved in circuits without the need for expensive ablations or architectural modifications. On three well-studied tasks - indirect object identification, greater-than comparisons, and docstring completion - the proposed method achieves higher precision and recall in recovering ground-truth circuits compared to state-of-the-art baselines, while reducing runtime from hours to seconds. Notably, we require only 5-10 text examples for each task to learn robust representations. Our findings highlight the promise of discrete sparse autoencoders for scalable and efficient mechanistic interpretability, offering a new direction for analysing the inner workings of large language models.

[Arxiv](https://arxiv.org/abs/2405.12522)