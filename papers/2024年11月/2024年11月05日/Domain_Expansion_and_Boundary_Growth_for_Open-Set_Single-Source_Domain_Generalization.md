# 领域扩展和边界增长用于开放集单源领域泛化

发布时间：2024年11月05日

`其他` `图像分类` `域泛化`

> Domain Expansion and Boundary Growth for Open-Set Single-Source Domain Generalization

# 摘要

> 开放集单源域泛化旨在使用单个源域来学习一个强大的模型，该模型可以泛化到具有域偏移和标签偏移的未知目标域。源域的稀缺性和目标域的未知数据分布给域不变特征学习和未知类别识别带来了巨大挑战。在本文中，我们提出了一种基于域扩展和边界增长的新学习方法，以扩展稀缺的源样本并扩大已知类之间的边界，从而间接拓宽已知类和未知类之间的边界。具体而言，我们通过在源数据上同时使用背景抑制和风格增强来合成新样本，从而实现域扩展。然后，我们迫使模型从合成样本中提取一致的知识，以便模型可以学习域不变信息。此外，我们在训练多二进制分类器时，通过将边缘图用作样本的附加模态来实现跨类别的边界增长。通过这种方式，它扩大了内点和外点之间的边界，从而在开放集泛化期间提高了未知类别的识别能力。大量实验表明，我们的方法可以取得显著的改进，并在几个跨域图像分类数据集上达到最先进的性能。

> Open-set single-source domain generalization aims to use a single-source domain to learn a robust model that can be generalized to unknown target domains with both domain shifts and label shifts. The scarcity of the source domain and the unknown data distribution of the target domain pose a great challenge for domain-invariant feature learning and unknown class recognition. In this paper, we propose a novel learning approach based on domain expansion and boundary growth to expand the scarce source samples and enlarge the boundaries across the known classes that indirectly broaden the boundary between the known and unknown classes. Specifically, we achieve domain expansion by employing both background suppression and style augmentation on the source data to synthesize new samples. Then we force the model to distill consistent knowledge from the synthesized samples so that the model can learn domain-invariant information. Furthermore, we realize boundary growth across classes by using edge maps as an additional modality of samples when training multi-binary classifiers. In this way, it enlarges the boundary between the inliers and outliers, and consequently improves the unknown class recognition during open-set generalization. Extensive experiments show that our approach can achieve significant improvements and reach state-of-the-art performance on several cross-domain image classification datasets.

[Arxiv](https://arxiv.org/abs/2411.02920)