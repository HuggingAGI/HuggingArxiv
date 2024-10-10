# Tri-Level Navigator：借助 LLM 的三级学习，助力时间序列 OOD 泛化

发布时间：2024年10月09日

`LLM理论` `机器学习` `时间序列分析`

> Tri-Level Navigator: LLM-Empowered Tri-Level Learning for Time Series OOD Generalization

# 摘要

> 机器学习中的分布外 (OOD) 泛化是一个新兴领域，旨在提升模型在新颖、未见且可能具有对抗性的数据环境中的适应性和韧性。本文通过预训练的大型语言模型 (LLM) 探索时间序列 OOD 泛化。我们提出了一种名为 TTSO 的三层学习框架，该框架综合考虑样本级和组级的不确定性，为 OOD 泛化问题提供了新的理论视角。此外，我们通过理论分析验证了该方法的合理性，并开发了专门的分层定位算法，确保了算法的收敛性。实验结果表明，该方法在真实数据集上的表现优异，迭代复杂度为 O($\frac{1}{ε^{2}}$)。

> Out-of-Distribution (OOD) generalization in machine learning is a burgeoning area of study. Its primary goal is to enhance the adaptability and resilience of machine learning models when faced with new, unseen, and potentially adversarial data that significantly diverges from their original training datasets. In this paper, we investigate time series OOD generalization via pre-trained Large Language Models (LLMs). We first propose a novel \textbf{T}ri-level learning framework for \textbf{T}ime \textbf{S}eries \textbf{O}OD generalization, termed TTSO, which considers both sample-level and group-level uncertainties. This formula offers a fresh theoretic perspective for formulating and analyzing OOD generalization problem. In addition, we provide a theoretical analysis to justify this method is well motivated. We then develop a stratified localization algorithm tailored for this tri-level optimization problem, theoretically demonstrating the guaranteed convergence of the proposed algorithm. Our analysis also reveals that the iteration complexity to obtain an $ε$-stationary point is bounded by O($\frac{1}{ε^{2}}$). Extensive experiments on real-world datasets have been conducted to elucidate the effectiveness of the proposed method.

[Arxiv](https://arxiv.org/abs/2410.07018)