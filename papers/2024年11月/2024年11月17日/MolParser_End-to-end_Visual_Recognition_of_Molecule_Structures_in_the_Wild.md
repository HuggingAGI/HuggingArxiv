# MolParser：实现对野外分子结构的端到端视觉识别

发布时间：2024年11月17日

`其他`

> MolParser: End-to-end Visual Recognition of Molecule Structures in the Wild

# 摘要

> 近几十年来，化学方面的出版物和专利数量迅猛增长。大量关键信息蕴含于分子结构图形之中，这使得大规模文献检索变得复杂，也限制了大型语言模型在生物、化学和制药等领域的应用。精确化学结构的自动提取极为重要。然而，现实文档中众多马库什结构的存在，以及分子图像质量、绘图风格和噪声的差异，严重制约了现有光学化学结构识别（OCSR）方法的性能。我们推出了 MolParser，这是一种全新的端到端 OCSR 方法，能够从现实世界的文档中高效、精准地识别化学结构，包括棘手的马库什结构。我们运用扩展的 SMILES 编码规则来标注训练数据集。基于此规则，我们构建了 MolParser-7M，据了解这是目前最大的标注分子图像数据集。在利用大量合成数据的同时，我们通过主动学习的方法将大量真实数据，特别是从真实专利和科学文献中截取的样本，融入训练过程。我们采用课程学习的方式训练了端到端的分子图像描述模型 MolParser。MolParser 在多数情况下都远超经典方法和基于学习的方法，在下游应用方面颇具潜力。该数据集可供公众使用。

> In recent decades, chemistry publications and patents have increased rapidly. A significant portion of key information is embedded in molecular structure figures, complicating large-scale literature searches and limiting the application of large language models in fields such as biology, chemistry, and pharmaceuticals. The automatic extraction of precise chemical structures is of critical importance. However, the presence of numerous Markush structures in real-world documents, along with variations in molecular image quality, drawing styles, and noise, significantly limits the performance of existing optical chemical structure recognition (OCSR) methods. We present MolParser, a novel end-to-end OCSR method that efficiently and accurately recognizes chemical structures from real-world documents, including difficult Markush structure. We use a extended SMILES encoding rule to annotate our training dataset. Under this rule, we build MolParser-7M, the largest annotated molecular image dataset to our knowledge. While utilizing a large amount of synthetic data, we employed active learning methods to incorporate substantial in-the-wild data, specifically samples cropped from real patents and scientific literature, into the training process. We trained an end-to-end molecular image captioning model, MolParser, using a curriculum learning approach. MolParser significantly outperforms classical and learning-based methods across most scenarios, with potential for broader downstream applications. The dataset is publicly available.

[Arxiv](https://arxiv.org/abs/2411.11098)