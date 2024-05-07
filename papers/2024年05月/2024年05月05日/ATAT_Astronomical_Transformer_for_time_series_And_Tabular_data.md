# ATAT：一种专门针对时间序列与表格数据的天文变换模型

发布时间：2024年05月05日

`分类：Agent

这篇论文描述了一种名为ATAT的新型分类模型，它被设计用于处理和分类新一代观测设备（如维拉·鲁宾天文台及其空间和时间遗产调查）产生的天文时间序列数据。这个模型在实际生产环境中进行了测试，并且在与现有的分类器相比时表现出了更好的性能。由于这个模型被设计为一个自动化的系统，用于处理和分类大量的天文数据，因此它属于"Agent"类别。这个类别通常包括那些被设计为执行特定任务或服务的智能系统或算法。` `天文学` `机器学习`

> ATAT: Astronomical Transformer for time series And Tabular data

# 摘要

> 随着维拉·鲁宾天文台及其空间和时间遗产调查（LSST）等新一代观测设备的问世，时域天文学研究迎来了新的机遇。为此，我们推出了扩展的LSST天文时间序列分类挑战（ELAsTiCC），旨在检验系统处理模拟LSST数据流的能力。本文介绍的ATAT，即天文变换器，是ALERCE警报系统为分类新一代警报流中的光曲线而设计的一种新型分类模型。在ELAsTiCC的首轮竞赛中，ATAT已在实际生产环境中进行了测试。ATAT由两个变换模型构成，分别采用创新的时间调制技术和分位数特征标记机制来编码光曲线和特征。该模型在不同的光曲线、元数据以及基于光曲线计算出的特征组合上进行了训练。在与ALERCE当前使用的平衡层次随机森林（BHRF）分类器的比较中，ATAT在20个类别上达到了82.9%的宏观F1分数，超越了基于429个人工特征训练的BHRF模型的79.4%。ATAT的成功展示了利用变换器多模态架构结合光曲线和表格数据进行警报分类的潜力，为类似维拉·鲁宾天文台这样的新一代大型望远镜在现实世界中的数据处理提供了新的解决方案。

> The advent of next-generation survey instruments, such as the Vera C. Rubin Observatory and its Legacy Survey of Space and Time (LSST), is opening a window for new research in time-domain astronomy. The Extended LSST Astronomical Time-Series Classification Challenge (ELAsTiCC) was created to test the capacity of brokers to deal with a simulated LSST stream. We describe ATAT, the Astronomical Transformer for time series And Tabular data, a classification model conceived by the ALeRCE alert broker to classify light-curves from next-generation alert streams. ATAT was tested in production during the first round of the ELAsTiCC campaigns. ATAT consists of two Transformer models that encode light curves and features using novel time modulation and quantile feature tokenizer mechanisms, respectively. ATAT was trained on different combinations of light curves, metadata, and features calculated over the light curves. We compare ATAT against the current ALeRCE classifier, a Balanced Hierarchical Random Forest (BHRF) trained on human-engineered features derived from light curves and metadata. When trained on light curves and metadata, ATAT achieves a macro F1-score of 82.9 +- 0.4 in 20 classes, outperforming the BHRF model trained on 429 features, which achieves a macro F1-score of 79.4 +- 0.1. The use of Transformer multimodal architectures, combining light curves and tabular data, opens new possibilities for classifying alerts from a new generation of large etendue telescopes, such as the Vera C. Rubin Observatory, in real-world brokering scenarios.

[Arxiv](https://arxiv.org/abs/2405.03078)