# 本研究借助提示学习技术，针对 Stack Overflow 平台开发了一种自动为编程问题生成融合两种模态信息的标题方法。

发布时间：2024年03月06日

`Agent`

> Automatic Bi-modal Question Title Generation for Stack Overflow with Prompt Learning

# 摘要

> 面对 Stack Overflow 中的问题提问，开发者常常难以在标题中精准提炼核心问题，导致问题求助延迟。因此，提升问题标题质量成为学术界关注热点。初期研究尝试仅依据问题正文中的代码片段自动生成标题，却忽视了其中问题描述的重要信息。为此，我们创新性地提出 SOTitle+ 方法，结合问题正文中的代码片段与问题描述两种模态信息进行处理。我们将针对不同编程语言的问题标题生成任务拆分为多个相关联的任务，并运用多任务学习策略共同优化。随后，我们基于预训练模型 CodeT5 进行微调，使其能够自动生成问题标题。然而，由于预训练任务与实际研究任务之间输入和优化目标存在差异，使得微调过程中难以充分利用预训练模型所蕴含的知识。于是，SOTitle+ 进一步引入了混合提示调优技术，结合硬提示与软提示的优点来优化 CodeT5。为了验证 SOTitle+ 的优越性，我们从 Stack Overflow 最新公开数据集中精心筛选并构建了一个涵盖六种主流编程语言、共计 179,119 条高质量问题帖子的大规模语料库。实验证明，在自动评价及人工评价两方面，SOTitle+ 均明显超越了四款最先进的基准方法。这一研究表明，在 Stack Overflow 标题生成领域中，综合考虑双模态信息与提示学习技术具有广阔的应用潜力和发展前景。

> When drafting question posts for Stack Overflow, developers may not accurately summarize the core problems in the question titles, which can cause these questions to not get timely help. Therefore, improving the quality of question titles has attracted the wide attention of researchers. An initial study aimed to automatically generate the titles by only analyzing the code snippets in the question body. However, this study ignored the helpful information in their corresponding problem descriptions. Therefore, we propose an approach SOTitle+ by considering bi-modal information (i.e., the code snippets and the problem descriptions) in the question body. Then we formalize the title generation for different programming languages as separate but related tasks and utilize multi-task learning to solve these tasks. Later we fine-tune the pre-trained language model CodeT5 to automatically generate the titles. Unfortunately, the inconsistent inputs and optimization objectives between the pre-training task and our investigated task may make fine-tuning hard to fully explore the knowledge of the pre-trained model. To solve this issue, SOTitle+ further prompt-tunes CodeT5 with hybrid prompts (i.e., mixture of hard and soft prompts). To verify the effectiveness of SOTitle+, we construct a large-scale high-quality corpus from recent data dumps shared by Stack Overflow. Our corpus includes 179,119 high-quality question posts for six popular programming languages. Experimental results show that SOTitle+ can significantly outperform four state-of-the-art baselines in both automatic evaluation and human evaluation. Our work indicates that considering bi-modal information and prompt learning in Stack Overflow title generation is a promising exploration direction.

[Arxiv](https://arxiv.org/abs/2403.03677)