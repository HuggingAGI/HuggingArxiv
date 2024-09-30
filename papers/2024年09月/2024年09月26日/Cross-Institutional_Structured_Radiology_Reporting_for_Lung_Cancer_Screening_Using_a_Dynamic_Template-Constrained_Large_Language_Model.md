# 利用动态模板约束的大型语言模型，实现肺癌筛查的跨机构结构化放射学报告。

发布时间：2024年09月26日

`LLM应用` `放射学`

> Cross-Institutional Structured Radiology Reporting for Lung Cancer Screening Using a Dynamic Template-Constrained Large Language Model

# 摘要

> 结构化放射报告有助于优化临床流程和患者结果。然而，当前的 LLM 在生成结构化报告时面临格式错误、内容幻觉和隐私泄露等挑战。我们开发了一款增强的开源 LLM，旨在从自由文本中生成标准化的 LCS 报告。经过机构批准，我们对 5,442 份去识别化的 LCS 报告进行了分析，并随机选择了 500 份进行手动标注。两位放射科医生设计了一个包含 29 个特征的标准化模板。我们提出了模板约束解码技术，显著提升了 LLAMA、Qwen 和 Mistral 等开源 LLM 的性能。通过 F1 分数、置信区间等多项测试，我们的方法在多机构数据集上表现优异，无格式错误或内容幻觉，性能提升高达 10.42%，超越了 GPT-4o。此外，我们成功原型化了一个结节检索系统，并在大规模多模态数据库上进行了演示，自动统计结果与先前研究高度一致。

> Structured radiology reporting is advantageous for optimizing clinical workflows and patient outcomes. Current LLMs in creating structured reports face the challenges of formatting errors, content hallucinations, and privacy leakage concerns when uploaded to external servers. We aim to develop an enhanced open-source LLM for creating structured and standardized LCS reports from free-text descriptions. After institutional IRB approvals, 5,442 de-identified LCS reports from two institutions were retrospectively analyzed. 500 reports were randomly selected from the two institutions evenly and then manually labeled for evaluation. Two radiologists from the two institutions developed a standardized template including 29 features for lung nodule reporting. We proposed template-constrained decoding to enhance state-of-the-art open-source LLMs, including LLAMA, Qwen, and Mistral. The LLM performance was extensively evaluated in terms of F1 score, confidence interval, McNemar test, and z-test. Based on the structured reports created from the large-scale dataset, a nodule-level retrieval system was prototyped and an automatic statistical analysis was performed. Our software, vLLM-structure, is publicly available for local deployment with enhanced LLMs. Our template-constrained decoding approach consistently enhanced the LLM performance on multi-institutional datasets, with neither formatting errors nor content hallucinations. Our method improved the best open-source LLAMA-3.1 405B by up to 10.42%, and outperformed GPT-4o by 17.19%. A novel nodule retrieval system was successfully prototyped and demonstrated on a large-scale multimodal database using our enhanced LLM technologies. The automatically derived statistical distributions were closely consistent with the prior findings in terms of nodule type, location, size, status, and Lung-RADS.

[Arxiv](https://arxiv.org/abs/2409.18319)