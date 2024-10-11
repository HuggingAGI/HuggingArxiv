# 无需标注数据，实现 LLM 服务的即插即用性能评估

发布时间：2024年10月10日

`LLM应用` `人工智能` `软件服务`

> Plug-and-Play Performance Estimation for LLM Services without Relying on Labeled Data

# 摘要

> 大型语言模型（LLM）服务通过上下文学习（ICL）在未学习任务上表现出色，仅需少量示例。然而，ICL 的成功因任务和上下文而异，导致服务质量参差不齐。直接评估每次调用 LLM 服务的性能既费力又需大量标注数据或内部信息。本文提出一种新方法，利用少量未标注样本，实现“即插即用”式的性能估计。研究发现，负对数似然和困惑度是有效特征。基于此，我们采用四种元模型进行性能估计，并与无标注基线对比，实验证明其在选择和优化 LLM 服务中的有效性。

> Large Language Model (LLM) services exhibit impressive capability on unlearned tasks leveraging only a few examples by in-context learning (ICL). However, the success of ICL varies depending on the task and context, leading to heterogeneous service quality. Directly estimating the performance of LLM services at each invocation can be laborious, especially requiring abundant labeled data or internal information within the LLM. This paper introduces a novel method to estimate the performance of LLM services across different tasks and contexts, which can be "plug-and-play" utilizing only a few unlabeled samples like ICL. Our findings suggest that the negative log-likelihood and perplexity derived from LLM service invocation can function as effective and significant features. Based on these features, we utilize four distinct meta-models to estimate the performance of LLM services. Our proposed method is compared against unlabeled estimation baselines across multiple LLM services and tasks. And it is experimentally applied to two scenarios, demonstrating its effectiveness in the selection and further optimization of LLM services.

[Arxiv](https://arxiv.org/abs/2410.07737)