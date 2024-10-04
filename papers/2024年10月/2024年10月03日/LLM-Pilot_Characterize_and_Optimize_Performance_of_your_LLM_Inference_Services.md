# LLM-Pilot：精调与优化您的 LLM 推理服务性能

发布时间：2024年10月03日

`LLM应用` `云计算` `人工智能`

> LLM-Pilot: Characterize and Optimize Performance of your LLM Inference Services

# 摘要

> 随着 LLM 的普及，推理服务需应对数千用户并满足性能要求。LLM-Pilot 系统应运而生，它通过在多种 GPU 上进行基准测试，优化配置，学习预测模型，为新 LLM 推荐最具性价比的硬件。相较于传统方法，LLM-Pilot 不仅提高了 33% 的性能达标率，还平均降低了 60% 的成本。

> As Large Language Models (LLMs) are rapidly growing in popularity, LLM inference services must be able to serve requests from thousands of users while satisfying performance requirements. The performance of an LLM inference service is largely determined by the hardware onto which it is deployed, but understanding of which hardware will deliver on performance requirements remains challenging. In this work we present LLM-Pilot - a first-of-its-kind system for characterizing and predicting performance of LLM inference services. LLM-Pilot performs benchmarking of LLM inference services, under a realistic workload, across a variety of GPUs, and optimizes the service configuration for each considered GPU to maximize performance. Finally, using this characterization data, LLM-Pilot learns a predictive model, which can be used to recommend the most cost-effective hardware for a previously unseen LLM. Compared to existing methods, LLM-Pilot can deliver on performance requirements 33% more frequently, whilst reducing costs by 60% on average.

[Arxiv](https://arxiv.org/abs/2410.02425)