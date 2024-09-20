# 通过高效知识蒸馏，小型语言模型也能获得教师模型的智慧。

发布时间：2024年09月19日

`LLM理论` `人工智能`

> Efficient Knowledge Distillation: Empowering Small Language Models with Teacher Model Insights

# 摘要

> 提升小型语言模型在实际应用中的部署能力，是研究界的一大挑战。由于大型语言模型的使用成本和难度，研究人员正探索如何有效部署任务特定的小型模型。我们提出了一种简单高效的知识蒸馏方法，通过一个约30亿参数的教师模型，识别决策中最关键的标记，并将其作为学生模型的学习依据。实验证明，这种方法在四个不同数据集上均优于传统微调和现有蒸馏技术。进一步分析发现，在68%的情况下，特别是在标签即答案的场景中，提取的标记与真实答案高度相关。

> Enhancing small language models for real-life application deployment is a significant challenge facing the research community. Due to the difficulties and costs of using large language models, researchers are seeking ways to effectively deploy task-specific small models. In this work, we introduce a simple yet effective knowledge distillation method to improve the performance of small language models. Our approach utilizes a teacher model with approximately 3 billion parameters to identify the most influential tokens in its decision-making process. These tokens are extracted from the input based on their attribution scores relative to the output, using methods like saliency maps. These important tokens are then provided as rationales to a student model, aiming to distill the knowledge of the teacher model. This method has proven to be effective, as demonstrated by testing it on four diverse datasets, where it shows improvement over both standard fine-tuning methods and state-of-the-art knowledge distillation models. Furthermore, we explore explanations of the success of the model by analyzing the important tokens extracted from the teacher model. Our findings reveal that in 68\% of cases, specifically in datasets where labels are part of the answer, such as multiple-choice questions, the extracted tokens are part of the ground truth.

[Arxiv](https://arxiv.org/abs/2409.12586)