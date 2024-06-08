# 利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。

发布时间：2024年06月06日

`Agent

理由：这篇论文描述了一种多模态神经网络，该网络能够从多波段地面观测数据中区分恒星、星系和类星体。这种网络可以被视为一个智能Agent，因为它能够处理输入数据（多波段图像和光谱信息），并输出对天文源的分类结果。该Agent通过学习和应用特定的算法（卷积神经网络和人工神经网络）来执行其任务，并在实际的天文数据集上展示了高准确率和分类性能。这与Agent分类下的定义相符，即Agent是能够感知环境并采取行动以达到目标的实体。` `天文学` `数据分类`

> Morpho-Photometric Classification of KiDS DR5 Sources Based on Neural Networks: A Comprehensive Star-Quasar-Galaxy Catalog

# 摘要

> 我们开发了一种创新的多模态神经网络，用于从光学到近红外的多波段地面观测中区分恒星、星系和类星体。该网络结合了卷积神经网络学习$r$波段图像形态特征和人工神经网络提取光谱能量分布信息的能力。利用KiDS第5次数据发布的9波段数据，我们的网络在全连接层的辅助下，实现了对天文源的精确分类。在斯隆数字天空调查与KiDS交叉匹配的样本上训练后，该模型在独立测试集上的准确率高达98.76%，各类别的F1分数均超过95%。通过调整输出概率阈值，我们实现了高纯度分类，尽管完整性略有下降。此外，我们还验证了该网络在外部目录上的表现，成功分类了99.74%的纯恒星样本和99.74%的外部星系样本。最终，我们将该网络应用于27,334,751个KiDS DR5源，生成了一个新的分类目录，展示了其在大型光度调查中对恒星、类星体和星系进行高效、稳健分类的能力。

> We present a novel multimodal neural network for classifying astronomical sources in multiband ground-based observations, from optical to near infrared, to separate sources in stars, galaxies and quasars. Our approach combines a convolutional neural network branch for learning morphological features from $r$-band images with an artificial neural network branch for extracting spectral energy distribution (SED) information. Specifically, we have used 9-band optical ($ugri$) and NIR ($ZYHJK_s$) data from the Kilo-Degree Survey (KiDS) Data Release 5. The two branches of the network are concatenated and feed into fully-connected layers for final classification. We train the network on a spectroscopically confirmed sample from the Sloan Digital Sky Survey cross-matched with KiDS. The trained model achieves 98.76\% overall accuracy on an independent testing dataset, with F1 scores exceeding 95\% for each class. Raising the output probability threshold, we obtain higher purity at the cost of a lower completeness. We have also validated the network using external catalogs cross-matched with KiDS, correctly classifying 99.74\% of a pure star sample selected from Gaia parallaxes and proper motions, and 99.74\% of an external galaxy sample from the Galaxy and Mass Assembly survey, adjusted for low-redshift contamination. We apply the trained network to 27,334,751 KiDS DR5 sources with $r \leqslant 23$ mag to generate a new classification catalog. This multimodal neural network successfully leverages both morphological and SED information to enable efficient and robust classification of stars, quasars, and galaxies in large photometric surveys.

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x1.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x2.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x3.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x4.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x5.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x6.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x7.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x8.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x9.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x10.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x11.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x12.png)

![利用神经网络对KiDS DR5源进行形态-光度分类，构建了一个详尽的恒星-类星体-星系目录。](../../../paper_images/2406.03797/x13.png)

[Arxiv](https://arxiv.org/abs/2406.03797)