# HierLLM：专为问题推荐设计的分层大型语言模型

发布时间：2024年09月09日

`LLM应用` `人工智能`

> HierLLM: Hierarchical Large Language Model for Question Recommendation

# 摘要

> 问题推荐旨在通过按顺序推荐问题来提升学生的学习效率。传统方法将此视为顺序决策问题，利用学习历史和目标来推荐问题，但面临冷启动和问题集过大两大难题。为此，我们提出了分层大语言模型（HierLLM），利用LLM的推理能力解决冷启动问题，并通过分层结构缩小推荐范围，从而提高推荐精度。实验结果显示，HierLLM表现优异。

> Question recommendation is a task that sequentially recommends questions for students to enhance their learning efficiency. That is, given the learning history and learning target of a student, a question recommender is supposed to select the question that will bring the most improvement for students. Previous methods typically model the question recommendation as a sequential decision-making problem, estimating students' learning state with the learning history, and feeding the learning state with the learning target to a neural network to select the recommended question from a question set. However, previous methods are faced with two challenges: (1) learning history is unavailable in the cold start scenario, which makes the recommender generate inappropriate recommendations; (2) the size of the question set is much large, which makes it difficult for the recommender to select the best question precisely. To address the challenges, we propose a method called hierarchical large language model for question recommendation (HierLLM), which is a LLM-based hierarchical structure. The LLM-based structure enables HierLLM to tackle the cold start issue with the strong reasoning abilities of LLM. The hierarchical structure takes advantage of the fact that the number of concepts is significantly smaller than the number of questions, narrowing the range of selectable questions by first identifying the relevant concept for the to-recommend question, and then selecting the recommended question based on that concept. This hierarchical structure reduces the difficulty of the recommendation.To investigate the performance of HierLLM, we conduct extensive experiments, and the results demonstrate the outstanding performance of HierLLM.

[Arxiv](https://arxiv.org/abs/2409.06177)