# MESS：现代电子结构模拟探索

发布时间：2024年06月05日

`LLM应用

理由：这篇论文介绍了MESS（一个基于JAX的现代电子结构模拟软件包），它将电子结构模拟（ESS）技术与机器学习（ML）结合，以提高性能和易用性。虽然涉及ML的应用，但主要关注的是将ML技术应用于科学计算领域，特别是电子结构模拟，这与大型语言模型（LLM）的应用相关，因为它展示了如何将现代ML技术整合到传统科学计算任务中，以提高效率和性能。因此，这篇论文更适合归类为LLM应用，而不是Agent、RAG或LLM理论。` `材料科学`

> MESS: Modern Electronic Structure Simulations

# 摘要

> 电子结构模拟（ESS）技术已服务科学界数十年，为化学、生物学及材料科学等领域提供了原子级别的精确洞察。传统上，这些模拟软件采用FORTRAN和C等编译语言开发。但随着机器学习（ML）的兴起，这些领域面临新的挑战：要么用传统语言重写ML模型，要么构建复杂的接口以桥接Python中的ML模型与庞大的编译软件系统。这与现代ML框架的发展趋势相悖，后者通过Python中张量程序的硬件加速，追求易用性与高性能的平衡。我们推出的MESS，是一个基于JAX的现代电子结构模拟软件包，它将ESS带入了ML的世界。本文探讨了采用ML软件开发实践对这一关键科学任务的影响，展示了MESS在广泛硬件加速器上的显著提速，并为ESS与ML的融合铺平了道路。MESS的代码已在https://github.com/graphcore-research/mess公开。

> Electronic structure simulation (ESS) has been used for decades to provide quantitative scientific insights on an atomistic scale, enabling advances in chemistry, biology, and materials science, among other disciplines. Following standard practice in scientific computing, the software packages driving these studies have been implemented in compiled languages such as FORTRAN and C. However, the recent introduction of machine learning (ML) into these domains has meant that ML models must be coded in these languages, or that complex software bridges have to be built between ML models in Python and these large compiled software systems. This is in contrast with recent progress in modern ML frameworks which aim to optimise both ease of use and high performance by harnessing hardware acceleration of tensor programs defined in Python. We introduce MESS: a modern electronic structure simulation package implemented in JAX; porting the ESS code to the ML world. We outline the costs and benefits of following the software development practices used in ML for this important scientific workload. MESS shows significant speedups n widely available hardware accelerators and simultaneously opens a clear pathway towards combining ESS with ML. MESS is available at https://github.com/graphcore-research/mess.

![MESS：现代电子结构模拟探索](../../../paper_images/2406.03121/x1.png)

![MESS：现代电子结构模拟探索](../../../paper_images/2406.03121/x2.png)

[Arxiv](https://arxiv.org/abs/2406.03121)