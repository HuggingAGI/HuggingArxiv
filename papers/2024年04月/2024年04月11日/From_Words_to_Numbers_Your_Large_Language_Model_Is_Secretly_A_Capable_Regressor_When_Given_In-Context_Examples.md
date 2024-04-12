# 大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。

发布时间：2024年04月11日

`LLM应用` `机器学习` `回归分析`

> From Words to Numbers: Your Large Language Model Is Secretly A Capable Regressor When Given In-Context Examples

# 摘要

> 我们探究了预训练的大型语言模型（如Llama2、GPT-4、Claude 3等）在仅提供上下文示例、无需进一步训练或梯度更新的情况下，完成线性和非线性回归的能力如何。研究发现，某些大型语言模型（如GPT-4、Claude 3）在执行回归任务时，其表现与传统的监督学习方法如随机森林、装袋法或梯度提升法相媲美，甚至更胜一筹。以Friedman #2这一复杂的回归数据集为例，Claude 3的表现超越了AdaBoost、SVM、随机森林、KNN和梯度提升法等多种监督学习方法。接着，我们考察了模型性能随上下文示例数量增加的扩展情况，借鉴在线学习中的“遗憾”概念，实证结果显示大型语言模型能够实现次线性的遗憾。

> We analyze how well pre-trained large language models (e.g., Llama2, GPT-4, Claude 3, etc) can do linear and non-linear regression when given in-context examples, without any additional training or gradient updates. Our findings reveal that several large language models (e.g., GPT-4, Claude 3) are able to perform regression tasks with a performance rivaling (or even outperforming) that of traditional supervised methods such as Random Forest, Bagging, or Gradient Boosting. For example, on the challenging Friedman #2 regression dataset, Claude 3 outperforms many supervised methods such as AdaBoost, SVM, Random Forest, KNN, or Gradient Boosting. We then investigate how well the performance of large language models scales with the number of in-context exemplars. We borrow from the notion of regret from online learning and empirically show that LLMs are capable of obtaining a sub-linear regret.

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni12_reduced.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/linear_regression_ranks_heatmap_v3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/non_linear_regression_ranks_heatmap_v2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/beyond_numeric_regression.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni11.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni12.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni23.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regression_ni33.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/linear_regression_ranks_heatmap_expanded_v3_wmoremodels_landscape.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/original2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/original3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/original4.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/original5.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/simple_random_nn1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/transformer1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/non_linear_regression_ranks_heatmap_expanded_v2_wmoremodels_landscape.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_yi34chat_friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_yi34chat_friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_yi34chat_friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_yi34chat_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_original2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_original2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_yi34chat_original2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_yi34chat_regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_claude3opus_regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gpt4-turbo_regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_yi34chat_regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gb_friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_with_polynomial_friedman1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gb_friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_with_polynomial_friedman2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gb_friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_with_polynomial_friedman3.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gb_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_with_polynomial_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_original2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gb_original2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_with_polynomial_original2.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gb_regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_with_polynomial_regression_ni13.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_gb_regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/regret_lr_with_polynomial_regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/claude_performance.jpeg)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/effects_of_rounding_nlr_heatmap.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/llms_vs_knns.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/contamination_regression_ni11.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/contamination_regression_ni12.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/contamination_regression_ni22.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/contamination_original1.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/contamination_heatmap.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/gpt4_friedman1_plateauing.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/gpt4_friedman2_plateauing.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/gpt4_friedman3_plateauing.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/gpt4_original1_plateauing.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/gpt4_original2_plateauing.png)

![大型语言模型，在你提供上下文示例的情况下，其实是位隐秘的回归高手。](../../../paper_images/2404.07544/nontransformerbasedllms_heatmap.jpeg)

[Arxiv](https://arxiv.org/abs/2404.07544)