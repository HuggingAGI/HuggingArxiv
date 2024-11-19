# 一种用于多模态中风风险预测的自监督式模型

发布时间：2024年11月14日

`其他` `中风预测`

> A Self-Supervised Model for Multi-modal Stroke Risk Prediction

# 摘要

> 预测中风风险是个复杂难题，整合各类临床上可用的数据模式可助力解决。本研究推出了一个自监督多模态框架，它融合了 3D 脑成像、临床数据及图像衍生特征，旨在发病前优化中风风险预测。借助大型未标注临床数据集，该框架能获取图像和表格数据模式间的互补与协同信息。我们的方法基于对比学习框架，将对比语言 - 图像预训练与图像 - 表格匹配模块相结合，从而在共享潜在空间中更优地对齐多模态数据表示。此模型在英国生物银行上训练，涵盖结构性脑 MRI 和临床数据。我们在不同的冻结和可训练模型设置下，通过表格、图像和图像 - 表格组合，将其性能与前沿的单模态和多模态方法进行基准对比。所提模型在 ROC - AUC 中比自监督表格（图像）方法高 2.6％（2.6％），平衡准确率高 3.3％（5.6％）。另外，相比最佳多模态监督模型，其平衡准确率提升 7.6％。借助可解释工具，我们的方法实现了表格和图像数据的更优整合，提供了更丰富且更对齐的嵌入。梯度加权类激活映射热图进一步揭示了文献中常与脑老化、中风风险和临床结果相关的激活脑区。这一强大的自监督多模态框架超越了中风风险预测的现有先进方法，为未来整合各类数据模式以推动临床预测建模的研究奠定了坚实基础。

> Predicting stroke risk is a complex challenge that can be enhanced by integrating diverse clinically available data modalities. This study introduces a self-supervised multimodal framework that combines 3D brain imaging, clinical data, and image-derived features to improve stroke risk prediction prior to onset. By leveraging large unannotated clinical datasets, the framework captures complementary and synergistic information across image and tabular data modalities. Our approach is based on a contrastive learning framework that couples contrastive language-image pretraining with an image-tabular matching module, to better align multimodal data representations in a shared latent space. The model is trained on the UK Biobank, which includes structural brain MRI and clinical data. We benchmark its performance against state-of-the-art unimodal and multimodal methods using tabular, image, and image-tabular combinations under diverse frozen and trainable model settings. The proposed model outperformed self-supervised tabular (image) methods by 2.6% (2.6%) in ROC-AUC and by 3.3% (5.6%) in balanced accuracy. Additionally, it showed a 7.6% increase in balanced accuracy compared to the best multimodal supervised model. Through interpretable tools, our approach demonstrated better integration of tabular and image data, providing richer and more aligned embeddings. Gradient-weighted Class Activation Mapping heatmaps further revealed activated brain regions commonly associated in the literature with brain aging, stroke risk, and clinical outcomes. This robust self-supervised multimodal framework surpasses state-of-the-art methods for stroke risk prediction and offers a strong foundation for future studies integrating diverse data modalities to advance clinical predictive modelling.

[Arxiv](https://arxiv.org/abs/2411.09822)