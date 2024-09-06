# 个性化内容分类器的终端用户创作：对比示例标签、规则编写与 LLM 提示

发布时间：2024年09月05日

`LLM应用` `社交媒体` `用户体验`

> End User Authoring of Personalized Content Classifiers: Comparing Example Labeling, Rule Writing, and LLM Prompting

# 摘要

> 现有的个人分类器创建工具通常假设用户会在一个长时间的无干扰会话中工作。然而，社交媒体用户往往以碎片化的方式互动，每天进行多次短时间会话。为了简化这类用户的内容管理分类器创建过程，工具应支持快速启动和迭代优化。我们比较了三种策略：示例标注、规则编写和LLM提示，用于帮助用户构建个人内容分类器。实验结果显示，LLM提示在5分钟内使非程序员参与者达到峰值性能的95%，因其高召回率而优于其他策略，但在迭代优化方面仍需改进。尽管LLM提示表现优异，用户在不同情境下偏好不同策略，甚至在使用提示时也倾向于提供示例或编写规则，这表明混合方法更具吸引力。

> Existing tools for laypeople to create personal classifiers often assume a motivated user working uninterrupted in a single, lengthy session. However, users tend to engage with social media casually, with many short sessions on an ongoing, daily basis. To make creating personal classifiers for content curation easier for such users, tools should support rapid initialization and iterative refinement. In this work, we compare three strategies -- (1) example labeling, (2) rule writing, and (3) large language model (LLM) prompting -- for end users to build personal content classifiers. From an experiment with 37 non-programmers tasked with creating personalized comment moderation filters, we found that with LLM prompting, participants reached 95\% of peak performance in 5 minutes, beating other strategies due to higher recall, but all strategies struggled with iterative refinement. Despite LLM prompting's better performance, participants preferred different strategies in different contexts and, even when prompting, provided examples or wrote rule-like prompts, suggesting hybrid approaches.

[Arxiv](https://arxiv.org/abs/2409.03247)