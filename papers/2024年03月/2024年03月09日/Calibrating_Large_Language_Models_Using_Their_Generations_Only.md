# 本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。

发布时间：2024年03月09日

`LLM应用`

> Calibrating Large Language Models Using Their Generations Only

# 摘要

> 随着LLMs在各类用户应用中的普及，准确评估模型预测信心以确保安全性和可信度变得至关重要。但目前面临的难题是，在仅能通过模型生成文本与之互动的情况下，如何有效地对其进行校准。为此，我们创新提出了一种名为APRICOT的方法，它专注于辅助预测LLM的信心目标，即训练一个额外的模型，仅依据LLM的输入输出文本预测其预测信心。此方法简洁易懂，无需访问模型内部结构，不影响语言生成过程，而且具有广泛的应用潜力，如明确表述预测信心等级或基于信心调整答案。实验结果显示，无论是在白盒还是黑盒LLM中，在封闭型问题回答任务上判断LLM答案正确与否时，APRICOT方法在校准误差上的表现均相当出色。

> As large language models (LLMs) are increasingly deployed in user-facing applications, building trust and maintaining safety by accurately quantifying a model's confidence in its prediction becomes even more important. However, finding effective ways to calibrate LLMs - especially when the only interface to the models is their generated text - remains a challenge. We propose APRICOT (auxiliary prediction of confidence targets): A method to set confidence targets and train an additional model that predicts an LLM's confidence based on its textual input and output alone. This approach has several advantages: It is conceptually simple, does not require access to the target model beyond its output, does not interfere with the language generation, and has a multitude of potential usages, for instance by verbalizing the predicted confidence or adjusting the given answer based on the confidence. We show how our approach performs competitively in terms of calibration error for white-box and black-box LLMs on closed-book question-answering to detect incorrect LLM answers.

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/x1.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/peach.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/x2.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/peach.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/default_strategy.drawio.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/cot_strategy.drawio.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/verbalized_strategy.drawio.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/06-03-2024_test_binary_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/16-02-2024_test_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/cluster_sizes.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/cluster_sizes_coqa.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/calibration_targets.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/calibration_targets_gpt3_5.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/calibration_targets_vicuna_coqa.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/calibration_targets_gpt3_5_coqa.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/clusters.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/clusters_gpt3_5.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/clusters_vicuna_coqa.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/clusters_gpt_3_5_coqa.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/24-02-2024_test_binary_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/16-02-2024_test_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/24-02-2024_test_binary_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/22-02-2024_test_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/06-03-2024_test_binary_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/06-03-2024_test_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_ts_cot_seq_likelihood.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_qual.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/test_verbalized_cot_quant.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/27-02-2024_test_binary_answer_question.png)

![本研究专注于仅通过大型语言模型自身生成的内容对其进行校准，探讨无需额外数据辅助即可提升其准确性和可信度的方法。](../../../paper_images/2403.05973/27-02-2024_test_answer_question.png)

[Arxiv](https://arxiv.org/abs/2403.05973)