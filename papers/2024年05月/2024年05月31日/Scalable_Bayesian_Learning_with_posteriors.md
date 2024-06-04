# 利用后验进行规模化的贝叶斯学习

发布时间：2024年05月31日

`LLM理论

理由：这篇论文主要关注贝叶斯学习在现代机器学习模型中的应用，特别是在处理高维后验分布时的计算挑战。论文中提到的 posteriors 库、随机梯度马尔可夫链蒙特卡洛的温度调整方法以及对深度集合的微调，都是为了更好地理解和应用贝叶斯学习在大型语言模型中的理论。因此，这篇论文更偏向于理论研究，探讨了贝叶斯近似的价值，包括冷后验效应的研究以及与大型语言模型的结合应用，属于LLM理论分类。` `机器学习` `大数据分析`

> Scalable Bayesian Learning with posteriors

# 摘要

> 尽管贝叶斯学习在理论上令人信服，但其在现代机器学习模型中的应用却因需近似高维后验分布而面临计算挑战。本研究中，我们推出了 posteriors，一个灵活的 PyTorch 库，它让贝叶斯学习在大数据和参数规模下变得触手可及且高效。我们还提出了随机梯度马尔可夫链蒙特卡洛的温度调整方法，该方法能平滑过渡至优化阶段，并对深度集合进行了微调，确保其对贝叶斯后验的渐近无偏性。通过一系列实验，我们探讨了贝叶斯近似的价值，包括对冷后验效应的研究以及与大型语言模型的结合应用。

> Although theoretically compelling, Bayesian learning with modern machine learning models is computationally challenging since it requires approximating a high dimensional posterior distribution. In this work, we (i) introduce posteriors, an easily extensible PyTorch library hosting general-purpose implementations making Bayesian learning accessible and scalable to large data and parameter regimes; (ii) present a tempered framing of stochastic gradient Markov chain Monte Carlo, as implemented in posteriors, that transitions seamlessly into optimization and unveils a minor modification to deep ensembles to ensure they are asymptotically unbiased for the Bayesian posterior, and (iii) demonstrate and compare the utility of Bayesian approximations through experiments including an investigation into the cold posterior effect and applications with large language models.

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/double_well_schematic.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/posteriors_snippet.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/laplace_loss.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/vi_loss.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/sghmc_loss.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/plot_A.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/plot_B.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/uncertainties.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/laplace_loss_with_mle.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/vi_loss_with_mle.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/sghmc_loss_with_mle.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/laplace_accuracy_with_mle.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/vi_accuracy_with_mle.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/sghmc_accuracy_with_mle.png)

![利用后验进行规模化的贝叶斯学习](../../../paper_images/2406.00104/uncertainties_appendix.png)

[Arxiv](https://arxiv.org/abs/2406.00104)