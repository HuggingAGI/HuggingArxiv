# SDoH-GPT：运用大型语言模型，精准提取健康社会决定因素。

发布时间：2024年07月24日

`LLM应用` `社会科学`

> SDoH-GPT: Using Large Language Models to Extract Social Determinants of Health (SDoH)

# 摘要

> 提取非结构化医疗笔记中的健康社会决定因素（SDoH）传统上依赖于劳动密集型的任务特定标注，这限制了其可重用性和共享性。本研究提出的SDoH-GPT方法，通过对比示例和简洁指令，实现了无需广泛医疗标注或人工干预的高效SDoH提取。该方法在时间和成本上分别大幅减少了十倍和二十倍，且与人类标注者的一致性高达0.92的Cohen's kappa。SDoH-GPT与XGBoost的结合，不仅保证了高准确性和计算效率，还持续保持了0.90+的AUROC分数。跨三个数据集的测试验证了其稳健性和准确性。本研究展示了LLM在革新医疗笔记分类方面的巨大潜力，能够在大幅降低时间和成本的同时，实现高度准确的分类。

> Extracting social determinants of health (SDoH) from unstructured medical notes depends heavily on labor-intensive annotations, which are typically task-specific, hampering reusability and limiting sharing. In this study we introduced SDoH-GPT, a simple and effective few-shot Large Language Model (LLM) method leveraging contrastive examples and concise instructions to extract SDoH without relying on extensive medical annotations or costly human intervention. It achieved tenfold and twentyfold reductions in time and cost respectively, and superior consistency with human annotators measured by Cohen's kappa of up to 0.92. The innovative combination of SDoH-GPT and XGBoost leverages the strengths of both, ensuring high accuracy and computational efficiency while consistently maintaining 0.90+ AUROC scores. Testing across three distinct datasets has confirmed its robustness and accuracy. This study highlights the potential of leveraging LLMs to revolutionize medical note classification, demonstrating their capability to achieve highly accurate classifications with significantly reduced time and cost.

[Arxiv](https://arxiv.org/abs/2407.17126)