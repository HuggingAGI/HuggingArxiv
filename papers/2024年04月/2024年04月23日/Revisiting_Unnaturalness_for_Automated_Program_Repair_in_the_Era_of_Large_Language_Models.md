# 在大型语言模型盛行的当下，我们有必要重新探讨自动化程序修复领域中的“不自然性”问题。

发布时间：2024年04月23日

`LLM应用` `软件工程` `自动化程序修复`

> Revisiting Unnaturalness for Automated Program Repair in the Era of Large Language Models

# 摘要

> 随着基于 Transformer 的大型语言模型（LLMs）的兴起，语言模型的性能实现了质的飞跃。这些模型不仅能生成与专业编码者相媲美的自然代码，还能计算代码令牌的自然度——即熵。我们推测，熵的计算可能对提升自动化程序修复（APR）的性能大有裨益。尽管 APR 领域已取得显著进展，但现有的故障定位技术因评分多样性不足而受限，补丁生成工具在效率上亦有待提高，因为它们需要在所有测试运行完毕后才能评估补丁的正确性，且补丁排名常常受到测试集过拟合的影响。此外，直接将 LLM 应用于 APR 还可能引发训练数据泄露的风险。在本研究中，我们提出了一种创新方法，将 LLMs 的熵值与现有的 APR 工具相结合，全面提升 APR 的各个环节。我们的实验结果表明，熵值与现有的故障定位工具相得益彰，我们提出的重新排名方法在 Top-5 的评分上实现了对 SBFL 50%的提升。我们还引入了一种新的补丁自然度度量标准——熵差值，它通过在测试前对可能的补丁进行排序，提高了基于模板的修复技术的效率。采用熵差值进行补丁排名和分类时，我们的方法在 Top-1 的准确率上比现有最先进的机器学习工具提升了 49%。这项研究表明，LLMs 能够有效地辅助传统的 APR 任务，同时最大限度地减少了测试集过拟合和 LLM 数据泄露的问题。

> Language models have improved by orders of magnitude with the recent emergence of Transformer-based Large Language Models (LLMs). LLMs have demonstrated their ability to generate natural code that is highly similar to code written by professional developers. One intermediate value an LLM can emit is entropy, which measures the naturalness of a token of code. We hypothesize that entropy can be used to improve the performance of Automated Program Repair (APR) tasks. While much progress has been made in Automated Program Repair (APR), fault localization techniques suffer from a lack of diversity in ranking scores, patch generation tools tend to be inefficient as all tests need to run before determining if a patch is likely to be correct, and patch ranking often suffers from the test-suite over-fitting problem. However, using an LLM directly for APR introduces concerns for training data leakage. In this work, we introduce a novel way of using the entropy of LLMs in combination with prior APR tools to improve all stages of APR. We show that entropy is highly complementary with prior fault localization tools. Our proposed re-ranking method achieves a 50% Top-5 score improvement over SBFL. We propose a patch-naturalness measurement, entropy-delta, to improve the efficiency of template-based repair techniques by ranking plausible patches before undergoing testing. When using entropy-delta for patch ranking and classification, our proposed method can rank correct patches more effectively than state-of-the-art machine learning tools with an 49% improvement in Top-1. Our work suggests that LLMs can be an effective addition to compliment prior APR tasks while minimizing both the test-suite overfitting problem and the LLM data leakage problem.

[Arxiv](https://arxiv.org/abs/2404.15236)