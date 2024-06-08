# 大型语言模型：推荐解释的智能评估者

发布时间：2024年06月05日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在评估推荐系统解释文本质量方面的应用。它特别关注了LLMs在遵循指令和常识推理方面的能力，并研究了这些模型是否适合作为推荐解释的评估者。论文通过实验和分析，展示了LLMs在特定设置下能够提供与人类评估相媲美的评价，并探讨了如何整合人类标签和利用多个异质LLM评估者的集成来提高评估的准确性和稳定性。因此，这篇论文属于LLM应用类别，因为它专注于LLMs在实际应用中的使用，特别是在推荐系统解释评估这一特定领域。` `推荐系统`

> Large Language Models as Evaluators for Recommendation Explanations

# 摘要

> 推荐系统的可解释性备受学术界和工业界关注，尽管已有诸多努力，但评估解释质量依旧充满挑战。近年来，LLMs在自然语言处理任务中作为评估者展现出潜力，尤其在遵循指令和常识推理方面表现卓越。然而，评估推荐解释文本的标准与人类感知紧密相关，且常带主观性，这使其与NLG任务有所不同。本文探讨了LLMs是否适合作为推荐解释的评估者，通过分析先前工作中用户的反馈，并结合第三方标注和LLM评估，我们采用了一种三层元评估策略来衡量评估结果与用户真实反馈的相关性。实验结果显示，在恰当的提示和设置下，如GPT4这样的LLMs能提供与人类评估相媲美的评价。此外，我们还探讨了如何将人类标签融入LLM评估过程，并利用多个异质LLM评估者的集成来提升评估的准确性和稳定性。研究表明，LLMs作为评估者是评估推荐解释文本的一种准确、可重复且经济高效的解决方案，相关代码已公开于https://github.com/Xiaoyu-SZ/LLMasEvaluator。

> The explainability of recommender systems has attracted significant attention in academia and industry. Many efforts have been made for explainable recommendations, yet evaluating the quality of the explanations remains a challenging and unresolved issue. In recent years, leveraging LLMs as evaluators presents a promising avenue in Natural Language Processing tasks (e.g., sentiment classification, information extraction), as they perform strong capabilities in instruction following and common-sense reasoning. However, evaluating recommendation explanatory texts is different from these NLG tasks, as its criteria are related to human perceptions and are usually subjective. In this paper, we investigate whether LLMs can serve as evaluators of recommendation explanations. To answer the question, we utilize real user feedback on explanations given from previous work and additionally collect third-party annotations and LLM evaluations. We design and apply a 3-level meta evaluation strategy to measure the correlation between evaluator labels and the ground truth provided by users. Our experiments reveal that LLMs, such as GPT4, can provide comparable evaluations with appropriate prompts and settings. We also provide further insights into combining human labels with the LLM evaluation process and utilizing ensembles of multiple heterogeneous LLM evaluators to enhance the accuracy and stability of evaluations. Our study verifies that utilizing LLMs as evaluators can be an accurate, reproducible and cost-effective solution for evaluating recommendation explanation texts. Our code is available at https://github.com/Xiaoyu-SZ/LLMasEvaluator.

![大型语言模型：推荐解释的智能评估者](../../../paper_images/2406.03248/x1.png)

![大型语言模型：推荐解释的智能评估者](../../../paper_images/2406.03248/x2.png)

![大型语言模型：推荐解释的智能评估者](../../../paper_images/2406.03248/x3.png)

![大型语言模型：推荐解释的智能评估者](../../../paper_images/2406.03248/x4.png)

[Arxiv](https://arxiv.org/abs/2406.03248)