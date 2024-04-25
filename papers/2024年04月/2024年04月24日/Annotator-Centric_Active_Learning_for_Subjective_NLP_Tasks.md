# 以标注者为中心的主动学习策略，应用于主观性自然语言处理任务。

发布时间：2024年04月24日

`分类：LLM应用` `人工智能`

> Annotator-Centric Active Learning for Subjective NLP Tasks

# 摘要

> 为了精确反映主观性NLP任务中人的判断差异，纳入多元视角进行标注非常关键。主动学习（AL）通过精心选择最具信息价值的样本进行标注，有效降低了人工标注的成本。我们提出了一种新的主动学习方法——以标注者为中心的主动学习（ACAL），它在数据选择后引入了标注者选择策略。我们的目标是双重的：一方面，高效地模拟出人类判断的全面多样性；另一方面，通过重视少数派观点的标注者中心指标来评估模型的表现。我们在七个不同的主观性NLP任务中测试了多种标注者选择策略，并采用了传统和创新的、以人为本的评估标准。研究结果显示，ACAL在提升数据使用效率和标注者中心的性能评估方面表现优异。然而，其成效依赖于能否获取一个足够大且多样化的标注者群体作为抽样来源。

> To accurately capture the variability in human judgments for subjective NLP tasks, incorporating a wide range of perspectives in the annotation process is crucial. Active Learning (AL) addresses the high costs of collecting human annotations by strategically annotating the most informative samples. We introduce Annotator-Centric Active Learning (ACAL), which incorporates an annotator selection strategy following data sampling. Our objective is two-fold: (1) to efficiently approximate the full diversity of human judgments, and to assess model performance using annotator-centric metrics, which emphasize minority perspectives over a majority. We experiment with multiple annotator selection strategies across seven subjective NLP tasks, employing both traditional and novel, human-centered evaluation metrics. Our findings indicate that ACAL improves data efficiency and excels in annotator-centric performance evaluations. However, its success depends on the availability of a sufficiently large and diverse pool of annotators to sample from.

[Arxiv](https://arxiv.org/abs/2404.15720)