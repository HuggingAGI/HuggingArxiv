# 利用多视角用户偏好排名反馈，优化大型语言模型，提升编程问题解答的精准度。

发布时间：2024年05月27日

`LLM应用

这篇论文主要探讨了如何通过基于人类反馈的强化学习（RLHF）技术改进大型语言模型（LLMs），以更好地服务于代码社区问答（CCQA）系统。论文提出了一种新的框架“基于多视角用户偏好排序反馈对编程问答进行对齐的大型语言模型（ALMupQA）”，并创建了StaCCQA数据集来评估其性能。这一研究直接应用于提升LLMs在特定领域的实际应用效果，即在CCQA系统中生成更符合用户需求的回答，因此属于LLM应用类别。` `软件工程` `问答系统`

> Aligning LLMs through Multi-perspective User Preference Ranking-based Feedback for Programming Question Answering

# 摘要

> 代码社区问答（CCQA）致力于解决编程难题，提升软件工程与学术研究的生产效率。近期，基于人类反馈的强化学习（RLHF）技术革新了大型语言模型（LLMs）的微调方法，使其回答更贴近人类行为。RLHF与LLMs结合，为CCQA应用开辟了新天地。不同于传统代码问答，CCQA答案多样，用户偏好各异，且社区偏爱新API，这使得LLMs难以满足CCQA中用户的多元需求。为此，我们推出了“基于多视角用户偏好排序反馈对编程问答进行对齐的大型语言模型（ALMupQA）”框架，旨在生成更贴合用户需求的回答。我们首先通过多视角偏好排序对齐（MPRA）整合不同用户偏好，再通过检索增强的上下文学习（RIL）模块，从问题库中提取类似问题答案，以解决答案过时问题。鉴于高质量多答案CCQA数据集的缺乏，我们创建了StaCCQA数据集。实验表明，ALMupQA在提升回答准确性与用户满意度方面成效显著，相较于基础模型，其在BLEU、BERTScore和CodeBERTScore上分别提升了11%、20%和17.5%。

> Code Community Question Answering (CCQA) seeks to tackle programming-related issues, thereby boosting productivity in both software engineering and academic research. Recent advancements in Reinforcement Learning from Human Feedback (RLHF) have transformed the fine-tuning process of Large Language Models (LLMs) to produce responses that closely mimic human behavior. Leveraging LLMs with RLHF for practical CCQA applications has thus emerged as a promising area of study. Unlike standard code question-answering tasks, CCQA involves multiple possible answers, with varying user preferences for each response. Additionally, code communities often show a preference for new APIs. These challenges prevent LLMs from generating responses that cater to the diverse preferences of users in CCQA tasks. To address these issues, we propose a novel framework called Aligning LLMs through Multi-perspective User Preference Ranking-based Feedback for Programming Question Answering (ALMupQA) to create user-focused responses. Our approach starts with Multi-perspective Preference Ranking Alignment (MPRA), which synthesizes varied user preferences based on the characteristics of answers from code communities. We then introduce a Retrieval-augmented In-context Learning (RIL) module to mitigate the problem of outdated answers by retrieving responses to similar questions from a question bank. Due to the limited availability of high-quality, multi-answer CCQA datasets, we also developed a dataset named StaCCQA from real code communities. Extensive experiments demonstrated the effectiveness of the ALMupQA framework in terms of accuracy and user preference. Compared to the base model, ALMupQA showed nearly an 11% improvement in BLEU, with increases of 20% and 17.5% in BERTScore and CodeBERTScore, respectively.

![利用多视角用户偏好排名反馈，优化大型语言模型，提升编程问题解答的精准度。](../../../paper_images/2406.00037/x1.png)

![利用多视角用户偏好排名反馈，优化大型语言模型，提升编程问题解答的精准度。](../../../paper_images/2406.00037/x2.png)

![利用多视角用户偏好排名反馈，优化大型语言模型，提升编程问题解答的精准度。](../../../paper_images/2406.00037/x3.png)

![利用多视角用户偏好排名反馈，优化大型语言模型，提升编程问题解答的精准度。](../../../paper_images/2406.00037/x4.png)

![利用多视角用户偏好排名反馈，优化大型语言模型，提升编程问题解答的精准度。](../../../paper_images/2406.00037/x5.png)

![利用多视角用户偏好排名反馈，优化大型语言模型，提升编程问题解答的精准度。](../../../paper_images/2406.00037/x6.png)

[Arxiv](https://arxiv.org/abs/2406.00037)