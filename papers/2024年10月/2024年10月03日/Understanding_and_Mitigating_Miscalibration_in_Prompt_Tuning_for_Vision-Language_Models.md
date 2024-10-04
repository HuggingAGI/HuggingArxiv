# 探索并缓解视觉-语言模型提示调优中的校准偏差

发布时间：2024年10月03日

`LLM应用` `机器学习` `计算机视觉`

> Understanding and Mitigating Miscalibration in Prompt Tuning for Vision-Language Models

# 摘要

> 置信度校准对机器学习模型在现实世界中的安全部署至关重要。然而，像 CLIP 这样的视觉-语言模型在微调后，这一问题仍未完全解决。我们发现，现有提示调优方法常导致基础类和新类间的校准权衡：CoOp 通过增加文本标签分歧使新类过度自信，而 KgCoOp 虽保持置信度，却因提高准确性导致基础类置信度不足。受此启发，我们提出动态离群正则化（DOR），确保微调后基础类和新类的置信度校准。具体来说，我们最小化从大词汇表中采样的新文本标签的特征偏差，从而防止新标签的文本分歧增加，同时减轻对基础类的限制。实验证明，DOR 能显著提升当前微调方法在基础类和新类上的校准性能。

> Confidence calibration is critical for the safe deployment of machine learning models in the real world. However, such issue in vision-language models like CLIP, particularly after fine-tuning, has not been fully addressed. In this work, we demonstrate that existing prompt tuning methods usually lead to a trade-off of calibration between base and new classes: the cross-entropy loss in CoOp causes overconfidence in new classes by increasing textual label divergence, whereas the regularization of KgCoOp maintains the confidence level but results in underconfidence in base classes due to the improved accuracy. Inspired by the observations, we introduce Dynamic Outlier Regularization (DOR) to ensure the confidence calibration on both base and new classes after fine-tuning. In particular, we propose to minimize the feature deviation of novel textual labels (instead of base classes) sampled from a large vocabulary. In effect, DOR prevents the increase in textual divergence for new labels while easing restrictions on base classes. Extensive experiments demonstrate that DOR can enhance the calibration performance of current fine-tuning methods on base and new classes.

[Arxiv](https://arxiv.org/abs/2410.02681)