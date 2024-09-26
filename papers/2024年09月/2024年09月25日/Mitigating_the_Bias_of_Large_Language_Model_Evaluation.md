# 缓解大型语言模型评估中的偏见

发布时间：2024年09月25日

`LLM理论` `人工智能`

> Mitigating the Bias of Large Language Model Evaluation

# 摘要

> 近期，评估大型语言模型（LLM）质量的趋势是采用“LLM 作为评判者”的方式，即利用另一个 LLM 来评判当前输出的质量。然而，现有评判者存在偏见，更青睐表面质量高的答案（如冗长、流畅），却忽视了指令遵循能力。为此，我们系统研究了 LLM 评判者的偏见问题。对于闭源评判模型，我们通过校准减轻表面质量的影响；对于开源评判模型，我们采用对比训练，利用精心挑选的负样本来纠正偏见。实验表明，我们的方法在保持高评估准确性的同时，显著减少了偏见。

> Recently, there has been a trend of evaluating the Large Language Model (LLM) quality in the flavor of LLM-as-a-Judge, namely leveraging another LLM to evaluate the current output quality. However, existing judges are proven to be biased, namely they would favor answers which present better superficial quality (such as verbosity, fluency) while ignoring the instruction following ability. In this work, we propose systematic research about the bias of LLM-as-a-Judge. Specifically, for closed-source judge models, we apply calibration to mitigate the significance of superficial quality, both on probability level and prompt level. For open-source judge models, we propose to mitigate the bias by contrastive training, with curated negative samples that deviate from instruction but present better superficial quality. We apply our methods on the bias evaluation benchmark, and experiment results show our methods mitigate the bias by a large margin while maintaining a satisfactory evaluation accuracy.

[Arxiv](https://arxiv.org/abs/2409.16788)