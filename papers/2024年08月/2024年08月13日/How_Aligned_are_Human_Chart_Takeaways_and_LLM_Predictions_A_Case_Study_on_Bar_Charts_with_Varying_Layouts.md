# 探究人类对图表的解读与LLM预测的一致性，通过不同布局条形图的案例深入分析。

发布时间：2024年08月13日

`LLM应用` `数据可视化` `人工智能`

> How Aligned are Human Chart Takeaways and LLM Predictions? A Case Study on Bar Charts with Varying Layouts

# 摘要

> 大型语言模型（LLM）虽已广泛应用于可视化任务，但其预测人类视觉收获的能力仍待提升。研究表明，人类对图表的解读受设计细节（如布局）影响显著。本研究以条形图为例，探讨LLM在不同布局下的表现。我们通过三组实验，测试了四种条形图布局，发现即使是最先进的LLM也难以准确、多样地解读图表。进一步实验显示，LLM在零-shot和one-shot设置下的解读与人类存在差异。此外，LLM对同一布局下不同图表的解读也表现出不一致性。总体而言，本研究揭示了LLM在模拟人类数据解读方面的局限与潜力，为未来发展指明了方向。

> Large Language Models (LLMs) have been adopted for a variety of visualizations tasks, but how far are we from perceptually aware LLMs that can predict human takeaways? Graphical perception literature has shown that human chart takeaways are sensitive to visualization design choices, such as spatial layouts. In this work, we examine the extent to which LLMs exhibit such sensitivity when generating takeaways, using bar charts with varying spatial layouts as a case study. We conducted three experiments and tested four common bar chart layouts: vertically juxtaposed, horizontally juxtaposed, overlaid, and stacked. In Experiment 1, we identified the optimal configurations to generate meaningful chart takeaways by testing four LLMs, two temperature settings, nine chart specifications, and two prompting strategies. We found that even state-of-the-art LLMs struggled to generate semantically diverse and factually accurate takeaways. In Experiment 2, we used the optimal configurations to generate 30 chart takeaways each for eight visualizations across four layouts and two datasets in both zero-shot and one-shot settings. Compared to human takeaways, we found that the takeaways LLMs generated often did not match the types of comparisons made by humans. In Experiment 3, we examined the effect of chart context and data on LLM takeaways. We found that LLMs, unlike humans, exhibited variation in takeaway comparison types for different bar charts using the same bar layout. Overall, our case study evaluates the ability of LLMs to emulate human interpretations of data and points to challenges and opportunities in using LLMs to predict human chart takeaways.

[Arxiv](https://arxiv.org/abs/2408.06837)