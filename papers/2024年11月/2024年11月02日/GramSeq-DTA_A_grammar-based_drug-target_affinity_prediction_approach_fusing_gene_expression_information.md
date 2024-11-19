# GramSeq-DTA：一种融合基因表达信息的基于语法规则的药物 - 靶点亲和性预测手段

发布时间：2024年11月02日

`其他` `药物研发` `生物医学`

> GramSeq-DTA: A grammar-based drug-target affinity prediction approach fusing gene expression information

# 摘要

> 药物 - 靶点亲和力（DTA）预测在药物研发中至关重要。药物和靶点的有效表征对精准预测意义重大。采用基于 1D 字符串的药物和靶点表征是常见手段，在 DTA 预测中成果斐然。但此类方法缺少原子和键相对位置的信息。为克服这一局限，基于图的表征已在一定程度上得以运用。然而，仅着眼于药物和靶点的结构层面，对于精确的 DTA 预测或许不足。在基因层面整合这些药物的功能方面能够增强模型的预测能力。为填补此空缺，我们提出了 GramSeq - DTA，它将化学扰动信息与药物和靶点的结构信息加以融合。我们运用语法变分自编码器（GVAE）进行药物特征提取，并采用两种不同方式进行蛋白质特征提取：卷积神经网络（CNN）和循环神经网络（RNN）。化学扰动数据源自 L1000 项目，该项目提供了所选药物引发的基因上调和下调的信息。对这类化学扰动信息加以处理，准备一个紧凑的数据集，作为药物的功能特征集。通过在模型中整合药物、基因和靶点的特征，在广泛使用的 DTA 数据集（BindingDB、Davis 和 KIBA）上验证时，我们的方法优于当下最先进的 DTA 预测模型。此项工作通过融合生物实体的结构和功能方面，为 DTA 预测提供了新颖且实用的途径，并激励在多模态 DTA 预测领域开展进一步的研究。

> Drug-target affinity (DTA) prediction is a critical aspect of drug discovery. The meaningful representation of drugs and targets is crucial for accurate prediction. Using 1D string-based representations for drugs and targets is a common approach that has demonstrated good results in drug-target affinity prediction. However, these approach lacks information on the relative position of the atoms and bonds. To address this limitation, graph-based representations have been used to some extent. However, solely considering the structural aspect of drugs and targets may be insufficient for accurate DTA prediction. Integrating the functional aspect of these drugs at the genetic level can enhance the prediction capability of the models. To fill this gap, we propose GramSeq-DTA, which integrates chemical perturbation information with the structural information of drugs and targets. We applied a Grammar Variational Autoencoder (GVAE) for drug feature extraction and utilized two different approaches for protein feature extraction: Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN). The chemical perturbation data is obtained from the L1000 project, which provides information on the upregulation and downregulation of genes caused by selected drugs. This chemical perturbation information is processed, and a compact dataset is prepared, serving as the functional feature set of the drugs. By integrating the drug, gene, and target features in the model, our approach outperforms the current state-of-the-art DTA prediction models when validated on widely used DTA datasets (BindingDB, Davis, and KIBA). This work provides a novel and practical approach to DTA prediction by merging the structural and functional aspects of biological entities, and it encourages further research in multi-modal DTA prediction.

[Arxiv](https://arxiv.org/abs/2411.01422)