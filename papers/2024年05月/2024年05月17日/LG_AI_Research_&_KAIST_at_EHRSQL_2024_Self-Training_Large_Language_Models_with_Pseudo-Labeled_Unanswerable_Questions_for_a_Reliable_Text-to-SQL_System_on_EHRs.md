# LG AI Research 携手 KAIST 在 EHRSQL 2024 展示：通过利用伪标记的不可回答问题，自我训练大型语言模型，旨在打造一个高效可靠的电子健康记录文本至 SQL 转换系统。

发布时间：2024年05月17日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）改进Text-to-SQL模型在医疗领域的应用，特别是在电子健康记录（EHRs）的访问方面。论文提出了一种新的训练策略，旨在提高模型的可靠性，确保其能够准确处理无法回答的问题或不确定的预测。这种方法的应用性质明显，因为它直接关联到如何改进特定领域（医疗）中的技术应用（Text-to-SQL模型），而不是专注于LLM的理论研究或Agent的设计与实现。因此，将其归类为LLM应用是合适的。` `电子健康记录`

> LG AI Research & KAIST at EHRSQL 2024: Self-Training Large Language Models with Pseudo-Labeled Unanswerable Questions for a Reliable Text-to-SQL System on EHRs

# 摘要

> Text-to-SQL模型是让医疗专业人员无需SQL知识就能访问电子健康记录（EHRs）的关键。随着大型语言模型的进步，这些系统已能更熟练地将复杂问题转化为SQL查询。但在医疗领域，确保模型的可靠性至关重要，这要求模型能精准识别无法回答的问题或不确定的预测，以防误导信息。为此，我们提出了一种利用伪标记的无法回答问题进行自我训练的策略，旨在提升EHRs中text-to-SQL模型的可靠性。该策略包含两阶段训练及基于令牌熵和查询执行的过滤机制。我们的方法在EHRSQL 2024共享任务中取得优异成绩，证明了其通过更可靠的text-to-SQL系统助力医疗决策的潜力。

> Text-to-SQL models are pivotal for making Electronic Health Records (EHRs) accessible to healthcare professionals without SQL knowledge. With the advancements in large language models, these systems have become more adept at translating complex questions into SQL queries. Nonetheless, the critical need for reliability in healthcare necessitates these models to accurately identify unanswerable questions or uncertain predictions, preventing misinformation. To address this problem, we present a self-training strategy using pseudo-labeled unanswerable questions to enhance the reliability of text-to-SQL models for EHRs. This approach includes a two-stage training process followed by a filtering method based on the token entropy and query execution. Our methodology's effectiveness is validated by our top performance in the EHRSQL 2024 shared task, showcasing the potential to improve healthcare decision-making through more reliable text-to-SQL systems.

![LG AI Research 携手 KAIST 在 EHRSQL 2024 展示：通过利用伪标记的不可回答问题，自我训练大型语言模型，旨在打造一个高效可靠的电子健康记录文本至 SQL 转换系统。](../../../paper_images/2405.11162/x1.png)

![LG AI Research 携手 KAIST 在 EHRSQL 2024 展示：通过利用伪标记的不可回答问题，自我训练大型语言模型，旨在打造一个高效可靠的电子健康记录文本至 SQL 转换系统。](../../../paper_images/2405.11162/final_prompt.png)

[Arxiv](https://arxiv.org/abs/2405.11162)