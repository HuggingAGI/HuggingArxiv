# 关于未识别非参数模型中的 MCMC 混合及其在变换模型下生存预测的应用

发布时间：2024年11月02日

`其他` `贝叶斯预测` `生存预测`

> On MCMC mixing under unidentified nonparametric models with an application to survival predictions under transformation models

# 摘要

> 在未识别的非参数模型中，多模态后验致使马尔可夫链蒙特卡罗（MCMC）混合不佳，这成为贝叶斯预测的阻碍。本文中，我们构想了一个先验信息量阈值，其实质为后验模式的方差，由非参数先验的不确定性超参数来表达。此阈值充当链内 MCMC 方差的下限，以保障 MCMC 混合，并通过超参数调整促使先验修改以降低模式方差。我们的方法区别于现有的后处理方法，它直接在无约束空间上对混合良好的 MCMC 链进行采样，且在预测推断中继承了原始的后验预测分布。在未识别的非参数变换模型下，我们的方法在贝叶斯生存预测中获得成功，有后验方差推断理论保驾护航，还引出了两个精妙的非参数先验。全面的模拟和真实世界数据分析显示，我们的方法实现了 MCMC 混合，在生存预测上优于现有方法。

> The multi-modal posterior under unidentified nonparametric models yields poor mixing of Markov Chain Monte Carlo (MCMC), which is a stumbling block to Bayesian predictions. In this article, we conceptualize a prior informativeness threshold that is essentially the variance of posterior modes and expressed by the uncertainty hyperparameters of nonparametric priors. The threshold plays the role of a lower bound of the within-chain MCMC variance to ensure MCMC mixing, and engines prior modification through hyperparameter tuning to descend the mode variance. Our method distinguishes from existing postprocessing methods in that it directly samples well-mixed MCMC chains on the unconstrained space, and inherits the original posterior predictive distribution in predictive inference. Our method succeeds in Bayesian survival predictions under an unidentified nonparametric transformation model, guarded by the inferential theories of the posterior variance, under elicitation of two delicate nonparametric priors. Comprehensive simulations and real-world data analysis demonstrate that our method achieves MCMC mixing and outperforms existing approaches in survival predictions.

[Arxiv](https://arxiv.org/abs/2411.01382)