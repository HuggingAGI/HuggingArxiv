# 非线性同化结合基于分数的顺序朗之万采样

发布时间：2024年11月20日

`其他` `数值分析` `非线性同化`

> Nonlinear Assimilation with Score-based Sequential Langevin Sampling

# 摘要

> 本文于递归贝叶斯框架之中，推出了一种用于非线性同化的新颖方法——基于分数的顺序朗之万采样（SSLS）。SSLS把同化过程拆解为一连串的预测和更新步骤，借助动态模型来预测，通过基于分数的朗之万蒙特卡罗，利用观测数据来更新。还引入了退火策略，以增强收敛性，助力多模态采样。在特定条件下，对SSLS在TV距离中的收敛性加以分析，为与超参数有关的误差行为提供了见解。数值实例显示，其在高维和非线性情境，以及存在稀疏或部分测量的状况下，表现卓越。另外，SSLS有效量化了与估计状态相关的不确定性，凸显了其在误差校准方面的潜力。

> This paper presents a novel approach for nonlinear assimilation called score-based sequential Langevin sampling (SSLS) within a recursive Bayesian framework. SSLS decomposes the assimilation process into a sequence of prediction and update steps, utilizing dynamic models for prediction and observation data for updating via score-based Langevin Monte Carlo. An annealing strategy is incorporated to enhance convergence and facilitate multi-modal sampling. The convergence of SSLS in TV-distance is analyzed under certain conditions, providing insights into error behavior related to hyper-parameters. Numerical examples demonstrate its outstanding performance in high-dimensional and nonlinear scenarios, as well as in situations with sparse or partial measurements. Furthermore, SSLS effectively quantifies the uncertainty associated with the estimated states, highlighting its potential for error calibration.

[Arxiv](https://arxiv.org/abs/2411.13443)