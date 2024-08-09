# 通过自动推理引擎调优，迈向SLO优化的LLM服务

发布时间：2024年08月08日

`LLM应用` `云计算` `人工智能`

> Towards SLO-Optimized LLM Serving via Automatic Inference Engine Tuning

# 摘要

> 服务级别目标 (SLO) 是云供应商追求的服务性能指标。优化 SLO 不仅能提升用户满意度，还能增强云供应商的竞争力。随着大型语言模型 (LLM) 在多领域的广泛应用，优化 LLM 推理服务的 SLO 变得尤为关键。本文发现，通过调整 LLM 推理引擎的参数，可以有效提升服务性能，且不同服务的最佳参数配置各异。为此，我们设计了 SCOOT 系统，该系统通过自动调优推理引擎参数，为每个 LLM 推理服务优化 SLO。SCOOT 首先提出一个通用调优公式，以应对参数间的多重目标与约束，并运用贝叶斯优化 (BO) 技术进行探索与利用。同时，SCOOT 采用随机森林学习调优过程中的隐含约束，避免无效探索。为提升调优效率，SCOOT 还引入了并行建议机制，加速调优进程。实验证明，SCOOT 在 SLO 优化上显著超越现有技术，且大幅提升了调优效率。

> A service-level objective (SLO) is a target performance metric of service that cloud vendors aim to ensure. Delivering optimized SLOs can enhance user satisfaction and improve the competitiveness of cloud vendors. As large language models (LLMs) are gaining increasing popularity across various fields, it is of great significance to optimize SLOs for LLM inference services. In this paper, we observe that adjusting the parameters of LLM inference engines can improve service performance, and the optimal parameter configurations of different services are different. Therefore, we propose SCOOT, an automatic performance tuning system to optimize SLOs for each LLM inference service by tuning the parameters of the inference engine. We first propose a generalized formulation of the tuning problem to handle various objectives and constraints between parameters, and SCOOT exploits the Bayesian optimization (BO) technique to resolve the problem via exploration and exploitation. Moreover, SCOOT adopts a random forest to learn hidden constraints during the tuning process to mitigate invalid exploration. To improve the tuning efficiency, SCOOT utilizes the parallel suggestion to accelerate the tuning process. Extensive experiments demonstrate that SCOOT can significantly outperform existing tuning techniques in SLO optimization while greatly improving the tuning efficiency.

[Arxiv](https://arxiv.org/abs/2408.04323)