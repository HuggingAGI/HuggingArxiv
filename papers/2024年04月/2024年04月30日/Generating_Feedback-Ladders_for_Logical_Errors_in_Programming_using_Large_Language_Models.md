# 利用大型语言模型为编程中的逻辑错误构建反馈梯度。

发布时间：2024年04月30日

`LLM应用` `软件工程`

> Generating Feedback-Ladders for Logical Errors in Programming using Large Language Models

# 摘要

> 在编程作业逻辑错误反馈生成领域，基于大型语言模型（LLM）的技术展现了显著的前景。这些技术通过问题描述和学生（存在缺陷的）作业提交，指导LLM生成反馈。然而，这种方法面临多重挑战：首先，反馈信息往往过于直白，容易暴露错误，减少了学生的自我发现机会；其次，它们忽略了学生的学习背景，如过往作业和知识水平；再者，它们缺乏层次性，通常对所有学生提交采用统一的提示。本文提出了一种利用LLM生成“反馈阶梯”的方法，即为同一问题和学生提交提供多层次的反馈。通过与学生、教师和研究者的用户体验研究，我们评估了所生成反馈阶梯的质量，并发现对于更高层次的反馈和得分较高的作业，其效果逐渐减弱。在实际应用中，该方法允许教师根据学生的个性化学习需求选择合适的反馈层次，或者在高层次反馈未能纠正错误时，逐步提供更详细的指导。

> In feedback generation for logical errors in programming assignments, large language model (LLM)-based methods have shown great promise. These methods ask the LLM to generate feedback given the problem statement and a student's (buggy) submission. There are several issues with these types of methods. First, the generated feedback messages are often too direct in revealing the error in the submission and thus diminish valuable opportunities for the student to learn. Second, they do not consider the student's learning context, i.e., their previous submissions, current knowledge, etc. Third, they are not layered since existing methods use a single, shared prompt for all student submissions. In this paper, we explore using LLMs to generate a "feedback-ladder", i.e., multiple levels of feedback for the same problem-submission pair. We evaluate the quality of the generated feedback-ladder via a user study with students, educators, and researchers. We have observed diminishing effectiveness for higher-level feedback and higher-scoring submissions overall in the study. In practice, our method enables teachers to select an appropriate level of feedback to show to a student based on their personal learning context, or in a progressive manner to go more detailed if a higher-level feedback fails to correct the student's error.

[Arxiv](https://arxiv.org/abs/2405.00302)