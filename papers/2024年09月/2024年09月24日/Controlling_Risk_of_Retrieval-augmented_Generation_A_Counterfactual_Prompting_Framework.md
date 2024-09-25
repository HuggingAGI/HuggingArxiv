# 掌控检索增强生成的风险：反事实提示框架

发布时间：2024年09月24日

`RAG` `风险管理`

> Controlling Risk of Retrieval-augmented Generation: A Counterfactual Prompting Framework

# 摘要

> RAG 作为解决大型语言模型幻觉问题的热门方案，却鲜少关注预测不确定性，即模型预测错误的风险。我们强调风险控制，确保 RAG 模型在低置信度时拒绝回答。研究发现，检索结果的质量和使用方式是影响 RAG 置信度的两大关键。为此，我们设计了反事实提示框架，帮助模型自我评估并调整这些因素。同时，引入基准程序收集拒绝回答的答案，进行实验验证。通过风险相关指标的评估，实验结果显示了方法的有效性。

> Retrieval-augmented generation (RAG) has emerged as a popular solution to mitigate the hallucination issues of large language models. However, existing studies on RAG seldom address the issue of predictive uncertainty, i.e., how likely it is that a RAG model's prediction is incorrect, resulting in uncontrollable risks in real-world applications. In this work, we emphasize the importance of risk control, ensuring that RAG models proactively refuse to answer questions with low confidence. Our research identifies two critical latent factors affecting RAG's confidence in its predictions: the quality of the retrieved results and the manner in which these results are utilized. To guide RAG models in assessing their own confidence based on these two latent factors, we develop a counterfactual prompting framework that induces the models to alter these factors and analyzes the effect on their answers. We also introduce a benchmarking procedure to collect answers with the option to abstain, facilitating a series of experiments. For evaluation, we introduce several risk-related metrics and the experimental results demonstrate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2409.16146)