# 交互式 DualChecker 旨在减少大型语言模型蒸馏过程中的幻觉问题

发布时间：2024年08月22日

`LLM应用` `绿色创新` `机器学习`

> Interactive DualChecker for Mitigating Hallucinations in Distilling Large Language Models

# 摘要

> 大型语言模型（LLM）在多种机器学习任务中表现出色，为高成本的监督学习数据集提供了一种高效的替代方案，通过少样本上下文学习实现价值。然而，这些模型在知识不完整的领域易产生幻觉，且现有的知识蒸馏方法难以提升模型效果。为此，我们创新性地提出了DualChecker框架，通过ContextAligner确保教师模型上下文符合人类标准，并引入动态检查系统，优化模型交互，促进知识高效传递。实验表明，DualChecker在绿色创新文本数据集上的表现显著超越现有技术，教师和学生模型的F1分数分别提升17%和10%。即使在挑战性领域，使用LLM预测微调的学生模型也能与实际数据微调的模型相媲美。我们公开了所有研究资源，以促进进一步的研究和应用。

> Large Language Models (LLMs) have demonstrated exceptional capabilities across various machine learning (ML) tasks. Given the high costs of creating annotated datasets for supervised learning, LLMs offer a valuable alternative by enabling effective few-shot in-context learning. However, these models can produce hallucinations, particularly in domains with incomplete knowledge. Additionally, current methods for knowledge distillation using LLMs often struggle to enhance the effectiveness of both teacher and student models. To address these challenges, we introduce DualChecker, an innovative framework designed to mitigate hallucinations and improve the performance of both teacher and student models during knowledge distillation. DualChecker employs ContextAligner to ensure that the context provided by teacher models aligns with human labeling standards. It also features a dynamic checker system that enhances model interaction: one component re-prompts teacher models with more detailed content when they show low confidence, and another identifies borderline cases from student models to refine the teaching templates. This interactive process promotes continuous improvement and effective knowledge transfer between the models. We evaluate DualChecker using a green innovation textual dataset that includes binary, multiclass, and token classification tasks. The experimental results show that DualChecker significantly outperforms existing state-of-the-art methods, achieving up to a 17% improvement in F1 score for teacher models and 10% for student models. Notably, student models fine-tuned with LLM predictions perform comparably to those fine-tuned with actual data, even in a challenging domain. We make all datasets, models, and code from this research publicly available.

[Arxiv](https://arxiv.org/abs/2408.12326)