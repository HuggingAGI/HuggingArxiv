# LLM 辅助的相关性评估：我们什么时候应该向 LLM 寻求帮助？

发布时间：2024年11月11日

`LLM应用` `信息检索` `测试集合`

> LLM-Assisted Relevance Assessments: When Should We Ask LLMs for Help?

# 摘要

> 测试集合是信息检索工具，允许研究人员快速轻松地评估排名算法。虽然测试集合已成为信息检索研究不可或缺的一部分，但数据创建过程涉及大量的人工注释工作，这往往使其非常昂贵和耗时。因此，当预算有限时，测试集合可能会变小，这可能导致评估不稳定。作为替代方案，最近的研究提出使用大型语言模型（LLM）完全取代人工评估员。然而，虽然 LLM 似乎与人类判断有一定的相关性，但它们并不完美，并且经常表现出偏差。此外，即使在一个数据集上找到了表现良好的 LLM 或提示，由于任务和数据的差异，也不能保证它在实际中表现相似。因此，完全用 LLM 替代被认为风险太大且不完全可信。

因此，在本文中，我们提出了\(	extbf{L}\)LM-\(	extbf{A}\)ssisted \(	extbf{R}\)elevance \(	extbf{A}\)ssessments（\(	extbf{LARA}\)），这是一种平衡人工注释和 LLM 注释的有效方法，有助于创建丰富可靠的测试集合。我们使用 LLM 预测的相关性概率，以便在预算限制下选择最有利可图的文档进行人工注释。虽然仅仅依靠 LLM 预测的概率进行人工注释表现相当不错，但通过理论推理，LARA 通过在线校准学习更有效地指导人工注释过程。然后，使用从有限的人工注释中学习到的校准模型，LARA 对 LLM 预测进行去偏，以注释其余未评估的数据。在 TREC-COVID 和 TREC-8 Ad Hoc 数据集上的实证评估表明，LARA 在几乎任何预算限制下都优于替代解决方案。

> Test collections are information retrieval tools that allow researchers to quickly and easily evaluate ranking algorithms. While test collections have become an integral part of IR research, the process of data creation involves significant efforts in manual annotations, which often makes it very expensive and time-consuming. Thus, the test collections could become small when the budget is limited, which may lead to unstable evaluations. As an alternative, recent studies have proposed the use of large language models (LLMs) to completely replace human assessors. However, while LLMs seem to somewhat correlate with human judgments, they are not perfect and often show bias. Moreover, even if a well-performing LLM or prompt is found on one dataset, there is no guarantee that it will perform similarly in practice, due to difference in tasks and data. Thus a complete replacement with LLMs is argued to be too risky and not fully trustable.
  Thus, in this paper, we propose \textbf{L}LM-\textbf{A}ssisted \textbf{R}elevance \textbf{A}ssessments (\textbf{LARA}), an effective method to balance manual annotations with LLM annotations, which helps to make a rich and reliable test collection. We use the LLM's predicted relevance probabilities in order to select the most profitable documents to manually annotate under a budget constraint. While solely relying on LLM's predicted probabilities to manually annotate performs fairly well, with theoretical reasoning, LARA guides the human annotation process even more effectively via online calibration learning. Then, using the calibration model learned from the limited manual annotations, LARA debiases the LLM predictions to annotate the remaining non-assessed data. Empirical evaluations on TREC-COVID and TREC-8 Ad Hoc datasets show that LARA outperforms the alternative solutions under almost any budget constraint.

[Arxiv](https://arxiv.org/abs/2411.06877)