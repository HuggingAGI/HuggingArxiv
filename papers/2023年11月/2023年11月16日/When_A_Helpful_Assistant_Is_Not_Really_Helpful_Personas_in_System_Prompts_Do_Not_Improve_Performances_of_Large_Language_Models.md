# 当“一个有帮助的助手”并非真的有帮助：系统提示中的角色设定并不能提高大型语言模型的性能。

发布时间：2023年11月16日

`LLM应用` `人工智能`

> When "A Helpful Assistant" Is Not Really Helpful: Personas in System Prompts Do Not Improve Performances of Large Language Models

# 摘要

> 摘要：提示是人类与大型语言模型（LLM）互动的主要方式。商业人工智能系统通常在系统提示中定义 LLM 的角色。例如，ChatGPT 将“你是一个乐于助人的助手”作为其默认系统提示的一部分。尽管目前在系统提示中添加角色的做法很常见，但不同角色如何影响模型在客观任务上的表现仍不清楚。在这项研究中，我们对系统提示中的角色进行了系统评估。我们整理了一份涵盖 6 种人际关系和 8 个专业领域的 162 个角色的列表。通过对 4 个流行的 LLM 家族和 2410 个事实问题的广泛分析，我们表明，与不添加角色的对照设置相比，在系统提示中添加角色并不能提高模型在一系列问题上的性能。然而，进一步的分析表明，角色的性别、类型和领域都可以影响最终的预测准确率。我们进一步试验了一系列角色搜索策略，发现虽然对每个问题从最佳角色聚合结果显著提高了预测准确率，但自动识别最佳角色具有挑战性，预测效果往往不比随机选择好。总的来说，我们的研究结果表明，虽然添加角色在某些情况下可能会带来性能提升，但每个角色的效果在很大程度上是随机的。代码和数据可在这个 https 网址获取。

> 
Abstract:Prompting serves as the major way humans interact with Large Language Models (LLM). Commercial AI systems commonly define the role of the LLM in system prompts. For example, ChatGPT uses ``You are a helpful assistant'' as part of its default system prompt. Despite current practices of adding personas to system prompts, it remains unclear how different personas affect a model's performance on objective tasks. In this study, we present a systematic evaluation of personas in system prompts. We curate a list of 162 roles covering 6 types of interpersonal relationships and 8 domains of expertise. Through extensive analysis of 4 popular families of LLMs and 2,410 factual questions, we demonstrate that adding personas in system prompts does not improve model performance across a range of questions compared to the control setting where no persona is added. Nevertheless, further analysis suggests that the gender, type, and domain of the persona can all influence the resulting prediction accuracies. We further experimented with a list of persona search strategies and found that, while aggregating results from the best persona for each question significantly improves prediction accuracy, automatically identifying the best persona is challenging, with predictions often performing no better than random selection. Overall, our findings suggest that while adding a persona may lead to performance gains in certain settings, the effect of each persona can be largely random. Code and data are available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2311.10054)