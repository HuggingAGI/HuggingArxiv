# 功能级不确定性量化：LLM 微调的校准之道

发布时间：2024年10月08日

`LLM理论` `人工智能`

> Functional-level Uncertainty Quantification for Calibrated Fine-tuning on LLMs

# 摘要

> 从常识推理到特定领域任务，PEFT 方法显著提升了 LLM 在下游任务中的表现。然而，微调后的 LLM 在面对不确定预测时往往过度自信，尤其是在训练数据稀疏的情况下。这种过度自信源于模型在有限数据下泛化能力的不足，导致认知不确定性校准不佳。现有的 PEFT 不确定性量化方法主要在微调后进行，因此在认知不确定性校准方面效果有限。为此，我们提出了 UQ4CT，通过专家混合框架在微调阶段捕捉和校准功能级认知不确定性。实验表明，UQ4CT 在保持高准确率的同时，将 ECE 降低了 25% 以上，并在 5 个基准测试中表现优异。此外，UQ4CT 在面对数据分布偏移时，仍能保持优越的 ECE 性能和高准确率，显示出更强的泛化能力。

> From common-sense reasoning to domain-specific tasks, parameter-efficient fine tuning (PEFT) methods for large language models (LLMs) have showcased significant performance improvements on downstream tasks. However, fine-tuned LLMs often struggle with overconfidence in uncertain predictions, particularly due to sparse training data. This overconfidence reflects poor epistemic uncertainty calibration, which arises from limitations in the model's ability to generalize with limited data. Existing PEFT uncertainty quantification methods for LLMs focus on the post fine-tuning stage and thus have limited capability in calibrating epistemic uncertainty. To address these limitations, we propose Functional-Level Uncertainty Quantification for Calibrated Fine-Tuning (UQ4CT), which captures and calibrates functional-level epistemic uncertainty during the fine-tuning stage via a mixture-of-expert framework. We show that UQ4CT reduces Expected Calibration Error (ECE) by more than $25\%$ while maintaining high accuracy across $5$ benchmarks. Furthermore, UQ4CT maintains superior ECE performance with high accuracy under distribution shift, showcasing improved generalizability.

[Arxiv](https://arxiv.org/abs/2410.06431)