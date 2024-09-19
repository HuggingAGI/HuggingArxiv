# 微调语言模型，使其能够表达不确定性

发布时间：2024年09月18日

`LLM理论` `信息搜索` `决策支持`

> Finetuning Language Models to Emit Linguistic Expressions of Uncertainty

# 摘要

> LLMs 在信息搜索和决策任务中的应用日益广泛，但它们生成的信息常与事实不符，且其说服性风格使这些错误显得自信且有说服力。这导致用户难以准确判断 LLMs 的自信程度与预测准确性，往往陷入盲目信任或完全忽视的两难境地。为此，我们提出通过监督微调来增强模型对不确定性的表达。我们首先评估预训练模型的校准情况，然后微调模型以生成更准确的不确定性表达。实验表明，LLMs 在评估自身预测时表现良好，而基于模型自信的监督微调能显著提升不确定性表达的准确性，尤其在单项答案中效果显著。

> Large language models (LLMs) are increasingly employed in information-seeking and decision-making tasks. Despite their broad utility, LLMs tend to generate information that conflicts with real-world facts, and their persuasive style can make these inaccuracies appear confident and convincing. As a result, end-users struggle to consistently align the confidence expressed by LLMs with the accuracy of their predictions, often leading to either blind trust in all outputs or a complete disregard for their reliability. In this work, we explore supervised finetuning on uncertainty-augmented predictions as a method to develop models that produce linguistic expressions of uncertainty. Specifically, we measure the calibration of pre-trained models and then fine-tune language models to generate calibrated linguistic expressions of uncertainty. Through experiments on various question-answering datasets, we demonstrate that LLMs are well-calibrated in assessing their predictions, and supervised finetuning based on the model's own confidence leads to well-calibrated expressions of uncertainty, particularly for single-claim answers.

[Arxiv](https://arxiv.org/abs/2409.12180)