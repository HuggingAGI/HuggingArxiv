# 利用后验分布实现贝叶斯学习的可扩展性

发布时间：2024年05月31日

`LLM理论

理由：这篇论文主要关注贝叶斯学习在现代机器学习模型中的实现挑战，并提出了一个PyTorch库（posteriors）来解决这些问题。虽然论文中提到了与大型语言模型的应用，但其核心贡献在于理论和方法论的改进，特别是在贝叶斯学习的近似方法上。因此，这篇论文更适合归类于LLM理论，因为它探讨了机器学习理论中的一个具体问题，并提供了理论上的解决方案。` `机器学习` `数据科学`

> Scalable Bayesian Learning with posteriors

# 摘要

> 尽管贝叶斯学习在理论上颇具吸引力，但在现代机器学习模型中实现它却因需近似高维后验分布而颇具挑战。本研究中，我们推出了 posteriors 这一 PyTorch 库，它不仅易于扩展，还提供了通用实现，让贝叶斯学习在大数据和参数规模下变得触手可及且高效。此外，我们提出了一种随机梯度马尔可夫链蒙特卡洛的温度调整方法，该方法在 posteriors 中实现，能平滑过渡至优化阶段，并对深度集合进行了微调，确保其对贝叶斯后验的渐近无偏性。通过一系列实验，我们验证并比较了贝叶斯近似的实用性，涵盖了对冷后验效应的探究及与大型语言模型的应用。

> Although theoretically compelling, Bayesian learning with modern machine learning models is computationally challenging since it requires approximating a high dimensional posterior distribution. In this work, we (i) introduce posteriors, an easily extensible PyTorch library hosting general-purpose implementations making Bayesian learning accessible and scalable to large data and parameter regimes; (ii) present a tempered framing of stochastic gradient Markov chain Monte Carlo, as implemented in posteriors, that transitions seamlessly into optimization and unveils a minor modification to deep ensembles to ensure they are asymptotically unbiased for the Bayesian posterior, and (iii) demonstrate and compare the utility of Bayesian approximations through experiments including an investigation into the cold posterior effect and applications with large language models.

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/double_well_schematic.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/posteriors_snippet.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/laplace_loss.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/vi_loss.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/sghmc_loss.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/plot_A.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/plot_B.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/uncertainties.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/laplace_loss_with_mle.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/vi_loss_with_mle.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/sghmc_loss_with_mle.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/laplace_accuracy_with_mle.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/vi_accuracy_with_mle.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/sghmc_accuracy_with_mle.png)

![利用后验分布实现贝叶斯学习的可扩展性](../../../paper_images/2406.00104/uncertainties_appendix.png)

[Arxiv](https://arxiv.org/abs/2406.00104)