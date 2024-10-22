# CPE-Pro：一款结构敏感的深度学习模型，专为蛋白质表示与起源评估而设计。

发布时间：2024年10月20日

`其他` `生物信息学` `蛋白质研究`

> CPE-Pro: A Structure-Sensitive Deep Learning Model for Protein Representation and Origin Evaluation

# 摘要

> 蛋白质结构对于理解其功能和相互作用至关重要。目前，众多蛋白质结构预测方法正在丰富结构数据库。区分结构的来源，对于区分实验解析和计算预测的结构、评估预测方法的可靠性以及指导下游生物学研究，具有重要意义。基于此，我们开发了结构敏感的监督深度学习模型CPE-Pro，用于表示和区分蛋白质结构的来源。CPE-Pro通过学习蛋白质的结构信息，捕捉结构间的差异，实现对四个数据类别的准确追溯，并有望扩展至更多类别。同时，我们利用Foldseek将蛋白质结构编码为“结构序列”，并训练了SSLM。初步实验显示，相较于大规模预训练的蛋白质语言模型，“结构序列”使语言模型能够学习更多信息的蛋白质特征，从而增强和优化结构表示。相关代码、模型权重及材料已发布在https://github.com/GouWenrui/CPE-Pro-main.git。

> Protein structures are important for understanding their functions and interactions. Currently, many protein structure prediction methods are enriching the structure database. Discriminating the origin of structures is crucial for distinguishing between experimentally resolved and computationally predicted structures, evaluating the reliability of prediction methods, and guiding downstream biological studies. Building on works in structure prediction, We developed a structure-sensitive supervised deep learning model, Crystal vs Predicted Evaluator for Protein Structure (CPE-Pro), to represent and discriminate the origin of protein structures. CPE-Pro learns the structural information of proteins and captures inter-structural differences to achieve accurate traceability on four data classes, and is expected to be extended to more. Simultaneously, we utilized Foldseek to encode protein structures into "structure-sequence" and trained a protein Structural Sequence Language Model, SSLM. Preliminary experiments demonstrated that, compared to large-scale protein language models pre-trained on vast amounts of amino acid sequences, the "structure-sequences" enable the language model to learn more informative protein features, enhancing and optimizing structural representations. We have provided the code, model weights, and all related materials on https://github.com/GouWenrui/CPE-Pro-main.git.

[Arxiv](https://arxiv.org/abs/2410.15592)