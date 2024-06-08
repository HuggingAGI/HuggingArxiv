# 利用大型语言模型（LLM）结合机器反馈的强化学习，重塑不当论证

发布时间：2024年06月05日

`Agent

这篇论文探讨了如何通过计算手段减少社交媒体平台上的不当言论，提出了一种基于强化学习的重写策略，该策略利用大型语言模型（LLM）来平衡内容保留与适当性。这种方法在文档级别进行内容的永久删除和添加，旨在预防负面行为。由于该方法涉及使用强化学习来指导一个Agent（即重写策略）在特定环境下采取行动以达到目标（减少不当言论），因此将其归类为Agent。` `社交媒体` `内容审核`

> LLM-based Rewriting of Inappropriate Argumentation using Reinforcement Learning from Machine Feedback

# 摘要

> 社交媒体平台面临的一大挑战是如何确保在线讨论既文明又富有成效。通常，这些平台依靠用户和自动化工具来标记不当言论，再由版主审查，但这种事后审查既耗时又成本高昂，版主常因此不堪重负。为此，我们提出了一种在内容创作阶段预防负面行为的新方法。本文探讨了如何通过计算手段减少争论中的不当语言，提出了一种基于强化学习的重写策略，该策略利用大型语言模型（LLM）平衡内容保留与适当性。与传统的风格转换任务不同，我们的方法允许在文档级别永久删除和添加内容。通过一系列实验，我们证明了这种方法能在保留大部分内容的同时显著减少不当言论，其效果远超其他基线方法，包括少量学习、提示和人工审查。

> Ensuring that online discussions are civil and productive is a major challenge for social media platforms. Such platforms usually rely both on users and on automated detection tools to flag inappropriate arguments of other users, which moderators then review. However, this kind of post-hoc moderation is expensive and time-consuming, and moderators are often overwhelmed by the amount and severity of flagged content. Instead, a promising alternative is to prevent negative behavior during content creation. This paper studies how inappropriate language in arguments can be computationally mitigated. We propose a reinforcement learning-based rewriting approach that balances content preservation and appropriateness based on existing classifiers, prompting an instruction-finetuned large language model (LLM) as our initial policy. Unlike related style transfer tasks, rewriting inappropriate arguments allows deleting and adding content permanently. It is therefore tackled on document level rather than sentence level. We evaluate different weighting schemes for the reward function in both absolute and relative human assessment studies. Systematic experiments on non-parallel data provide evidence that our approach can mitigate the inappropriateness of arguments while largely preserving their content. It significantly outperforms competitive baselines, including few-shot learning, prompting, and humans.

![利用大型语言模型（LLM）结合机器反馈的强化学习，重塑不当论证](../../../paper_images/2406.03363/x1.png)

![利用大型语言模型（LLM）结合机器反馈的强化学习，重塑不当论证](../../../paper_images/2406.03363/x2.png)

![利用大型语言模型（LLM）结合机器反馈的强化学习，重塑不当论证](../../../paper_images/2406.03363/x3.png)

[Arxiv](https://arxiv.org/abs/2406.03363)