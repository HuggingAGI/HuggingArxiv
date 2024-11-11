# FactTest：具有统计保证的大型语言模型中的真实性测试

发布时间：2024年11月04日

`LLM应用` `语言模型` `问答系统`

> FactTest: Factuality Testing in Large Language Models with Statistical Guarantees

# 摘要

> 大型语言模型（LLMs）产生幻觉和非事实内容的倾向削弱了它们在高风险领域的可靠性，在这些领域，对 I 型错误（将幻觉错误分类为真实内容的条件概率）的严格控制至关重要。尽管其重要性不言而喻，但对此类保证的 LLM 真实性的正式验证在很大程度上仍未得到探索。在本文中，我们引入了 FactTest，这是一个新颖的框架，它从统计学角度评估 LLM 是否能够自信地为给定问题提供正确率有高概率保证的正确答案。我们将真实性测试表述为假设检验问题，以在用户指定的显著水平上强制 I 型错误的上限。值得注意的是，我们证明了我们的框架在温和条件下也能确保强大的 II 型错误控制，并且在存在协变量偏移时可以扩展以保持其有效性。%这些分析适用于原则性的 NP 框架。我们的方法不受分布限制，适用于任何数量的人工注释样本。它与模型无关，适用于任何黑盒或白盒 LM。在问答（QA）和多项选择基准上的大量实验表明，该方法有效地检测幻觉，并提高了模型避免回答未知问题的能力，导致准确率提高了 40%以上。

> The propensity of Large Language Models (LLMs) to generate hallucinations and non-factual content undermines their reliability in high-stakes domains, where rigorous control over Type I errors (the conditional probability of incorrectly classifying hallucinations as truthful content) is essential. Despite its importance, formal verification of LLM factuality with such guarantees remains largely unexplored. In this paper, we introduce FactTest, a novel framework that statistically assesses whether an LLM can confidently provide correct answers to given questions with high-probability correctness guarantees. We formulate factuality testing as hypothesis testing problem to enforce an upper bound of Type I errors at user-specified significance levels. Notably, we prove that our framework also ensures strong Type II error control under mild conditions and can be extended to maintain its effectiveness when covariate shifts exist. %These analyses are amenable to the principled NP framework. Our approach is distribution-free and works for any number of human-annotated samples. It is model-agnostic and applies to any black-box or white-box LM. Extensive experiments on question-answering (QA) and multiple-choice benchmarks demonstrate that \approach effectively detects hallucinations and improves the model's ability to abstain from answering unknown questions, leading to an over 40% accuracy improvement.

[Arxiv](https://arxiv.org/abs/2411.02603)