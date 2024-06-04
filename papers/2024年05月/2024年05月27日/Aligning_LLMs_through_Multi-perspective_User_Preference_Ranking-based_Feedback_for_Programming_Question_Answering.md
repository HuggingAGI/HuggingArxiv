# 基于多视角用户偏好排名的反馈，优化大型语言模型以精准解答编程问题

发布时间：2024年05月27日

`LLM应用

这篇论文主要探讨了如何通过结合基于人类反馈的强化学习（RLHF）技术来微调大型语言模型（LLMs），以更好地适应代码社区问答（CCQA）的需求。论文提出了一个名为“基于多视角用户偏好排序反馈的编程问答大型语言模型对齐（ALMupQA）”框架，并创建了StaCCQA数据集来评估其性能。这一研究直接应用于LLM在特定场景（即代码社区问答）的优化和改进，因此属于LLM应用类别。` `软件工程` `问答系统`

> Aligning LLMs through Multi-perspective User Preference Ranking-based Feedback for Programming Question Answering

# 摘要

> 代码社区问答（CCQA）致力于解决编程难题，提升软件工程与学术研究的生产效率。近期，基于人类反馈的强化学习（RLHF）技术革新了大型语言模型（LLMs）的微调方法，使其回答更贴近人类行为。结合RLHF的LLMs在CCQA实际应用中展现出巨大潜力。不同于传统代码问答，CCQA提供多个答案选项，且用户偏好各异。同时，代码社区倾向于采用新API，这给LLMs带来了挑战，难以满足CCQA任务中用户的多样化需求。为此，我们创新性地提出了“基于多视角用户偏好排序反馈的编程问答大型语言模型对齐（ALMupQA）”框架，旨在生成更贴合用户需求的回答。该框架首先通过多视角偏好排序对齐（MPRA）整合不同用户偏好，再通过检索增强的上下文学习（RIL）模块，从问题库中提取相似问题答案，以解决答案过时问题。鉴于高质量多答案CCQA数据集的缺乏，我们创建了StaCCQA数据集。实验结果显示，ALMupQA在准确性和用户偏好上均有显著提升，相较于基础模型，BLEU得分提升11%，BERTScore和CodeBERTScore分别提升20%和17.5%。

> Code Community Question Answering (CCQA) seeks to tackle programming-related issues, thereby boosting productivity in both software engineering and academic research. Recent advancements in Reinforcement Learning from Human Feedback (RLHF) have transformed the fine-tuning process of Large Language Models (LLMs) to produce responses that closely mimic human behavior. Leveraging LLMs with RLHF for practical CCQA applications has thus emerged as a promising area of study. Unlike standard code question-answering tasks, CCQA involves multiple possible answers, with varying user preferences for each response. Additionally, code communities often show a preference for new APIs. These challenges prevent LLMs from generating responses that cater to the diverse preferences of users in CCQA tasks. To address these issues, we propose a novel framework called Aligning LLMs through Multi-perspective User Preference Ranking-based Feedback for Programming Question Answering (ALMupQA) to create user-focused responses. Our approach starts with Multi-perspective Preference Ranking Alignment (MPRA), which synthesizes varied user preferences based on the characteristics of answers from code communities. We then introduce a Retrieval-augmented In-context Learning (RIL) module to mitigate the problem of outdated answers by retrieving responses to similar questions from a question bank. Due to the limited availability of high-quality, multi-answer CCQA datasets, we also developed a dataset named StaCCQA from real code communities. Extensive experiments demonstrated the effectiveness of the ALMupQA framework in terms of accuracy and user preference. Compared to the base model, ALMupQA showed nearly an 11% improvement in BLEU, with increases of 20% and 17.5% in BERTScore and CodeBERTScore, respectively.

![基于多视角用户偏好排名的反馈，优化大型语言模型以精准解答编程问题](../../../paper_images/2406.00037/x1.png)

![基于多视角用户偏好排名的反馈，优化大型语言模型以精准解答编程问题](../../../paper_images/2406.00037/x2.png)

![基于多视角用户偏好排名的反馈，优化大型语言模型以精准解答编程问题](../../../paper_images/2406.00037/x3.png)

![基于多视角用户偏好排名的反馈，优化大型语言模型以精准解答编程问题](../../../paper_images/2406.00037/x4.png)

![基于多视角用户偏好排名的反馈，优化大型语言模型以精准解答编程问题](../../../paper_images/2406.00037/x5.png)

![基于多视角用户偏好排名的反馈，优化大型语言模型以精准解答编程问题](../../../paper_images/2406.00037/x6.png)

[Arxiv](https://arxiv.org/abs/2406.00037)