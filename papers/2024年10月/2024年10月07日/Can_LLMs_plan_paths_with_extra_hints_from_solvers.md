# LLMs 能否借助解算器的额外提示来规划路径？

发布时间：2024年10月07日

`LLM应用` `机器人` `人工智能`

> Can LLMs plan paths with extra hints from solvers?

# 摘要

> LLM 在 NLP、数学和程序合成任务中表现出色，但在长期规划和高阶推理方面仍显不足。本文通过引入求解器反馈，探索了提升 LLM 在机器人规划任务中表现的方法。我们测试了四种反馈策略，包括视觉反馈，并对三种 LLM 在 10 个标准和 100 个随机生成的规划问题中的表现进行了评估。结果显示，求解器反馈能有效提升 LLM 解决中等难度问题的能力，但面对更难的问题仍显乏力。研究还深入分析了不同提示策略和 LLM 的规划倾向。

> Large Language Models (LLMs) have shown remarkable capabilities in natural language processing, mathematical problem solving, and tasks related to program synthesis. However, their effectiveness in long-term planning and higher-order reasoning has been noted to be limited and fragile. This paper explores an approach for enhancing LLM performance in solving a classical robotic planning task by integrating solver-generated feedback. We explore four different strategies for providing feedback, including visual feedback, we utilize fine-tuning, and we evaluate the performance of three different LLMs across a 10 standard and 100 more randomly generated planning problems. Our results suggest that the solver-generated feedback improves the LLM's ability to solve the moderately difficult problems, but the harder problems still remain out of reach. The study provides detailed analysis of the effects of the different hinting strategies and the different planning tendencies of the evaluated LLMs.

[Arxiv](https://arxiv.org/abs/2410.05045)