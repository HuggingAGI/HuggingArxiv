# P-RAG：渐进式检索增强生成，专为实体日常任务规划而生

发布时间：2024年09月17日

`RAG` `人工智能` `机器人`

> P-RAG: Progressive Retrieval Augmented Generation For Planning on Embodied Everyday Task

# 摘要

> Embodied Everyday Task 在 embodied AI 领域颇受欢迎，要求代理根据自然语言指令和视觉观察执行一系列动作。传统方法面临两大挑战：自然语言指令缺乏明确任务规划，且需大量训练才能掌握任务环境知识。基于大型语言模型 (LLM) 的先前工作要么因缺乏特定任务知识而表现不佳，要么依赖少量真实样本。为解决这些问题，我们提出了 Progressive Retrieval Augmented Generation (P-RAG) 方法，既充分利用 LLM 的语言处理能力，又逐步积累特定任务知识，无需真实数据。与传统一次性检索辅助生成的方法不同，P-RAG 采用迭代方式逐步更新数据库，每次迭代都从前次交互中获取历史信息作为经验参考。我们还引入了更细粒度的检索方案，不仅检索类似任务，还结合类似情况，提供更有价值的参考经验。实验证明，P-RAG 在不使用真实数据的情况下表现优异，甚至可通过自我迭代进一步提升性能。

> Embodied Everyday Task is a popular task in the embodied AI community, requiring agents to make a sequence of actions based on natural language instructions and visual observations. Traditional learning-based approaches face two challenges. Firstly, natural language instructions often lack explicit task planning. Secondly, extensive training is required to equip models with knowledge of the task environment. Previous works based on Large Language Model (LLM) either suffer from poor performance due to the lack of task-specific knowledge or rely on ground truth as few-shot samples. To address the above limitations, we propose a novel approach called Progressive Retrieval Augmented Generation (P-RAG), which not only effectively leverages the powerful language processing capabilities of LLMs but also progressively accumulates task-specific knowledge without ground-truth. Compared to the conventional RAG methods, which retrieve relevant information from the database in a one-shot manner to assist generation, P-RAG introduces an iterative approach to progressively update the database. In each iteration, P-RAG retrieves the latest database and obtains historical information from the previous interaction as experiential references for the current interaction. Moreover, we also introduce a more granular retrieval scheme that not only retrieves similar tasks but also incorporates retrieval of similar situations to provide more valuable reference experiences. Extensive experiments reveal that P-RAG achieves competitive results without utilizing ground truth and can even further improve performance through self-iterations.

[Arxiv](https://arxiv.org/abs/2409.11279)