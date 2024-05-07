# ATAT：一种专为时间序列和表格数据设计的天文变换模型

发布时间：2024年05月05日

`分类：Agent

这篇论文摘要描述了一个用于时间序列和表格数据分类的模型，即天文变换器（ATAT），它专门用于对新一代警报流中的光曲线进行分类。这个模型在实际生产环境中进行了测试，并与现有的分类器进行了比较。由于这个模型是一个用于特定任务（天文学数据分类）的智能代理，因此它属于"Agent"类别。` `天文学` `机器学习`

> ATAT: Astronomical Transformer for time series And Tabular data

# 摘要

> 随着新一代观测设备如薇拉·C·鲁宾天文台及其“空间和时间遗产调查”（LSST）的问世，时域天文学研究迎来了新的机遇。为了检验处理模拟LSST数据流的能力，我们创建了扩展的LSST天文时间序列分类挑战（ELAsTiCC）。本文介绍了由ALERCE警报系统设计的天文变换器（ATAT），这是一种用于时间序列和表格数据的分类模型，专门用于对新一代警报流中的光曲线进行分类。在ELAsTiCC的首轮竞赛中，ATAT在实际生产环境中接受了测试。ATAT由两个变换模型构成，分别采用创新的时间调制和分位数特征标记技术来编码光曲线和特征。该模型在不同的光曲线、元数据以及基于光曲线计算出的特征组合上进行了训练。我们将其与ALERCE现有的平衡层次随机森林（BHRF）分类器进行了对比，后者是基于人工提取的光曲线和元数据特征进行训练的。在光曲线和元数据上训练时，ATAT在20个类别中达到了82.9%的宏观F1分数，超越了基于429个特征训练的BHRF模型的79.4%。采用变换器多模态架构，融合光曲线与表格数据，为新一代大视场望远镜，如薇拉·C·鲁宾天文台，提供了在现实警报处理场景中的分类新方案。

> The advent of next-generation survey instruments, such as the Vera C. Rubin Observatory and its Legacy Survey of Space and Time (LSST), is opening a window for new research in time-domain astronomy. The Extended LSST Astronomical Time-Series Classification Challenge (ELAsTiCC) was created to test the capacity of brokers to deal with a simulated LSST stream. We describe ATAT, the Astronomical Transformer for time series And Tabular data, a classification model conceived by the ALeRCE alert broker to classify light-curves from next-generation alert streams. ATAT was tested in production during the first round of the ELAsTiCC campaigns. ATAT consists of two Transformer models that encode light curves and features using novel time modulation and quantile feature tokenizer mechanisms, respectively. ATAT was trained on different combinations of light curves, metadata, and features calculated over the light curves. We compare ATAT against the current ALeRCE classifier, a Balanced Hierarchical Random Forest (BHRF) trained on human-engineered features derived from light curves and metadata. When trained on light curves and metadata, ATAT achieves a macro F1-score of 82.9 +- 0.4 in 20 classes, outperforming the BHRF model trained on 429 features, which achieves a macro F1-score of 79.4 +- 0.1. The use of Transformer multimodal architectures, combining light curves and tabular data, opens new possibilities for classifying alerts from a new generation of large etendue telescopes, such as the Vera C. Rubin Observatory, in real-world brokering scenarios.

[Arxiv](https://arxiv.org/abs/2405.03078)