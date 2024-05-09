# 借助Overgenerate-and-rank策略，我们优化了数学多项选择题的自动干扰项生成，提升了题目的质量和难度。

发布时间：2024年04月18日

`Agent

理由：这篇论文主要探讨了自动生成数学题的干扰项的方法，并利用排名模型来筛选生成的干扰项。这个过程涉及到创建一个能够生成和评估干扰项的系统，这可以被视为一个智能代理（Agent）的行为，因为它在执行任务（生成和评估干扰项）时需要做出决策和预测。因此，这篇论文更符合Agent分类，而不是RAG、LLM应用或LLM理论，因为它不直接涉及检索增强生成（RAG）、大型语言模型（LLM）的应用或理论研究。` `数学教育` `自动出题系统`

> Improving Automated Distractor Generation for Math Multiple-choice Questions with Overgenerate-and-rank

# 摘要

> 多选题因其便于大规模评分和应用而在数学教育中广泛使用，其关键在于精心设计的干扰项，旨在模拟学生的常见错误。然而，自动生成数学题的干扰项一直颇具挑战。本研究提出一种创新方法，通过大量生成并利用排名模型筛选，该模型能预测学生选择干扰项的可能性。实验与教师评估均显示，我们的方法虽提升了生成干扰项与人工编写的相似度，但人工编写的干扰项仍更受青睐。

> Multiple-choice questions (MCQs) are commonly used across all levels of math education since they can be deployed and graded at a large scale. A critical component of MCQs is the distractors, i.e., incorrect answers crafted to reflect student errors or misconceptions. Automatically generating them in math MCQs, e.g., with large language models, has been challenging. In this work, we propose a novel method to enhance the quality of generated distractors through overgenerate-and-rank, training a ranking model to predict how likely distractors are to be selected by real students. Experimental results on a real-world dataset and human evaluation with math teachers show that our ranking model increases alignment with human-authored distractors, although human-authored ones are still preferred over generated ones.

[Arxiv](https://arxiv.org/abs/2405.05144)