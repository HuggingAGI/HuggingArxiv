# 语言模型与检索增强生成技术联手，自动从诊断报告中提取结构化数据。

发布时间：2024年09月15日

`LLM应用` `人工智能`

> Language Models and Retrieval Augmented Generation for Automated Structured Data Extraction from Diagnostic Reports

# 摘要

> 本研究旨在开发并评估一个自动化系统，利用开放权重的大型语言模型（LMs）和检索增强生成（RAG），从非结构化的放射学和病理学报告中提取结构化的临床信息。我们使用了两个标注数据集：7,294份放射学报告和2,154份病理学报告。通过自动化管道，我们系统评估了模型大小、量化、提示策略等因素对提取性能的影响。结果显示，最佳模型在提取BT-RADS评分和IDH突变状态时的准确率分别超过98%和90%。经过医学微调的llama3表现尤为突出。研究发现，更大、更新的领域微调模型性能更优，而模型量化对性能影响甚微。少样本提示显著提升了准确性，RAG则对复杂病理学报告的性能有所提升。结论指出，开放LMs在自动化提取临床数据方面潜力巨大，且在本地隐私保护应用中表现出色。精心选择模型、优化提示策略及半自动化优化是实现最佳性能的关键。这些方法在研究工作流程中具有实际应用价值，为人机协作在医疗数据提取中的应用提供了新视角。

> Purpose: To develop and evaluate an automated system for extracting structured clinical information from unstructured radiology and pathology reports using open-weights large language models (LMs) and retrieval augmented generation (RAG), and to assess the effects of model configuration variables on extraction performance. Methods and Materials: The study utilized two datasets: 7,294 radiology reports annotated for Brain Tumor Reporting and Data System (BT-RADS) scores and 2,154 pathology reports annotated for isocitrate dehydrogenase (IDH) mutation status. An automated pipeline was developed to benchmark the performance of various LMs and RAG configurations. The impact of model size, quantization, prompting strategies, output formatting, and inference parameters was systematically evaluated. Results: The best performing models achieved over 98% accuracy in extracting BT-RADS scores from radiology reports and over 90% for IDH mutation status extraction from pathology reports. The top model being medical fine-tuned llama3. Larger, newer, and domain fine-tuned models consistently outperformed older and smaller models. Model quantization had minimal impact on performance. Few-shot prompting significantly improved accuracy. RAG improved performance for complex pathology reports but not for shorter radiology reports. Conclusions: Open LMs demonstrate significant potential for automated extraction of structured clinical data from unstructured clinical reports with local privacy-preserving application. Careful model selection, prompt engineering, and semi-automated optimization using annotated data are critical for optimal performance. These approaches could be reliable enough for practical use in research workflows, highlighting the potential for human-machine collaboration in healthcare data extraction.

[Arxiv](https://arxiv.org/abs/2409.10576)