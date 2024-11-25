# RoBIn：一个基于 Transformer 的、用于借助机器阅读理解进行偏差风险推断的模型

发布时间：2024年10月28日

`LLM应用` `机器阅读理解`

> RoBIn: A Transformer-Based Model For Risk Of Bias Inference With Machine Reading Comprehension

# 摘要

> 目标：科学出版物在挖掘见解、测试新药以及塑造医疗保健政策方面起着关键作用。要获取出版物的质量，就得评估其偏倚风险（RoB），这通常由人工评审员操作。在本研究中，我们引入了一个用于机器阅读理解和RoB评估的新数据集，并推出RoBIn（偏倚风险推断）这一创新模型，旨在实现此类评估的自动化。该模型运用双任务方式，从给定的情境中提取证据，并依据所收集的证据评估RoB。方法：我们以Cochrane系统评价数据库（CDSR）的数据为基准，对来自PubMed的开放获取临床试验出版物进行标注。通过这一流程，我们得以专门为机器阅读理解和RoB推断开发训练及测试数据集。此外，我们创建了基于提取（RoBInExt）和生成（RoBInGen）的Transformer方法，以有效提取相关证据并对RoB进行分类。结果：RoBIn在各种设定下接受评估，并与包括多种场景中的大型语言模型在内的RoB推断前沿方法进行对比。在多数情况下，表现最优的RoBIn变体超越了传统机器学习和基于LLM的方法，达成了0.83的ROC AUC。结论：基于从临床试验报告中提取的证据，RoBIn进行二分类，判定试验处于低RoB还是高/不明确RoB。我们发现RoBInGen和RoBInExt都很可靠，在众多设定中均有最佳表现。

> Objective: Scientific publications play a crucial role in uncovering insights, testing novel drugs, and shaping healthcare policies. Accessing the quality of publications requires evaluating their Risk of Bias (RoB), a process typically conducted by human reviewers. In this study, we introduce a new dataset for machine reading comprehension and RoB assessment and present RoBIn (Risk of Bias Inference), an innovative model crafted to automate such evaluation. The model employs a dual-task approach, extracting evidence from a given context and assessing the RoB based on the gathered evidence. Methods: We use data from the Cochrane Database of Systematic Reviews (CDSR) as ground truth to label open-access clinical trial publications from PubMed. This process enabled us to develop training and test datasets specifically for machine reading comprehension and RoB inference. Additionally, we created extractive (RoBInExt) and generative (RoBInGen) Transformer-based approaches to extract relevant evidence and classify the RoB effectively. Results: RoBIn is evaluated across various settings and benchmarked against state-of-the-art methods for RoB inference, including large language models in multiple scenarios. In most cases, the best-performing RoBIn variant surpasses traditional machine learning and LLM-based approaches, achieving an ROC AUC of 0.83. Conclusion: Based on the evidence extracted from clinical trial reports, RoBIn performs a binary classification to decide whether the trial is at a low RoB or a high/unclear RoB. We found that both RoBInGen and RoBInExt are robust and have the best results in many settings.

[Arxiv](https://arxiv.org/abs/2410.21495)