# 《在推理中迷失：重新探寻自然语言推理于大型语言模型的角色》

发布时间：2024年11月21日

`LLM应用` `模型评估`

> Lost in Inference: Rediscovering the Role of Natural Language Inference for Large Language Models

# 摘要

> 在不久前，评估自然语言理解（NLU）的常见方式是考量模型执行自然语言推理（NLI）任务的能力。在本文中，我们探究了鲜少用于 LLM 评估的 NLI 任务，对评估 LLM 是否仍具意义。针对六个不同规模模型的五个 NLI 基准，我们研究它们能否区分不同大小和质量的模型，以及其准确率在训练过程中的变化情况。另外，我们还探究了在陈述含混或模糊时，模型的 softmax 分布与人类分布的契合程度。总的来说，我们的研究结果为 NLI 任务呈现出积极态势：我们发现它们能有效区分处于不同训练阶段的模型，但并非（全部）达到饱和。而且，我们发现虽然模型分布与人类标签分布的相似度随规模增大而提高，但仍远高于两个人类群体之间的相似度，这使其成为一个可能值得关注的有趣统计量。

> In the recent past, a popular way of evaluating natural language understanding (NLU), was to consider a model's ability to perform natural language inference (NLI) tasks. In this paper, we investigate if NLI tasks, that are rarely used for LLM evaluation, can still be informative for evaluating LLMs. Focusing on five different NLI benchmarks across six models of different scales, we investigate if they are able to discriminate models of different size and quality and how their accuracies develop during training. Furthermore, we investigate the extent to which the softmax distributions of models align with human distributions in cases where statements are ambiguous or vague. Overall, our results paint a positive picture for the NLI tasks: we find that they are able to discriminate well between models at various stages of training, yet are not (all) saturated. Furthermore, we find that while the similarity of model distributions with human label distributions increases with scale, it is still much higher than the similarity between two populations of humans, making it a potentially interesting statistic to consider.

[Arxiv](https://arxiv.org/abs/2411.14103)