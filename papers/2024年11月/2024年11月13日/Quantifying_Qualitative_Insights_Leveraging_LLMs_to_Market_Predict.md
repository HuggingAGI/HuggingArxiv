# 量化定性见解：利用大型语言模型进行市场预测

发布时间：2024年11月13日

`LLM应用` `市场预测`

> Quantifying Qualitative Insights: Leveraging LLMs to Market Predict

# 摘要

> 大型语言模型（LLM）的最新进展有可能通过整合数字和文本数据来改变金融分析。然而，在融合多模态信息时上下文不足以及难以衡量 LLM 以文本形式生成的定性输出的效用等挑战，限制了它们在金融预测等任务中的有效性。本研究通过利用证券公司的日报来创建高质量的上下文信息来应对这些挑战。这些报告被分割为基于文本的关键因素，并与价格信息等数字数据相结合，形成上下文集。通过根据查询时间动态更新少样本示例，这些集合纳入了最新信息，形成了与查询点高度相关的集合。此外，还设计了一个精心制作的提示，为关键因素分配分数，将定性见解转化为定量结果。得出的分数经过缩放过程，将其转化为用于预测的实际值。我们的实验表明，LLM 在市场预测方面优于时间序列模型，尽管仍然存在诸如不完全可重复性和有限可解释性等挑战。

> Recent advancements in Large Language Models (LLMs) have the potential to transform financial analytics by integrating numerical and textual data. However, challenges such as insufficient context when fusing multimodal information and the difficulty in measuring the utility of qualitative outputs, which LLMs generate as text, have limited their effectiveness in tasks such as financial forecasting. This study addresses these challenges by leveraging daily reports from securities firms to create high-quality contextual information. The reports are segmented into text-based key factors and combined with numerical data, such as price information, to form context sets. By dynamically updating few-shot examples based on the query time, the sets incorporate the latest information, forming a highly relevant set closely aligned with the query point. Additionally, a crafted prompt is designed to assign scores to the key factors, converting qualitative insights into quantitative results. The derived scores undergo a scaling process, transforming them into real-world values that are used for prediction. Our experiments demonstrate that LLMs outperform time-series models in market forecasting, though challenges such as imperfect reproducibility and limited explainability remain.

[Arxiv](https://arxiv.org/abs/2411.08404)