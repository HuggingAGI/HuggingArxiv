# [我们提出了一种创新的方法，结合了Transformer和CNN技术，以提升蛋白质结构预测的精准度。](https://arxiv.org/abs/2402.19095)

发布时间：2024年02月29日

`Agent`

> A Protein Structure Prediction Approach Leveraging Transformer and CNN Integration

> 蛋白质作为生命的基石，其功能直接受其结构影响，其中二级结构源自一级结构的折叠，三级结构则源于二级结构的进一步弯折与折叠。因此，深入探究蛋白质二级结构对于全面解析蛋白质结构至关重要。尽管机器学习与深度学习技术助力下，蛋白质二级结构预测精度不断提升，但遗憾的是，在面对庞大的蛋白质结构预测需求时，现有进展仍显得捉襟见肘。鉴于深度学习在特征抽取与学习能力上的优越性，本文引入了一种名为DstruCCN的二维融合深度神经网络模型，巧妙结合卷积神经网络（CCN）及监督式Transformer蛋白质语言模型的优势，针对单序列蛋白质结构预测任务。该模型整合两者训练出的特征，预估蛋白质Transformer结合位点矩阵，并运用能量最小化原理重构三维结构。

> Proteins are essential for life, and their structure determines their function. The protein secondary structure is formed by the folding of the protein primary structure, and the protein tertiary structure is formed by the bending and folding of the secondary structure. Therefore, the study of protein secondary structure is very helpful to the overall understanding of protein structure. Although the accuracy of protein secondary structure prediction has continuously improved with the development of machine learning and deep learning, progress in the field of protein structure prediction, unfortunately, remains insufficient to meet the large demand for protein information. Therefore, based on the advantages of deep learning-based methods in feature extraction and learning ability, this paper adopts a two-dimensional fusion deep neural network model, DstruCCN, which uses Convolutional Neural Networks (CCN) and a supervised Transformer protein language model for single-sequence protein structure prediction. The training features of the two are combined to predict the protein Transformer binding site matrix, and then the three-dimensional structure is reconstructed using energy minimization.