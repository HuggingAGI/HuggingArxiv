# MathGAP：针对任意复杂证明问题的分布外评估

发布时间：2024年10月17日

`LLM理论` `人工智能`

> MathGAP: Out-of-Distribution Evaluation on Problems with Arbitrarily Complex Proofs

# 摘要

> 大型语言模型（LLM）在解决算术问题时表现出色，但它们如何应对比训练时更复杂的问题仍是个谜。当前评估方法存在两大缺陷：一是评估数据常与训练数据重叠，二是基准数据集无法涵盖证明的多样复杂性。为此，我们推出了 MathGAP 框架，专门用于评估 LLM 在处理复杂算术证明问题时的表现。MathGAP 通过生成符合固定证明规范的问题，并附带链式思维推理注释，系统地研究了算术证明复杂性对泛化的影响。研究发现，随着证明的复杂度增加，大多数模型的性能显著下降，尤其是在非线性、复杂的证明结构中，即使 GPT-4o 也感到棘手。有趣的是，提供与测试集同分布的上下文示例并不总是提升性能，有时零-shot 提示或展示较简单的多样化示例反而效果更佳。

> Large language models (LLMs) can solve arithmetic word problems with high accuracy, but little is known about how well they generalize to problems that are more complex than the ones on which they have been trained. Empirical investigations of such questions are impeded by two major flaws of current evaluations: (i) much of the evaluation data is contaminated, in the sense that it has already been seen during training, and (ii) benchmark datasets do not capture how problem proofs may be arbitrarily complex in various ways. As a step towards addressing these issues, we present a framework for evaluating LLMs on problems that have arbitrarily complex arithmetic proofs, called MathGAP. MathGAP generates problems that follow fixed proof specifications -- along with chain-of-thought reasoning annotations -- enabling systematic studies on generalization with respect to arithmetic proof complexity. We apply MathGAP to analyze how in-context learning interacts with generalization to problems that have more complex proofs. We find that among the models tested, most show a significant decrease in performance as proofs get deeper and wider. This effect is more pronounced in complex, nonlinear proof structures, which are challenging even for GPT-4o. Surprisingly, providing in-context examples from the same distribution as the test set is not always beneficial for performance. In particular, zero-shot prompting as well as demonstrating a diverse range of examples that are less complex than the test data sometimes yield similar or higher accuracies.

[Arxiv](https://arxiv.org/abs/2410.13502)