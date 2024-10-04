# 通过无标签的比较推理，提升上下文学习的校准与区分能力。

发布时间：2024年10月03日

`LLM理论` `机器学习` `人工智能`

> Calibrate to Discriminate: Improve In-Context Learning with Label-Free Comparative Inference

# 摘要

> 尽管 LLM 的 in-context learning 表现出色，但我们发现了一种特殊现象：正确与错误的预测竟被赋予相同置信度，我们称之为“无差别校准失调”。传统校准指标如 ECE 对此无能为力。为此，我们设计了新指标来量化这种失调的严重性，并创新了一种 in-context 比较推理方法，以改善校准并提升分类准确性。实验证明，相比传统的 zero-shot 和 few-shot 方法，我们的方案能带来更精准、更可靠的预测结果。

> While in-context learning with large language models (LLMs) has shown impressive performance, we have discovered a unique miscalibration behavior where both correct and incorrect predictions are assigned the same level of confidence. We refer to this phenomenon as indiscriminate miscalibration. We found that traditional calibration metrics, such as Expected Calibrated Errors (ECEs), are unable to capture this behavior effectively. To address this issue, we propose new metrics to measure the severity of indiscriminate miscalibration. Additionally, we develop a novel in-context comparative inference method to alleviate miscalibrations and improve classification performance. Through extensive experiments on five datasets, we demonstrate that our proposed method can achieve more accurate and calibrated predictions compared to regular zero-shot and few-shot prompting.

[Arxiv](https://arxiv.org/abs/2410.02210)