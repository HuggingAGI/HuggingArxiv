# LLMClean：一种利用大型语言模型（LLM）生成的OFD（开放性功能需求）进行上下文感知的表格数据清洗方法。

发布时间：2024年04月29日

`LLM应用` `企业决策` `工业4.0`

> LLMClean: Context-Aware Tabular Data Cleaning via LLM-Generated OFDs

# 摘要

> 机器学习正迅速成为企业决策和工业4.0发展的核心。AI的效能依赖于训练阶段使用的数据质量，而数据清洗工具，尤其是那些能够挖掘本体框架或上下文模型中功能依赖的工具，对于提升数据质量至关重要。尽管如此，构建这些上下文模型是一项既耗费资源又考验专业技能的任务，通常需要依赖领域专家的深入知识。面对这些挑战，本论文提出了一种名为LLMClean的创新自动生成上下文模型的方法，该方法利用大型语言模型来分析和理解不同的数据集。LLMClean通过一系列步骤，包括对数据集进行分类、提取或映射相关模型，最终生成上下文模型。为了证明其有效性，我们开发并测试了一个原型，将其应用于物联网、医疗保健和工业4.0领域的三个不同数据集。评估结果显示，我们的自动化方法在数据清洗效果上可与人类专家创建的上下文模型相媲美。

> Machine learning's influence is expanding rapidly, now integral to decision-making processes from corporate strategy to the advancements in Industry 4.0. The efficacy of Artificial Intelligence broadly hinges on the caliber of data used during its training phase; optimal performance is tied to exceptional data quality. Data cleaning tools, particularly those that exploit functional dependencies within ontological frameworks or context models, are instrumental in augmenting data quality. Nevertheless, crafting these context models is a demanding task, both in terms of resources and expertise, often necessitating specialized knowledge from domain experts.
  In light of these challenges, this paper introduces an innovative approach, called LLMClean, for the automated generation of context models, utilizing Large Language Models to analyze and understand various datasets. LLMClean encompasses a sequence of actions, starting with categorizing the dataset, extracting or mapping relevant models, and ultimately synthesizing the context model. To demonstrate its potential, we have developed and tested a prototype that applies our approach to three distinct datasets from the Internet of Things, healthcare, and Industry 4.0 sectors. The results of our evaluation indicate that our automated approach can achieve data cleaning efficacy comparable with that of context models crafted by human experts.

[Arxiv](https://arxiv.org/abs/2404.18681)