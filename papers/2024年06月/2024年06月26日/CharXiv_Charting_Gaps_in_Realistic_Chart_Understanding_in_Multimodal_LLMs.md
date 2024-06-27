# CharXiv：揭示多模态LLMs在现实图表理解上的盲点

发布时间：2024年06月26日

`LLM应用

这篇论文主要关注多模态大型语言模型（MLLMs）在实际任务中的应用，特别是在图表理解方面的挑战和评估。论文通过介绍一个新的评估平台CharXiv，旨在提供更真实的评估环境，以推动MLLM在图表理解方面的发展。这表明论文的重点在于应用层面，即如何改进和评估MLLMs在特定任务（如科学论文或财务报告分析中的图表理解）中的表现，因此属于LLM应用分类。` `科学研究` `财务分析`

> CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs

# 摘要

> 在应用多模态大型语言模型（MLLMs）于实际任务，如科学论文或财务报告分析时，图表理解至关重要。但现有数据集多聚焦于简化且单一的图表和模板问题，导致对进展的评估过于乐观。我们发现，开源模型虽在基准测试中表现出色，但面对稍有变化的图表或问题，性能可能骤降34.5%。为此，我们推出了CharXiv，一个包含2,323个来自arXiv的复杂多样图表的评估平台。CharXiv涵盖两类问题：描述性问题关注图表基础元素，推理问题则需整合复杂视觉信息。所有内容均由专家精心筛选和验证。结果显示，最强专有模型（如GPT-4o）的推理准确率为47.1%，而最强开源模型（如InternVL Chat V1.5）为29.2%，均远低于人类80.5%的水平，揭示了MLLMs在图表理解上的短板。我们期待CharXiv能通过提供更真实的评估，推动MLLM图表理解研究的发展。项目详情及排行榜请访问：https://charxiv.github.io/

> Chart understanding plays a pivotal role when applying Multimodal Large Language Models (MLLMs) to real-world tasks such as analyzing scientific papers or financial reports. However, existing datasets often focus on oversimplified and homogeneous charts with template-based questions, leading to an over-optimistic measure of progress. We demonstrate that although open-source models can appear to outperform strong proprietary models on these benchmarks, a simple stress test with slightly different charts or questions can deteriorate performance by up to 34.5%. In this work, we propose CharXiv, a comprehensive evaluation suite involving 2,323 natural, challenging, and diverse charts from arXiv papers. CharXiv includes two types of questions: 1) descriptive questions about examining basic chart elements and 2) reasoning questions that require synthesizing information across complex visual elements in the chart. To ensure quality, all charts and questions are handpicked, curated, and verified by human experts. Our results reveal a substantial, previously underestimated gap between the reasoning skills of the strongest proprietary model (i.e., GPT-4o), which achieves 47.1% accuracy, and the strongest open-source model (i.e., InternVL Chat V1.5), which achieves 29.2%. All models lag far behind human performance of 80.5%, underscoring weaknesses in the chart understanding capabilities of existing MLLMs. We hope CharXiv facilitates future research on MLLM chart understanding by providing a more realistic and faithful measure of progress. Project page and leaderboard: https://charxiv.github.io/

[Arxiv](https://arxiv.org/abs/2406.18521)