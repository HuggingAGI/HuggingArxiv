# HateGPT：让 GPT-3.5 Turbo 出马，在 X 平台上对抗仇恨言论

发布时间：2024年11月14日

`LLM应用` `社交媒体` `内容检测`

> HateGPT: Unleashing GPT-3.5 Turbo to Combat Hate Speech on X

# 摘要

> 推特、脸书等社交媒体平台的广泛运用，让各年龄段的人都能分享想法与经历，致使用户生成的内容大量积聚。然而，在带来好处的同时，这些平台也面临着管理仇恨言论和冒犯性内容的难题，这可能会破坏理性交流，威胁民主价值。所以，检测和减少这类内容的自动化方法需求愈发迫切，特别是考虑到对话的复杂性，可能需要对包括印式英语、德英混合语、孟加拉语等代码混合语言在内的多种语言进行上下文分析。我们参与了英语任务，要把英语推文分为仇恨冒犯类和非仇恨冒犯类。在这项工作中，我们通过提示，运用像 GPT-3.5 Turbo 这样的先进大型语言模型对推文进行上述分类。在本研究中，我们通过三次不同的运行，用宏观 F1 分数来评估分类模型的性能。宏观 F1 分数能平衡所有类别的精度和召回率，是模型评估的主要指标。运行 1 的分数是 0.756，运行 2 是 0.751，运行 3 是 0.754，表明性能水平较高，各次运行差异较小。结果显示，该模型在精度和召回率方面一直表现出色，运行 1 的表现最佳。这些发现凸显了该模型在不同运行中的稳健性和可靠性。

> The widespread use of social media platforms like Twitter and Facebook has enabled people of all ages to share their thoughts and experiences, leading to an immense accumulation of user-generated content. However, alongside the benefits, these platforms also face the challenge of managing hate speech and offensive content, which can undermine rational discourse and threaten democratic values. As a result, there is a growing need for automated methods to detect and mitigate such content, especially given the complexity of conversations that may require contextual analysis across multiple languages, including code-mixed languages like Hinglish, German-English, and Bangla. We participated in the English task where we have to classify English tweets into two categories namely Hate and Offensive and Non Hate-Offensive. In this work, we experiment with state-of-the-art large language models like GPT-3.5 Turbo via prompting to classify tweets into Hate and Offensive or Non Hate-Offensive. In this study, we evaluate the performance of a classification model using Macro-F1 scores across three distinct runs. The Macro-F1 score, which balances precision and recall across all classes, is used as the primary metric for model evaluation. The scores obtained are 0.756 for run 1, 0.751 for run 2, and 0.754 for run 3, indicating a high level of performance with minimal variance among the runs. The results suggest that the model consistently performs well in terms of precision and recall, with run 1 showing the highest performance. These findings highlight the robustness and reliability of the model across different runs.

[Arxiv](https://arxiv.org/abs/2411.09214)