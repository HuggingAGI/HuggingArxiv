# 自然语言解释的情境化场景与策略

发布时间：2024年06月07日

`LLM应用

这篇论文主要关注大型语言模型（LLMs）在生成适应不同用户情境的自然语言解释（NLE）方面的应用。论文通过引入Situation-Based Explanation数据集，并评估了不同预训练语言模型在生成情境化解释方面的表现，探讨了如何通过不同的提示方法（如基于规则的提示、元提示和情境学习提示）来提高LLMs生成解释的适应性。这些内容主要涉及LLMs的实际应用，特别是在教育和技术支持等领域的解释生成，因此属于LLM应用分类。`

> Scenarios and Approaches for Situated Natural Language Explanations

# 摘要

> 大型语言模型（LLMs）能生成适应不同用户情境的自然语言解释（NLE），但这种适应性的定量评估尚不完善。为此，我们推出了Situation-Based Explanation数据集，内含100个解释对象，每个对象都配有针对教育者、学生和专业人士的解释，便于评估这些解释在满足特定群体信息需求和情境方面的效果。我们为每种“解释对象配对受众”情况提供了人工编写的解释，并据此计算LLMs适应情境的得分。在多种预训练语言模型上，我们测试了基于规则的提示、元提示和情境学习提示三种方法，发现：1) 语言模型能生成更贴合目标情境的解释提示；2) 明确建模“助手”角色并非情境NLE任务的必要提示技巧；3) 情境学习提示虽能帮助LLMs学习演示模板，但未能提升推理性能。SBE数据集及我们的分析为未来研究情境化自然语言解释提供了基础。

> Large language models (LLMs) can be used to generate natural language explanations (NLE) that are adapted to different users' situations. However, there is yet to be a quantitative evaluation of the extent of such adaptation. To bridge this gap, we collect a benchmarking dataset, Situation-Based Explanation. This dataset contains 100 explanandums. Each explanandum is paired with explanations targeted at three distinct audience types-such as educators, students, and professionals-enabling us to assess how well the explanations meet the specific informational needs and contexts of these diverse groups e.g. students, teachers, and parents. For each "explanandum paired with an audience" situation, we include a human-written explanation. These allow us to compute scores that quantify how the LLMs adapt the explanations to the situations. On an array of pretrained language models with varying sizes, we examine three categories of prompting methods: rule-based prompting, meta-prompting, and in-context learning prompting. We find that 1) language models can generate prompts that result in explanations more precisely aligned with the target situations, 2) explicitly modeling an "assistant" persona by prompting "You are a helpful assistant..." is not a necessary prompt technique for situated NLE tasks, and 3) the in-context learning prompts only can help LLMs learn the demonstration template but can't improve their inference performance. SBE and our analysis facilitate future research towards generating situated natural language explanations.

![自然语言解释的情境化场景与策略](../../../paper_images/2406.05035/example.png)

![自然语言解释的情境化场景与策略](../../../paper_images/2406.05035/data_pie_chart.png)

![自然语言解释的情境化场景与策略](../../../paper_images/2406.05035/score_prompt.png)

![自然语言解释的情境化场景与策略](../../../paper_images/2406.05035/score_model.png)

![自然语言解释的情境化场景与策略](../../../paper_images/2406.05035/similarity_heatmap.png)

![自然语言解释的情境化场景与策略](../../../paper_images/2406.05035/matchness_heatmap.png)

[Arxiv](https://arxiv.org/abs/2406.05035)