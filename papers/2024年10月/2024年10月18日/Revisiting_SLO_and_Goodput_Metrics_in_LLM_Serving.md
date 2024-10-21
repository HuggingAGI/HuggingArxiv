# 重探 LLM 服务中的 SLO 与 Goodput 指标

发布时间：2024年10月18日

`LLM应用` `互联网服务` `用户体验`

> Revisiting SLO and Goodput Metrics in LLM Serving

# 摘要

> 大型语言模型 (LLM) 在各种应用中表现出色，但其推理服务引发了用户体验和服务吞吐量的担忧。为此，我们引入了服务水平目标 (SLO) 和 goodput 来评估 LLM 服务的性能。然而，现有指标未能全面反映用户体验。我们发现两个荒谬现象：1) 延迟令牌交付能平滑请求中的尾部时间；2) 中途丢弃未达标的请求能提高 goodput。本文重新审视了 LLM 服务中的 SLO 和 goodput 指标，提出了一个统一的 smooth goodput 框架，以更准确地反映用户体验。该框架灵活适应不同任务，我们基于此框架重新评估了多个 LLM 服务系统，并指出了未来优化的方向。我们希望这个框架能为 LLM 服务评估提供统一标准，推动相关研究朝着一致方向发展。

> Large language models (LLMs) have achieved remarkable performance and are widely deployed in various applications, while the serving of LLM inference has raised concerns about user experience and serving throughput. Accordingly, service level objectives (SLOs) and goodput-the number of requests that meet SLOs per second-are introduced to evaluate the performance of LLM serving. However, existing metrics fail to capture the nature of user experience. We observe two ridiculous phenomena in existing metrics: 1) delaying token delivery can smooth the tail time between tokens (tail TBT) of a request and 2) dropping the request that fails to meet the SLOs midway can improve goodput.
  In this paper, we revisit SLO and goodput metrics in LLM serving and propose a unified metric framework smooth goodput including SLOs and goodput to reflect the nature of user experience in LLM serving. The framework can adapt to specific goals of different tasks by setting parameters. We re-evaluate the performance of different LLM serving systems under multiple workloads based on this unified framework and provide possible directions for future optimization of existing strategies. We hope that this framework can provide a unified standard for evaluating LLM serving and foster researches in the field of LLM serving optimization to move in a cohesive direction.

[Arxiv](https://arxiv.org/abs/2410.14257)