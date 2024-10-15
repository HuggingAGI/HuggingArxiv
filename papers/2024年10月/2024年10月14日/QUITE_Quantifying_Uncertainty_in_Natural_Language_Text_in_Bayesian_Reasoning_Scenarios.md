# QUITE：在贝叶斯推理背景下，精准量化自然语言文本的不确定性

发布时间：2024年10月14日

`LLM理论` `人工智能` `数据科学`

> QUITE: Quantifying Uncertainty in Natural Language Text in Bayesian Reasoning Scenarios

# 摘要

> 推理在众多决策过程中至关重要，它涉及整合带有不确定性的规则性前提和观察结果以得出结论。我们在这项研究中探讨了两种情况：一是前提被量化为概率规则，二是人类用模糊的词语表达其估计。现有数据集简化了推理任务，如仅要求模型排序文本选项或仅使用二元变量。为此，我们推出了QUITE，一个包含复杂关系和分类变量的真实贝叶斯推理数据集。QUITE不仅提供高质量的前提表述和证据，还要求以概率形式回答问题。实验表明，逻辑模型在各类推理任务中均优于大型语言模型，这为神经符号模型在复杂推理中的潜力提供了有力支持。我们已在Github上公开QUITE及实验代码。

> Reasoning is key to many decision making processes. It requires consolidating a set of rule-like premises that are often associated with degrees of uncertainty and observations to draw conclusions. In this work, we address both the case where premises are specified as numeric probabilistic rules and situations in which humans state their estimates using words expressing degrees of certainty. Existing probabilistic reasoning datasets simplify the task, e.g., by requiring the model to only rank textual alternatives, by including only binary random variables, or by making use of a limited set of templates that result in less varied text.
  In this work, we present QUITE, a question answering dataset of real-world Bayesian reasoning scenarios with categorical random variables and complex relationships. QUITE provides high-quality natural language verbalizations of premises together with evidence statements and expects the answer to a question in the form of an estimated probability. We conduct an extensive set of experiments, finding that logic-based models outperform out-of-the-box large language models on all reasoning types (causal, evidential, and explaining-away). Our results provide evidence that neuro-symbolic models are a promising direction for improving complex reasoning. We release QUITE and code for training and experiments on Github.

[Arxiv](https://arxiv.org/abs/2410.10449)