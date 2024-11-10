# 关于近期大型语言模型在为肺癌患者生成出院小结方面的比较研究

发布时间：2024年11月06日

`LLM应用`

> A Comparative Study of Recent Large Language Models on Generating Hospital Discharge Summaries for Lung Cancer Patients

# 摘要

> 生成出院小结在临床实践中是一项关键但耗时的任务，对于传达相关患者信息和促进护理的连续性至关重要。大型语言模型（LLM）的最新进展显著增强了它们理解和总结复杂医学文本的能力。本研究旨在探索 LLM 如何减轻手动总结的负担，提高工作流程效率，并支持医疗保健环境中的知情决策。利用了 1099 名肺癌患者的临床记录，其中 50 名患者用于测试，102 名患者用于模型微调。本研究评估了多个 LLM（包括 GPT-3.5、GPT-4、GPT-4o 和 LLaMA 3 8b）生成出院小结的性能。评估指标包括标记级别分析（BLEU、ROUGE-1、ROUGE-2、ROUGE-L）以及模型生成的摘要与医生编写的黄金标准之间的语义相似度得分。LLaMA 3 8b 还在不同长度的临床记录上进行了测试，以检查其性能的稳定性。研究发现 LLM 之间的总结能力存在显著差异。GPT-4o 和微调后的 LLaMA 3 在标记级别评估指标上表现出色，而 LLaMA 3 在不同输入长度下始终生成简洁的摘要。语义相似度得分表明 GPT-4o 和 LLaMA 3 是捕捉临床相关性的领先模型。本研究为 LLM 生成出院小结的有效性提供了见解，突出了 LLaMA 3 在不同临床环境中保持清晰和相关性的强大性能。这些发现强调了自动总结工具在提高文档准确性和效率方面的潜力，最终改善医疗保健环境中的患者护理和运营能力。

> Generating discharge summaries is a crucial yet time-consuming task in clinical practice, essential for conveying pertinent patient information and facilitating continuity of care. Recent advancements in large language models (LLMs) have significantly enhanced their capability in understanding and summarizing complex medical texts. This research aims to explore how LLMs can alleviate the burden of manual summarization, streamline workflow efficiencies, and support informed decision-making in healthcare settings. Clinical notes from a cohort of 1,099 lung cancer patients were utilized, with a subset of 50 patients for testing purposes, and 102 patients used for model fine-tuning. This study evaluates the performance of multiple LLMs, including GPT-3.5, GPT-4, GPT-4o, and LLaMA 3 8b, in generating discharge summaries. Evaluation metrics included token-level analysis (BLEU, ROUGE-1, ROUGE-2, ROUGE-L) and semantic similarity scores between model-generated summaries and physician-written gold standards. LLaMA 3 8b was further tested on clinical notes of varying lengths to examine the stability of its performance. The study found notable variations in summarization capabilities among LLMs. GPT-4o and fine-tuned LLaMA 3 demonstrated superior token-level evaluation metrics, while LLaMA 3 consistently produced concise summaries across different input lengths. Semantic similarity scores indicated GPT-4o and LLaMA 3 as leading models in capturing clinical relevance. This study contributes insights into the efficacy of LLMs for generating discharge summaries, highlighting LLaMA 3's robust performance in maintaining clarity and relevance across varying clinical contexts. These findings underscore the potential of automated summarization tools to enhance documentation precision and efficiency, ultimately improving patient care and operational capability in healthcare settings.

[Arxiv](https://arxiv.org/abs/2411.03805)