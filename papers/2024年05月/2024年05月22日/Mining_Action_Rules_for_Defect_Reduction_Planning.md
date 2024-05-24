# 挖掘行动规则，助力缺陷减少规划

发布时间：2024年05月22日

`LLM应用

这篇论文主要讨论了如何利用大型语言模型（LLM）来生成代码编辑，以提高软件质量和降低维护成本。通过CounterACT方法，论文展示了如何生成缺陷减少策略，并通过实验评估了这些策略的有效性。这种方法涉及到了LLM的应用，特别是在软件工程领域，因此将其归类为LLM应用。` `软件工程` `缺陷减少`

> Mining Action Rules for Defect Reduction Planning

# 摘要

> 在提升软件质量和降低维护成本方面，缺陷减少规划至关重要。通过训练黑盒机器学习模型并解释其预测，软件工程中的可解释AI旨在揭示影响维护风险的代码特性。但事后解释未必能准确反映模型的原始计算。本文介绍了CounterACT，一种无需依赖黑盒模型的反事实行动规则挖掘方法，用于生成缺陷减少策略。CounterACT利用行动规则，为代码分类（如缺陷与否）提供了一种反事实解释的行动路径。我们对比了CounterACT与原始行动规则挖掘算法及六种主流缺陷减少方法在9个软件项目上的效果。评估指标包括：（a）提出的代码变更与开发者实际修改的重叠度；（b）未来版本的改进程度；以及（c）计划的精确度、召回率和F1分数。结果显示，CounterACT的解释性计划在发布和提交级别上重叠度更高（中位数分别为95%和85.97%），并在精确度和召回率之间取得更优平衡（中位数F1分数88.12%）。此外，我们还探索了利用大型语言模型（LLM）根据我们的计划生成代码编辑，发现这些建议更实用，且通过相关测试的可能性更大。

> Defect reduction planning plays a vital role in enhancing software quality and minimizing software maintenance costs. By training a black box machine learning model and "explaining" its predictions, explainable AI for software engineering aims to identify the code characteristics that impact maintenance risks. However, post-hoc explanations do not always faithfully reflect what the original model computes. In this paper, we introduce CounterACT, a Counterfactual ACTion rule mining approach that can generate defect reduction plans without black-box models. By leveraging action rules, CounterACT provides a course of action that can be considered as a counterfactual explanation for the class (e.g., buggy or not buggy) assigned to a piece of code. We compare the effectiveness of CounterACT with the original action rule mining algorithm and six established defect reduction approaches on 9 software projects. Our evaluation is based on (a) overlap scores between proposed code changes and actual developer modifications; (b) improvement scores in future releases; and (c) the precision, recall, and F1-score of the plans. Our results show that, compared to competing approaches, CounterACT's explainable plans achieve higher overlap scores at the release level (median 95%) and commit level (median 85.97%), and they offer better trade-off between precision and recall (median F1-score 88.12%). Finally, we venture beyond planning and explore leveraging Large Language models (LLM) for generating code edits from our generated plans. Our results show that suggested LLM code edits supported by our plans are actionable and are more likely to pass relevant test cases than vanilla LLM code recommendations.

[Arxiv](https://arxiv.org/abs/2405.13740)