# LLM 对话状态跟踪中的置信度评估

发布时间：2024年09月15日

`LLM应用` `人工智能` `对话系统`

> Confidence Estimation for LLM-Based Dialogue State Tracking

# 摘要

> 在基于 LLM 的对话 AI 系统中，准确估计模型输出的置信度至关重要，尤其是在减少幻觉和防止过度依赖方面。我们深入研究了多种方法，包括针对开放和封闭权重 LLM 的策略，旨在量化并利用模型不确定性，以提升 LLM 生成响应的可靠性，特别是在任务导向对话系统中的对话状态跟踪。无论模型类型如何，良好校准的置信度分数都是处理不确定性的关键，从而提升模型性能。我们评估了四种方法：基于 softmax、原始令牌分数、口头化置信度及其组合，使用 AUC 指标评估校准效果，AUC 越高表示校准越好。我们还引入了自探测机制，进一步优化了这些方法。此外，我们使用为 DST 任务微调的开放权重模型进行评估，显著提升了联合目标准确性。研究结果表明，微调开放权重 LLM 能有效提高 AUC 性能，显示出更好的置信度分数校准。

> Estimation of a model's confidence on its outputs is critical for Conversational AI systems based on large language models (LLMs), especially for reducing hallucination and preventing over-reliance. In this work, we provide an exhaustive exploration of methods, including approaches proposed for open- and closed-weight LLMs, aimed at quantifying and leveraging model uncertainty to improve the reliability of LLM-generated responses, specifically focusing on dialogue state tracking (DST) in task-oriented dialogue systems (TODS). Regardless of the model type, well-calibrated confidence scores are essential to handle uncertainties, thereby improving model performance. We evaluate four methods for estimating confidence scores based on softmax, raw token scores, verbalized confidences, and a combination of these methods, using the area under the curve (AUC) metric to assess calibration, with higher AUC indicating better calibration. We also enhance these with a self-probing mechanism, proposed for closed models. Furthermore, we assess these methods using an open-weight model fine-tuned for the task of DST, achieving superior joint goal accuracy (JGA). Our findings also suggest that fine-tuning open-weight LLMs can result in enhanced AUC performance, indicating better confidence score calibration.

[Arxiv](https://arxiv.org/abs/2409.09629)