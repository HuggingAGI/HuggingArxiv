# 确保在多样化的应用场景中实现大型语言模型服务的公平性

发布时间：2024年11月24日

`LLM应用` `语言模型` `服务平台`

> Ensuring Fair LLM Serving Amid Diverse Applications

# 摘要

> 在服务多种应用的多租户大型语言模型（LLM）服务平台里，部分用户可能提交大量请求，致使服务对其他用户无法使用，形成不公平现象。现有的公平手段未考虑不同应用及多次 LLM 调用中的令牌长度差异，所以不适用于这类平台。为应对公平性难题，本文对微软托管的真实多租户 LLM 平台 MS CoPilot 上数千用户的数百万个请求进行了分析。我们的分析证实了现有方法的缺陷，并引导开发出 FairServe 系统，它能保障不同应用间公平地访问 LLM。FairServe 提出了应用特征感知的请求限流，以及基于加权服务计数器的调度技术，以遏制不良行为并确保公平。我们在真实跟踪数据上的实验结果显示，FairServe 在确保公平方面比最先进的方法更出色。我们正积极推进系统的生产部署，期望能造福全球数百万用户。

> In a multi-tenant large language model (LLM) serving platform hosting diverse applications, some users may submit an excessive number of requests, causing the service to become unavailable to other users and creating unfairness. Existing fairness approaches do not account for variations in token lengths across applications and multiple LLM calls, making them unsuitable for such platforms. To address the fairness challenge, this paper analyzes millions of requests from thousands of users on MS CoPilot, a real-world multi-tenant LLM platform hosted by Microsoft. Our analysis confirms the inadequacy of existing methods and guides the development of FairServe, a system that ensures fair LLM access across diverse applications. FairServe proposes application-characteristic aware request throttling coupled with a weighted service counter based scheduling technique to curb abusive behavior and ensure fairness. Our experimental results on real-world traces demonstrate FairServe's superior performance compared to the state-of-the-art method in ensuring fairness. We are actively working on deploying our system in production, expecting to benefit millions of customers world-wide.

[Arxiv](https://arxiv.org/abs/2411.15997)