# 利用后验分布实现贝叶斯学习的可扩展性

发布时间：2024年05月31日

`LLM理论

理由：这篇论文主要关注的是贝叶斯学习在现代机器学习模型中的实现挑战，并介绍了 posteriors 这一 PyTorch 库，以及一种新的随机梯度马尔可夫链蒙特卡洛方法。这些内容更多地涉及了大型语言模型（LLM）的理论基础和方法论，而不是直接的应用或特定的Agent或RAG框架。因此，将其归类为LLM理论是合适的。` `机器学习` `数据科学`

> Scalable Bayesian Learning with posteriors

# 摘要

> 尽管贝叶斯学习在理论上颇具吸引力，但在现代机器学习模型中实现它却因需处理高维后验分布而颇具挑战。本研究中，我们推出了 posteriors 这一灵活的 PyTorch 库，它让贝叶斯学习在大规模数据和参数环境下变得触手可及且易于扩展。我们还提出了一种温和的随机梯度马尔可夫链蒙特卡洛方法，该方法在 posteriors 中实现，能平滑过渡到优化阶段，并对深度集合进行了微调，确保其对贝叶斯后验的渐近无偏性。通过一系列实验，我们展示了贝叶斯近似的实际效用，并探讨了冷后验效应以及与大型语言模型的结合应用。

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