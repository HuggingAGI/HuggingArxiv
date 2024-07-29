# 借助 GPT-4 引领因果机器学习之旅

发布时间：2024年07月26日

`LLM应用` `人工智能` `机器学习`

> Using GPT-4 to guide causal machine learning

# 摘要

> 自ChatGPT问世以来，其影响力空前绝后。一方面，专家们对AI的进步赞不绝口，同时也警示其潜在风险；另一方面，有人对大型语言模型（LLMs）的准确性与实用性提出质疑。本文聚焦于LLMs的因果关系识别能力，特别是GPT-4（Turbo）的表现。我们通过仅依赖变量标签、不提供任何上下文的方式，评估了GPT-4推断因果关系的能力，揭示了其在仅接收标签信息时的最低有效性水平。结果显示，参与者认为GPT-4图在评估中最为准确，紧随其后的是领域专家构建的知识图，而因果机器学习（ML）则明显落后。我们借此强调因果ML的一个关键局限：它常生成违背常识的因果图，损害了信任度。但通过将GPT-4与因果ML结合，我们成功克服了这一局限，使得从真实数据中学习的图形结构更贴近专家识别的结构，相较于单独使用因果ML。综上所述，尽管GPT-4并非专为因果推理设计，但它仍能显著提升因果ML算法的因果发现过程，成为因果表示的宝贵工具。

> Since its introduction to the public, ChatGPT has had an unprecedented impact. While some experts praised AI advancements and highlighted their potential risks, others have been critical about the accuracy and usefulness of Large Language Models (LLMs). In this paper, we are interested in the ability of LLMs to identify causal relationships. We focus on the well-established GPT-4 (Turbo) and evaluate its performance under the most restrictive conditions, by isolating its ability to infer causal relationships based solely on the variable labels without being given any context, demonstrating the minimum level of effectiveness one can expect when it is provided with label-only information. We show that questionnaire participants judge the GPT-4 graphs as the most accurate in the evaluated categories, closely followed by knowledge graphs constructed by domain experts, with causal Machine Learning (ML) far behind. We use these results to highlight the important limitation of causal ML, which often produces causal graphs that violate common sense, affecting trust in them. However, we show that pairing GPT-4 with causal ML overcomes this limitation, resulting in graphical structures learnt from real data that align more closely with those identified by domain experts, compared to structures learnt by causal ML alone. Overall, our findings suggest that despite GPT-4 not being explicitly designed to reason causally, it can still be a valuable tool for causal representation, as it improves the causal discovery process of causal ML algorithms that are designed to do just that.

[Arxiv](https://arxiv.org/abs/2407.18607)