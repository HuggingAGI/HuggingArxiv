# MILE：一款专为 In-Context Learning 系统设计的变异测试工具

发布时间：2024年09月07日

`LLM应用` `人工智能` `软件测试`

> MILE: A Mutation Testing Framework of In-Context Learning Systems

# 摘要

> ICL 在 LLM 应用中表现出色，只需少量示例即可在推理时高效学习新任务，无需调整模型参数。然而，这种能力虽神秘且引人研究，却也面临黑箱和示例选择敏感等挑战。受 ML 测试技术启发，我们设计了突变测试框架，以评估 ICL 测试数据的质量。我们提出了针对 ICL 演示的突变操作符及相应分数，并通过实验验证了框架的有效性。代码已公开，详见 https://github.com/weizeming/MILE。

> In-context Learning (ICL) has achieved notable success in the applications of large language models (LLMs). By adding only a few input-output pairs that demonstrate a new task, the LLM can efficiently learn the task during inference without modifying the model parameters. Such mysterious ability of LLMs has attracted great research interests in understanding, formatting, and improving the in-context demonstrations, while still suffering from drawbacks like black-box mechanisms and sensitivity against the selection of examples. In this work, inspired by the foundations of adopting testing techniques in machine learning (ML) systems, we propose a mutation testing framework designed to characterize the quality and effectiveness of test data for ICL systems. First, we propose several mutation operators specialized for ICL demonstrations, as well as corresponding mutation scores for ICL test sets. With comprehensive experiments, we showcase the effectiveness of our framework in evaluating the reliability and quality of ICL test suites. Our code is available at https://github.com/weizeming/MILE.

[Arxiv](https://arxiv.org/abs/2409.04831)