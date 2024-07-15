# Lomics：借助大型语言模型，我们生成通路和基因集，以助力转录组分析的深入探索。

发布时间：2024年07月12日

`LLM应用` `生物信息学` `转录组分析`

> Lomics: Generation of Pathways and Gene Sets using Large Language Models for Transcriptomic Analysis

# 摘要

> 生物途径的探究是omics数据分析的核心。借助大型语言模型（LLMs），我们能定制针对特定科学问题的生物途径和基因集，这些定制集远小于传统途径富集库，有效减少多重假设检验，提升统计效力。Lomics v1.0，一款基于Python的生物信息学工具，优化了转录组分析中的途径与基因集生成流程，通过三步操作：根据研究问题推导途径、生成有效基因集、输出.GMX文件，并附带途径选择解释。通过迭代、格式验证及基因符号核对，确保结果的准确与一致。Lomics不仅为LLMs在omics研究中的应用打下基础，更可能提升途径分析的精准与效率。

> Interrogation of biological pathways is an integral part of omics data analysis. Large language models (LLMs) enable the generation of custom pathways and gene sets tailored to specific scientific questions. These targeted sets are significantly smaller than traditional pathway enrichment analysis libraries, reducing multiple hypothesis testing and potentially enhancing statistical power. Lomics (Large Language Models for Omics Studies) v1.0 is a python-based bioinformatics toolkit that streamlines the generation of pathways and gene sets for transcriptomic analysis. It operates in three steps: 1) deriving relevant pathways based on the researcher's scientific question, 2) generating valid gene sets for each pathway, and 3) outputting the results as .GMX files. Lomics also provides explanations for pathway selections. Consistency and accuracy are ensured through iterative processes, JSON format validation, and HUGO Gene Nomenclature Committee (HGNC) gene symbol verification. Lomics serves as a foundation for integrating LLMs into omics research, potentially improving the specificity and efficiency of pathway analysis.

[Arxiv](https://arxiv.org/abs/2407.09089)