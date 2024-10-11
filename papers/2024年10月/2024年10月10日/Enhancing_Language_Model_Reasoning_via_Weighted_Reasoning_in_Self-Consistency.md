# 借助自一致性中的加权推理，提升语言模型的推理能力

发布时间：2024年10月10日

`LLM理论` `人工智能`

> Enhancing Language Model Reasoning via Weighted Reasoning in Self-Consistency

# 摘要

> 尽管 LLM 在多项任务中表现出色，但在推理任务上仍有不足。随着 LLM 在实际应用中的普及，提升其推理能力显得尤为重要。Wang 等提出的自洽性框架通过采样多个理由并在多数投票前进行分析，有效提升了模型在封闭答案推理任务中的表现。然而，现有方法仅汇总最终决策，忽略了详细的推理路径。我们的研究则进一步整合并分析了这些推理路径及其最终决策，不仅增强了推理路径的可靠性，还显著提升了模型在复杂推理任务中的表现。

> While large language models (LLMs) have rapidly improved their performance on a broad number of tasks, they still often fall short on reasoning tasks. As LLMs become more integrated in diverse real-world tasks, advancing their reasoning capabilities is crucial to their effectiveness in nuanced, complex problems. Wang et al's self-consistency framework reveals that sampling multiple rationales before taking a majority vote reliably improves model performance across various closed-answer reasoning tasks. Standard methods based on this framework aggregate the final decisions of these rationales but fail to utilize the detailed step-by-step reasoning paths applied by these paths. Our work enhances this approach by incorporating and analyzing both the reasoning paths of these rationales in addition to their final decisions before taking a majority vote. These methods not only improve the reliability of reasoning paths but also cause more robust performance on complex reasoning tasks.

[Arxiv](https://arxiv.org/abs/2410.07839)