# 将特定领域的模型与LLMs相融合，以实现从调查数据中对疾病表型的自动分析

发布时间：2024年10月27日

`LLM应用` `生物医学`

> Combining Domain-Specific Models and LLMs for Automated Disease Phenotyping from Survey Data

# 摘要

> 这项探索性试点研究探究了将特定领域模型 BERN2 与大型语言模型（LLMs）相结合的可能性，旨在从研究调查数据中强化自动疾病表型分析。鉴于需要高效且准确的方法来协调日益增多的调查数据与标准化疾病本体，我们运用了生物医学命名实体识别和规范化模型 BERN2，从 ORIGINS 出生队列调查数据中提取疾病信息。在针对人工整理的真实数据集严格评估 BERN2 的性能后，我们借助提示工程、检索增强生成（RAG）和指令微调（IFT）整合了各类 LLMs 以优化模型输出。BERN2 在提取和规范疾病表述方面表现优异，而 LLMs 的整合，尤其是与少量样本推理和 RAG 编排相结合，进一步提升了准确性。这种方法，尤其是在融入结构化示例、逻辑推理提示和详细上下文时，为开发能够在大型、异构研究数据集中实现有效队列分析和数据协调的工具提供了一条充满希望的途径。

> This exploratory pilot study investigated the potential of combining a domain-specific model, BERN2, with large language models (LLMs) to enhance automated disease phenotyping from research survey data. Motivated by the need for efficient and accurate methods to harmonize the growing volume of survey data with standardized disease ontologies, we employed BERN2, a biomedical named entity recognition and normalization model, to extract disease information from the ORIGINS birth cohort survey data. After rigorously evaluating BERN2's performance against a manually curated ground truth dataset, we integrated various LLMs using prompt engineering, Retrieval-Augmented Generation (RAG), and Instructional Fine-Tuning (IFT) to refine the model's outputs. BERN2 demonstrated high performance in extracting and normalizing disease mentions, and the integration of LLMs, particularly with Few Shot Inference and RAG orchestration, further improved accuracy. This approach, especially when incorporating structured examples, logical reasoning prompts, and detailed context, offers a promising avenue for developing tools to enable efficient cohort profiling and data harmonization across large, heterogeneous research datasets.

[Arxiv](https://arxiv.org/abs/2410.20695)