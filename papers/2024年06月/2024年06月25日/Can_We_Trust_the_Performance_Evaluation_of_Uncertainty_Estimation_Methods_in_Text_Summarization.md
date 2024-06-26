# 文本摘要中不确定性估计方法的性能评估，我们能否信以为真？

发布时间：2024年06月25日

`LLM应用

理由：这篇论文主要关注的是文本摘要任务中的不确定性估计（UE-TS），并为此推出了一套综合基准，评估了不同语言模型在此任务上的表现。虽然涉及到语言模型的应用，但重点在于如何通过多种NLG指标和不确定性估计方法来提高文本摘要任务的可靠性和效率，这属于LLM在特定应用场景（文本摘要）中的实际应用和评估，因此归类为LLM应用。` `人机交互`

> Can We Trust the Performance Evaluation of Uncertainty Estimation Methods in Text Summarization?

# 摘要

> 文本摘要作为NLG的核心任务，在多领域中扮演着关键角色。但在高风险应用，尤其是涉及人机交互决策的场景中，不准确的摘要可能导致严重后果，这使得文本摘要的不确定性估计（UE-TS）评估方法的可靠性备受关注。这一关注点源于不确定性模型对多样且可能矛盾的NLG指标的依赖。为此，我们推出了一套包含31种NLG指标的UE-TS综合基准，覆盖四个维度，并评估了两大语言模型及一预训练模型在三组数据上的不确定性估计能力，同时结合了必要的人工分析。此外，我们还测试了14种不确定性估计方法在此基准上的表现。研究结果表明，综合考虑多个独立的NLG指标及多元的不确定性估计方法，对于确保UE-TS评估的可靠性和效率至关重要。

> Text summarization, a key natural language generation (NLG) task, is vital in various domains. However, the high cost of inaccurate summaries in risk-critical applications, particularly those involving human-in-the-loop decision-making, raises concerns about the reliability of uncertainty estimation on text summarization (UE-TS) evaluation methods. This concern stems from the dependency of uncertainty model metrics on diverse and potentially conflicting NLG metrics. To address this issue, we introduce a comprehensive UE-TS benchmark incorporating 31 NLG metrics across four dimensions. The benchmark evaluates the uncertainty estimation capabilities of two large language models and one pre-trained language model on three datasets, with human-annotation analysis incorporated where applicable. We also assess the performance of 14 common uncertainty estimation methods within this benchmark. Our findings emphasize the importance of considering multiple uncorrelated NLG metrics and diverse uncertainty estimation methods to ensure reliable and efficient evaluation of UE-TS techniques.

[Arxiv](https://arxiv.org/abs/2406.17274)