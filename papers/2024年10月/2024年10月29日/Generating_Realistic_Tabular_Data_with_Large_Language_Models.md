# 利用大型语言模型生成逼真的表格数据

发布时间：2024年10月29日

`LLM应用` `表格数据` `数据生成`

> Generating Realistic Tabular Data with Large Language Models

# 摘要

> 虽说多数生成模型在图像数据生成领域成果斐然，但专为表格数据生成而开发的却寥寥无几。近来，鉴于大型语言模型（LLM）在各类任务中的出色表现，其也被应用于表格数据生成。然而，这些方法未能捕捉到特征与目标变量间的正确关联，给其在下游预测任务中的应用造成阻碍。为化解此难题，我们提出一种基于 LLM 的方法，包含三项重要改进，以精准捕捉真实数据中的真实特征-类别相关性。其一，在微调阶段，我们为输入数据提出了新颖的排列策略。其二，我们提出了特征条件采样的方法来生成合成样本。其三，我们依据生成的样本构建提示来询问微调后的 LLM 从而生成标签。大量实验表明，在下游任务的 20 个数据集中，我们的方法显著优于 10 个最先进的基线。在质量和多样性方面，它还生成了高度逼真的合成样本。尤为重要的是，用我们的合成数据训练的分类器，在半数基准数据集中甚至能与用原始数据训练的分类器一较高下，这在表格数据生成领域堪称重大成就。

> While most generative models show achievements in image data generation, few are developed for tabular data generation. Recently, due to success of large language models (LLM) in diverse tasks, they have also been used for tabular data generation. However, these methods do not capture the correct correlation between the features and the target variable, hindering their applications in downstream predictive tasks. To address this problem, we propose a LLM-based method with three important improvements to correctly capture the ground-truth feature-class correlation in the real data. First, we propose a novel permutation strategy for the input data in the fine-tuning phase. Second, we propose a feature-conditional sampling approach to generate synthetic samples. Finally, we generate the labels by constructing prompts based on the generated samples to query our fine-tuned LLM. Our extensive experiments show that our method significantly outperforms 10 SOTA baselines on 20 datasets in downstream tasks. It also produces highly realistic synthetic samples in terms of quality and diversity. More importantly, classifiers trained with our synthetic data can even compete with classifiers trained with the original data on half of the benchmark datasets, which is a significant achievement in tabular data generation.

[Arxiv](https://arxiv.org/abs/2410.21717)