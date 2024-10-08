# 探索大型语言模型在辅导中的教学引导：以建模生产性失败为例

发布时间：2024年10月03日

`LLM应用` `人工智能`

> Towards the Pedagogical Steering of Large Language Models for Tutoring: A Case Study with Modeling Productive Failure

# 摘要

> 一对一辅导是最有效的教学方法之一。随着大型语言模型 (LLM) 的兴起，人们开始利用它们创建对话式辅导系统，使一对一辅导的好处惠及大众。然而，当前的 LLM 主要被训练为助手，缺乏关键的教学技能。例如，它们常常迅速给出答案，无法进行丰富的多轮教学互动。为了在教学场景中有效使用 LLM，我们需要引导它们采用有效的教学策略，这就是我们提出的“教学引导”问题。我们通过引入 StratL 算法，形式化辅导策略的概念，并通过提示引导 LLM 遵循这些策略。作为案例研究，我们基于 Productive Failure (PF) 设计，创建了一个高中数学辅导原型。为了验证我们的方法，我们在新加坡对 17 名高中生进行了实地研究，结果显示 StratL 成功引导 LLM 遵循了 PF 辅导策略。我们还探讨了 LLM 的理想属性是否受到影响。基于这些发现，我们指出了教学引导的挑战，并提出了改进方向。此外，我们发布了 PF 问题数据集及原型代码，以鼓励后续研究。

> One-to-one tutoring is one of the most efficient methods of teaching. Following the rise in popularity of Large Language Models (LLMs), there have been efforts to use them to create conversational tutoring systems, which can make the benefits of one-to-one tutoring accessible to everyone. However, current LLMs are primarily trained to be helpful assistants and thus lack crucial pedagogical skills. For example, they often quickly reveal the solution to the student and fail to plan for a richer multi-turn pedagogical interaction. To use LLMs in pedagogical scenarios, they need to be steered towards using effective teaching strategies: a problem we introduce as Pedagogical Steering and believe to be crucial for the efficient use of LLMs as tutors. We address this problem by formalizing a concept of tutoring strategy, and introducing StratL, an algorithm to model a strategy and use prompting to steer the LLM to follow this strategy. As a case study, we create a prototype tutor for high school math following Productive Failure (PF), an advanced and effective learning design. To validate our approach in a real-world setting, we run a field study with 17 high school students in Singapore. We quantitatively show that StratL succeeds in steering the LLM to follow a Productive Failure tutoring strategy. We also thoroughly investigate the existence of spillover effects on desirable properties of the LLM, like its ability to generate human-like answers. Based on these results, we highlight the challenges in Pedagogical Steering and suggest opportunities for further improvements. We further encourage follow-up research by releasing a dataset of Productive Failure problems and the code of our prototype and algorithm.

[Arxiv](https://arxiv.org/abs/2410.03781)