# 迈向可扩展的自动化评分：利用大型语言模型对工程中的概念性问题进行评估

发布时间：2024年11月05日

`LLM应用` `机械工程`

> Towards Scalable Automated Grading: Leveraging Large Language Models for Conceptual Question Evaluation in Engineering

# 摘要

> 本研究探讨了使用大型语言模型（LLM），特别是 GPT-4o（ChatGPT），对本科机械工程课程中的概念性问题进行自动评分的可行性。我们将 GPT-4o 的评分表现与人类教学助理（TA）在德克萨斯 A&M 大学 MEEN 361 课程的十个测验问题上的表现进行了比较，每个问题约有 225 名学生回答。LLM 和 TA 都遵循相同的教师提供的评分标准，以确保评分的一致性。我们使用斯皮尔曼等级相关系数和均方根误差（RMSE）来评估性能，以评估 GPT-4o 和 TA 在零样本和少样本评分设置下的排名一致性和分配分数的准确性。在零样本设置中，GPT-4o 与 TA 评分显示出很强的相关性，在十个数据集中有七个的斯皮尔曼等级相关系数超过 0.6，最高达到 0.9387。我们的分析表明，当评分标准简单明了时，GPT-4o 表现良好，但在处理微妙的答案时存在困难，特别是那些涉及评分标准中未出现的同义词的答案。与人类 TA 相比，该模型在模糊情况下的评分也往往更严格。总的来说，ChatGPT 作为概念性问题评分的工具显示出了潜力，具有可扩展性和一致性。

> This study explores the feasibility of using large language models (LLMs), specifically GPT-4o (ChatGPT), for automated grading of conceptual questions in an undergraduate Mechanical Engineering course. We compared the grading performance of GPT-4o with that of human teaching assistants (TAs) on ten quiz problems from the MEEN 361 course at Texas A&M University, each answered by approximately 225 students. Both the LLM and TAs followed the same instructor-provided rubric to ensure grading consistency. We evaluated performance using Spearman's rank correlation coefficient and Root Mean Square Error (RMSE) to assess the alignment between rankings and the accuracy of scores assigned by GPT-4o and TAs under zero- and few-shot grading settings. In the zero-shot setting, GPT-4o demonstrated a strong correlation with TA grading, with Spearman's rank correlation coefficient exceeding 0.6 in seven out of ten datasets and reaching a high of 0.9387. Our analysis reveals that GPT-4o performs well when grading criteria are straightforward but struggles with nuanced answers, particularly those involving synonyms not present in the rubric. The model also tends to grade more stringently in ambiguous cases compared to human TAs. Overall, ChatGPT shows promise as a tool for grading conceptual questions, offering scalability and consistency.

[Arxiv](https://arxiv.org/abs/2411.03659)