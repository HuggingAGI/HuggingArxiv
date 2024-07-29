# 揭秘评分机制：深入探究大型语言模型与人类评分者在自动评分领域的不同表现

发布时间：2024年07月04日

`LLM应用`

> Unveiling Scoring Processes: Dissecting the Differences between LLMs and Human Graders in Automatic Scoring

# 摘要

> 大型语言模型（LLM）在自动评分领域展现出巨大潜力，尤其是在处理构建响应评估时。然而，LLM的评分机制仍是个谜，我们也不清楚其评分过程是否与人类一致。本文旨在揭秘LLM使用的评分标准，并探讨其与人类评分的契合度。我们通过让LLM生成评分标准，分析其与人类标准的差异。实验表明，尽管LLM能迅速适应评分任务，但它们常采用捷径，忽略了人类评分中的深度逻辑推理。引入高质量的分析性评分标准，能有效缩小这一差距，提升评分准确性。这提醒我们，在科学教育中应用LLM时需谨慎，确保其输出与人类期望一致，以实现高效准确的自动评分。

> Large language models (LLMs) have demonstrated strong potential in performing automatic scoring for constructed response assessments. While constructed responses graded by humans are usually based on given grading rubrics, the methods by which LLMs assign scores remain largely unclear. It is also uncertain how closely AI's scoring process mirrors that of humans, or if it adheres to the same grading criteria. To address this gap, this paper uncovers the grading rubrics that LLMs used to score students' written responses to science tasks and their alignment with human scores. We also examine whether enhancing the alignments can improve scoring accuracy. Specifically, we prompt LLMs to generate analytic rubrics that they use to assign scores and study the alignment gap with human grading rubrics. Based on a series of experiments with various configurations of LLM settings, we reveal a notable alignment gap between human and LLM graders. While LLMs can adapt quickly to scoring tasks, they often resort to shortcuts, bypassing deeper logical reasoning expected in human grading. We found that incorporating high-quality analytical rubrics designed to reflect human grading logic can mitigate this gap and enhance LLMs' scoring accuracy. These results caution against the simplistic application of LLMs in science education and highlight the importance of aligning LLM outputs with human expectations to ensure efficient and accurate automatic scoring.

[Arxiv](https://arxiv.org/abs/2407.18328)