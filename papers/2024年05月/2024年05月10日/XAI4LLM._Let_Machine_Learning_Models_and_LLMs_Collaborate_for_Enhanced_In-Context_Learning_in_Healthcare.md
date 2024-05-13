# XAI4LLM：携手机器学习与大型语言模型，共铸医疗领域上下文学习的辉煌。

发布时间：2024年05月10日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在医疗诊断领域的应用，特别是通过一种新颖的上下文学习（ICL）方法来整合医学知识，并分析了不同沟通风格对诊断准确性和风险的影响。研究结果表明，通过结合少量示例和可解释人工智能（XAI）方法，LLMs的性能可以得到显著提升，特别是在成本敏感性方面。这表明，通过精心设计的领域知识和沟通策略，LLMs能够显著提升诊断效率。因此，这篇论文属于LLM应用分类，因为它关注的是LLMs在特定领域（医疗诊断）的实际应用和效果。` `医疗诊断` `临床决策支持`

> XAI4LLM. Let Machine Learning Models and LLMs Collaborate for Enhanced In-Context Learning in Healthcare

# 摘要

> 将LLMs融入医疗诊断为临床决策开辟了新途径。本研究提出了一种新颖的ICL方法，通过多层结构化提示整合医学知识，并比较了NC和NL-ST两种沟通风格的效果。我们系统地分析了920名患者的诊断准确性和风险，发现尽管传统ML模型在零-shot和few-shot场景中表现更佳，但结合few-shot示例和XAI方法后，LLMs的性能大幅提升。特别是，随着示例增多，NC风格几乎与ML模型媲美，且LLMs在成本敏感性上表现出色。这表明，通过精心设计的领域知识和沟通策略，LLMs能显著提升诊断效率。研究强调了优化训练示例和沟通风格对于提高LLMs准确性和减少偏见的重要性。

> The integration of Large Language Models (LLMs) into healthcare diagnostics offers a promising avenue for clinical decision-making. This study outlines the development of a novel method for zero-shot/few-shot in-context learning (ICL) by integrating medical domain knowledge using a multi-layered structured prompt. We also explore the efficacy of two communication styles between the user and LLMs: the Numerical Conversational (NC) style, which processes data incrementally, and the Natural Language Single-Turn (NL-ST) style, which employs long narrative prompts. Our study systematically evaluates the diagnostic accuracy and risk factors, including gender bias and false negative rates, using a dataset of 920 patient records in various few-shot scenarios. Results indicate that traditional clinical machine learning (ML) models generally outperform LLMs in zero-shot and few-shot settings. However, the performance gap narrows significantly when employing few-shot examples alongside effective explainable AI (XAI) methods as sources of domain knowledge. Moreover, with sufficient time and an increased number of examples, the conversational style (NC) nearly matches the performance of ML models. Most notably, LLMs demonstrate comparable or superior cost-sensitive accuracy relative to ML models. This research confirms that, with appropriate domain knowledge and tailored communication strategies, LLMs can significantly enhance diagnostic processes. The findings highlight the importance of optimizing the number of training examples and communication styles to improve accuracy and reduce biases in LLM applications.

[Arxiv](https://arxiv.org/abs/2405.06270)