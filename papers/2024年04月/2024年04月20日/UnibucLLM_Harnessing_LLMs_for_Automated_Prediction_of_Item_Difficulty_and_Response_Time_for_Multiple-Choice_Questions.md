# UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。

发布时间：2024年04月20日

`LLM应用` `医学教育`

> UnibucLLM: Harnessing LLMs for Automated Prediction of Item Difficulty and Response Time for Multiple-Choice Questions

# 摘要

> 本文提出了一种创新的数据增强技术，依托大型语言模型（LLMs），旨在预测美国医学执照考试（USMLE）多项选择题（MCQs）在BEA 2024共享任务中的题目难度与答题时间。该技术通过引入零样本LLMs（如Falcon、Meditron、Mistral）的答案来扩充数据集，并利用基于六种不同特征组合的变换器模型进行分析。研究发现，准确预测题目难度较为困难。尤为突出的是，表现最佳的模型始终整合了题目文本，并充分利用了LLMs答案的多样性，这突显了LLMs在提升医学执照考试自动化评估方面的潜力。我们的代码已在 https://github.com/ana-rogoz/BEA-2024 上公开，以供进一步研究。

> This work explores a novel data augmentation method based on Large Language Models (LLMs) for predicting item difficulty and response time of retired USMLE Multiple-Choice Questions (MCQs) in the BEA 2024 Shared Task. Our approach is based on augmenting the dataset with answers from zero-shot LLMs (Falcon, Meditron, Mistral) and employing transformer-based models based on six alternative feature combinations. The results suggest that predicting the difficulty of questions is more challenging. Notably, our top performing methods consistently include the question text, and benefit from the variability of LLM answers, highlighting the potential of LLMs for improving automated assessment in medical licensing exams. We make our code available https://github.com/ana-rogoz/BEA-2024.

![UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。](../../../paper_images/2404.13343/bea-overview-2.png)

![UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。](../../../paper_images/2404.13343/exam_difficulty_1.png)

![UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。](../../../paper_images/2404.13343/exam_response_1.png)

![UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。](../../../paper_images/2404.13343/item_difficulty_1.png)

![UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。](../../../paper_images/2404.13343/item_response_1.png)

![UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。](../../../paper_images/2404.13343/answer_difficulty_3.png)

![UnibucLLM：借助大型语言模型 (LLM) 之力，实现对多项选择题难度及答题时间的自动化预测。](../../../paper_images/2404.13343/answer_time_3.png)

[Arxiv](https://arxiv.org/abs/2404.13343)