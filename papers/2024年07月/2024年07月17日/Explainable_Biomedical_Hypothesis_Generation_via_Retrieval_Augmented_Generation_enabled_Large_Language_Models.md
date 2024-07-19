# 利用检索增强生成技术的大型语言模型，实现生物医学假设的可解释生成

发布时间：2024年07月17日

`RAG` `生物医学`

> Explainable Biomedical Hypothesis Generation via Retrieval Augmented Generation enabled Large Language Models

# 摘要

> 当前生物医学信息的庞大规模对研究者构成了挑战。大型语言模型（LLMs）虽强大，但可能产生幻觉响应，因此检索增强生成（RAG）对确保信息准确性至关重要。我们提出的RUGGED系统，通过图引导的可解释疾病区分进行检索，整合文本挖掘与图预测模型，从文献和数据库中提炼信息，预测药物与疾病的潜在关联。这一框架结合RAG技术，助力研究者深入探索机制与假设。临床实例显示，RUGGED能有效评估并推荐针对特定心肌病的治疗方案，分析药物分子作用及新应用，减少模型幻觉，提供实用见解，推动新药研发。

> The vast amount of biomedical information available today presents a significant challenge for investigators seeking to digest, process, and understand these findings effectively. Large Language Models (LLMs) have emerged as powerful tools to navigate this complex and challenging data landscape. However, LLMs may lead to hallucinatory responses, making Retrieval Augmented Generation (RAG) crucial for achieving accurate information. In this protocol, we present RUGGED (Retrieval Under Graph-Guided Explainable disease Distinction), a comprehensive workflow designed to support investigators with knowledge integration and hypothesis generation, identifying validated paths forward. Relevant biomedical information from publications and knowledge bases are reviewed, integrated, and extracted via text-mining association analysis and explainable graph prediction models on disease nodes, forecasting potential links among drugs and diseases. These analyses, along with biomedical texts, are integrated into a framework that facilitates user-directed mechanism elucidation as well as hypothesis exploration through RAG-enabled LLMs. A clinical use-case demonstrates RUGGED's ability to evaluate and recommend therapeutics for Arrhythmogenic Cardiomyopathy (ACM) and Dilated Cardiomyopathy (DCM), analyzing prescribed drugs for molecular interactions and unexplored uses. The platform minimizes LLM hallucinations, offers actionable insights, and improves the investigation of novel therapeutics.

[Arxiv](https://arxiv.org/abs/2407.12888)