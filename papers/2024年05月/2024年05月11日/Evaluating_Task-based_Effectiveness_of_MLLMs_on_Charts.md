# 探究多模态大型语言模型在图表任务中的实际效能。

发布时间：2024年05月11日

`LLM应用

这篇论文聚焦于GPT-4V在图表低级数据分析任务中的应用，通过创建大规模数据集ChartInsights，并评估多个先进的MLLMs模型，展示了GPT-4V在这一领域的性能。论文还探讨了模型在特定任务中的局限性，并提出了改进策略，如Chain-of-Charts文本提示策略，以提升准确率。这些内容表明该论文属于大型语言模型（LLM）的应用研究范畴，而非Agent、RAG或LLM理论分类。` `数据分析` `人工智能`

> Evaluating Task-based Effectiveness of MLLMs on Charts

# 摘要

> 本文深入探讨了GPT-4V在图表低级数据分析任务中的效能。我们创建了名为ChartInsights的大规模数据集，包含近9万组图表分析案例，覆盖了7大类图表的10种分析任务。通过系统评估18个先进的MLLMs（包括开源和闭源模型），我们发现GPT-4V以56.13%的准确率领先，远超平均水平36.17%。为了深入了解GPT-4V在低级数据分析中的局限，我们设计了一系列实验，并研究了图表视觉元素变化对GPT-4V性能的影响。我们总结了12项实验发现，揭示了GPT-4V在图表交互方面的革新潜力，同时也指出了与人类分析需求之间的差距。为了提升性能，我们提出了名为Chain-of-Charts的新型文本提示策略，将准确率提升至80.49%，并通过视觉提示策略进一步提高至83.83%。我们的研究不仅揭示了GPT-4V在低级数据分析中的能力和局限，也为未来研究提供了重要启示。

> In this paper, we explore a forward-thinking question: Is GPT-4V effective at low-level data analysis tasks on charts? To this end, we first curate a large-scale dataset, named ChartInsights, consisting of 89,388 quartets (chart, task, question, answer) and covering 10 widely-used low-level data analysis tasks on 7 chart types. Firstly, we conduct systematic evaluations to understand the capabilities and limitations of 18 advanced MLLMs, which include 12 open-source models and 6 closed-source models. Starting with a standard textual prompt approach, the average accuracy rate across the 18 MLLMs is 36.17%. Among all the models, GPT-4V achieves the highest accuracy, reaching 56.13%. To understand the limitations of multimodal large models in low-level data analysis tasks, we have designed various experiments to conduct an in-depth test of capabilities of GPT-4V. We further investigate how visual modifications to charts, such as altering visual elements (e.g. changing color schemes) and introducing perturbations (e.g. adding image noise), affect performance of GPT-4V. Secondly, we present 12 experimental findings. These findings suggest potential of GPT-4V to revolutionize interaction with charts and uncover the gap between human analytic needs and capabilities of GPT-4V. Thirdly, we propose a novel textual prompt strategy, named Chain-of-Charts, tailored for low-level analysis tasks, which boosts model performance by 24.36%, resulting in an accuracy of 80.49%. Furthermore, by incorporating a visual prompt strategy that directs attention of GPT-4V to question-relevant visual elements, we further improve accuracy to 83.83%. Our study not only sheds light on the capabilities and limitations of GPT-4V in low-level data analysis tasks but also offers valuable insights for future research.

[Arxiv](https://arxiv.org/abs/2405.07001)