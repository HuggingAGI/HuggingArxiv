# AMPCliff 研究：为抗微生物肽中的活性差异设立定量标准，并进行性能基准评估

发布时间：2024年04月15日

`LLM应用` `生物信息学` `药物研发`

> AMPCliff: quantitative definition and benchmarking of activity cliffs in antimicrobial peptides

# 摘要

> 活性悬崖（AC）现象描述了一对结构相似的分子，仅因微小变化却导致其生化活性差异显著。尽管小分子的AC现象已受到广泛关注，但关于标准氨基酸构成的肽链中的AC现象，我们知之甚少。本研究提出了AMPCliff这一量化方法和评估框架，专门针对由标准氨基酸构成的抗微生物肽（AMPs）中的AC现象。通过对现有AMP数据的综合分析，我们发现AMP中AC现象普遍存在。AMPCliff通过最小抑菌浓度（MIC）来衡量AMP的活性，并设定0.9为对齐肽链之间BLOSUM62相似度的最低阈值，这些肽链至少有两倍以上MIC的变化。研究基于公开数据集GRAMPA建立了金黄色葡萄球菌AMP对的基准数据集，并对多种AMP AC预测模型进行了严格评估，包括九种机器学习方法、四种深度学习算法、四种掩蔽语言模型和四种生成语言模型。分析结果表明，这些模型能够有效识别AMP AC事件，其中预训练的ESM2蛋白质语言模型在各项评估中表现突出。尽管如此，AMP活性悬崖的预测精度仍有提升空间，目前ESM2模型在MIC值回归任务中的斯皮尔曼相关系数仅为0.50。相关源代码和资源可通过https://www.healthinformaticslab.org/supp/ 或 https://github.com/Kewei2023/AMPCliff-generation 访问。

> Activity cliff (AC) is a phenomenon that a pair of similar molecules differ by a small structural alternation but exhibit a large difference in their biochemical activities. The AC of small molecules has been extensively investigated but limited knowledge is accumulated about the AC phenomenon in peptides with canonical amino acids. This study introduces a quantitative definition and benchmarking framework AMPCliff for the AC phenomenon in antimicrobial peptides (AMPs) composed by canonical amino acids. A comprehensive analysis of the existing AMP dataset reveals a significant prevalence of AC within AMPs. AMPCliff quantifies the activities of AMPs by the metric minimum inhibitory concentration (MIC), and defines 0.9 as the minimum threshold for the normalized BLOSUM62 similarity score between a pair of aligned peptides with at least two-fold MIC changes. This study establishes a benchmark dataset of paired AMPs in Staphylococcus aureus from the publicly available AMP dataset GRAMPA, and conducts a rigorous procedure to evaluate various AMP AC prediction models, including nine machine learning, four deep learning algorithms, four masked language models, and four generative language models. Our analysis reveals that these models are capable of detecting AMP AC events and the pre-trained protein language ESM2 model demonstrates superior performance across the evaluations. The predictive performance of AMP activity cliffs remains to be further improved, considering that ESM2 with 33 layers only achieves the Spearman correlation coefficient=0.50 for the regression task of the MIC values on the benchmark dataset. Source code and additional resources are available at https://www.healthinformaticslab.org/supp/ or https://github.com/Kewei2023/AMPCliff-generation.

[Arxiv](https://arxiv.org/abs/2404.09738)