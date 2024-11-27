# 人工智能能否预测临床试验的结果？

发布时间：2024年11月26日

`LLM应用` `临床试验`

> Can artificial intelligence predict clinical trial outcomes?

# 摘要

> 临床试验，尤其是在肿瘤学和先进疗法领域，其复杂性与成本持续攀升，给药物研发带来了巨大挑战。本研究对 GPT-3.5、GPT-4 和 HINT 等大型语言模型在判定临床试验结果方面的预测能力进行了评估。借助从 ClinicalTrials.gov 整理的试验数据集，我们通过平衡准确率、特异性、召回率以及马修斯相关系数（MCC）等指标来对比模型的性能。结果显示，GPT-4 在早期试验阶段表现强劲，召回率高，但特异性有限。相反，HINT 模型在识别负面结果上表现出众，尤其在后期试验阶段，能在不同终点上提供均衡的方法。具有高复杂性特点的肿瘤学试验对所有模型而言依旧充满挑战。另外，试验时长和疾病类别会影响预测性能，时长较长以及像肿瘤这样的复杂疾病会降低准确性。本研究凸显了 LLMs 和 HINT 的互补优势，为优化临床试验设计和风险管理的预测工具提供了思路。未来 LLMs 的发展对于填补当前在处理负面结果和复杂领域方面的空白至关重要。

> The increasing complexity and cost of clinical trials, particularly in the context of oncology and advanced therapies, pose significant challenges for drug development. This study evaluates the predictive capabilities of large language models (LLMs) such as GPT-3.5, GPT-4, and HINT in determining clinical trial outcomes. By leveraging a curated dataset of trials from ClinicalTrials.gov, we compare the models' performance using metrics including balanced accuracy, specificity, recall, and Matthews Correlation Coefficient (MCC). Results indicate that GPT-4o demonstrates robust performance in early trial phases, achieving high recall but facing limitations in specificity. Conversely, the HINT model excels in recognizing negative outcomes, particularly in later trial phases, offering a balanced approach across diverse endpoints. Oncology trials, characterized by high complexity, remain challenging for all models. Additionally, trial duration and disease categories influence predictive performance, with longer durations and complex diseases such as neoplasms reducing accuracy. This study highlights the complementary strengths of LLMs and HINT, providing insights into optimizing predictive tools for clinical trial design and risk management. Future advancements in LLMs are essential to address current gaps in handling negative outcomes and complex domains.

[Arxiv](https://arxiv.org/abs/2411.17595)