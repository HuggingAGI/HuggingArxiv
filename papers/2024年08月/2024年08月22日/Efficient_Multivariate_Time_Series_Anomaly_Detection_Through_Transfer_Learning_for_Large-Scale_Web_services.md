# 利用迁移学习技术，我们实现了针对大规模网络服务的高效多元时间序列异常检测。

发布时间：2024年08月22日

`LLM应用` `信息技术`

> Efficient Multivariate Time Series Anomaly Detection Through Transfer Learning for Large-Scale Web services

# 摘要

> 大型语言模型（LLM）虽在通用问答中表现卓越，但在专业领域因缺乏特定知识而表现欠佳。商业公司在利用LLM进行微调时，既要保护隐私又要应对资源限制。为此，我们提出“自我进化”框架，通过多次迭代微调轻量级开源LLM来应对这些挑战。该框架在迭代过程中筛选并强化高价值知识，以提升微调效率。我们利用4,000份富含中国移动领域知识的文档对Qwen1.5-7B-Chat进行“自我进化”，使其在特定领域问答评估中的性能得分比原版高出174%，甚至超越了更大型号的Qwen1.5-72B-Chat。该框架已在中国移动的日常运维中应用117天，显著提升了定位警报、问题修复及报告查找的效率，平均提升超过18.6%。此外，我们已在GitHub上发布“自我进化”框架代码，供业界参考。

> Large language models (LLMs) excel at general question-answering (Q&A) but often fall short in specialized domains due to a lack of domain-specific knowledge. Commercial companies face the dual challenges of privacy protection and resource constraints when involving LLMs for fine-tuning. This paper propose a novel framework, Self-Evolution, designed to address these issues by leveraging lightweight open-source LLMs through multiple iterative fine-tuning rounds. To enhance the efficiency of iterative fine-tuning, Self-Evolution employ a strategy that filters and reinforces the knowledge with higher value during the iterative process. We employed Self-Evolution on Qwen1.5-7B-Chat using 4,000 documents containing rich domain knowledge from China Mobile, achieving a performance score 174% higher on domain-specific question-answering evaluations than Qwen1.5-7B-Chat and even 22% higher than Qwen1.5-72B-Chat. Self-Evolution has been deployed in China Mobile's daily operation and maintenance for 117 days, and it improves the efficiency of locating alarms, fixing problems, and finding related reports, with an average efficiency improvement of over 18.6%. In addition, we release Self-Evolution framework code in https://github.com/Zero-Pointer/Self-Evolution.

[Arxiv](https://arxiv.org/abs/2408.12247)