# PFML：实现对时间序列数据的自监督学习且避免表示崩溃

发布时间：2024年11月15日

`其他` `时间序列数据`

> PFML: Self-Supervised Learning of Time-Series Data Without Representation Collapse

# 摘要

> 自我监督学习（SSL）是一种依靠数据内在结构引导学习进程的数据驱动型学习方式。和依赖外部标签的监督学习不同，SSL 借助数据的固有特性生成自身的监督信号。然而，SSL 方法常出现表示崩溃的问题，即模型输出恒定不变且与输入无关的特征表示。这一问题阻碍了 SSL 方法在新数据模式中的潜在应用，因为避免表示崩溃会耗费研究人员大量的时间和精力。本文引入了一种针对时间序列数据的新型 SSL 算法，名为从掩码潜在变量预测泛函（PFML）。PFML 并非直接预测掩码输入信号或其潜在表示，而是依据未掩码嵌入的序列，对与掩码嵌入对应的输入信号的统计泛函进行预测来运作。该算法旨在规避表示崩溃，从而能直接应用于不同的时间序列数据领域，比如临床数据中的新型传感器模式。我们通过三个不同数据模式下复杂的现实分类任务验证了 PFML 的有效性：基于多传感器惯性测量单元数据的婴儿姿势和运动分类、源于语音数据的情绪识别以及来自脑电图数据的睡眠阶段分类。结果显示，PFML 优于概念相近的既有 SSL 方法，与当前最先进的 SSL 方法相比也不逊色，而且概念更简单，不会出现表示崩溃的情况。

> Self-supervised learning (SSL) is a data-driven learning approach that utilizes the innate structure of the data to guide the learning process. In contrast to supervised learning, which depends on external labels, SSL utilizes the inherent characteristics of the data to produce its own supervisory signal. However, one frequent issue with SSL methods is representation collapse, where the model outputs a constant input-invariant feature representation. This issue hinders the potential application of SSL methods to new data modalities, as trying to avoid representation collapse wastes researchers' time and effort. This paper introduces a novel SSL algorithm for time-series data called Prediction of Functionals from Masked Latents (PFML). Instead of predicting masked input signals or their latent representations directly, PFML operates by predicting statistical functionals of the input signal corresponding to masked embeddings, given a sequence of unmasked embeddings. The algorithm is designed to avoid representation collapse, rendering it straightforwardly applicable to different time-series data domains, such as novel sensor modalities in clinical data. We demonstrate the effectiveness of PFML through complex, real-life classification tasks across three different data modalities: infant posture and movement classification from multi-sensor inertial measurement unit data, emotion recognition from speech data, and sleep stage classification from EEG data. The results show that PFML is superior to a conceptually similar pre-existing SSL method and competitive against the current state-of-the-art SSL method, while also being conceptually simpler and without suffering from representation collapse.

[Arxiv](https://arxiv.org/abs/2411.10087)