# 大型语言模型的规则化数据精选

发布时间：2024年10月06日

`LLM理论` `人工智能` `数据科学`

> Rule-based Data Selection for Large Language Models

# 摘要

> 训练数据的质量对 LLM 的性能影响重大。现有研究多依赖人工设计的规则来评分和选择数据，但这些传统方法过于依赖人类直觉，缺乏有效评估规则的指标，且适应新任务的能力有限。我们提出了一种创新的基于规则的框架，利用规则评分向量的正交性作为新评估指标。该框架首先使用 LLM 生成多样化的评分规则，涵盖多个维度以评估数据质量。然后，通过行列式点过程 (DPP) 选择最正交的评分向量，识别出独立规则，用于评估所有数据，并选择高平均分的样本用于 LLM 训练等下游任务。实验结果显示，我们的 DPP 评分方法在评分精度和模型性能上均优于其他方法，包括无规则评分、均匀采样、重要性重采样和 QuRating。

> The quality of training data significantly impacts the performance of large language models (LLMs). There are increasing studies using LLMs to rate and select data based on several human-crafted metrics (rules). However, these conventional rule-based approaches often depend too heavily on human heuristics, lack effective metrics for assessing rules, and exhibit limited adaptability to new tasks. In our study, we introduce an innovative rule-based framework that utilizes the orthogonality of score vectors associated with rules as a novel metric for rule evaluations. Our approach includes an automated pipeline that first uses LLMs to generate a diverse set of rules, encompassing various rating dimensions to evaluate data quality. Then it rates a batch of data based on these rules and uses the determinantal point process (DPP) from random matrix theory to select the most orthogonal score vectors, thereby identifying a set of independent rules. These rules are subsequently used to evaluate all data, selecting samples with the highest average scores for downstream tasks such as LLM training. We verify the effectiveness of our method through two experimental setups: 1) comparisons with ground truth ratings and 2) benchmarking LLMs trained with the chosen data. Our comprehensive experiments cover a range of scenarios, including general pre-training and domain-specific fine-tuning in areas such as IMDB, Medical, Math, and Code. The outcomes demonstrate that our DPP-based rule rating method consistently outperforms other approaches, including rule-free rating, uniform sampling, importance resampling, and QuRating, in terms of both rating precision and model performance.

[Arxiv](https://arxiv.org/abs/2410.04715)