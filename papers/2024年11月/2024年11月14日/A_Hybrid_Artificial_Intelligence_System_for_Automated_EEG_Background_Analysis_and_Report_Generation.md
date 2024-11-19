# 一个用于脑电图背景自动分析与报告生成的混合式人工智能系统

发布时间：2024年11月14日

`LLM应用` `神经科`

> A Hybrid Artificial Intelligence System for Automated EEG Background Analysis and Report Generation

# 摘要

> 脑电图（EEG）在各类神经疾病的诊断中发挥着关键作用。然而，小型医院和诊所往往缺少先进的脑电图信号分析系统，人工解读脑电图时容易出错。本研究推出了一种创新的混合人工智能（AI）系统，用于自动解读脑电图背景活动和生成报告。此系统融合了用于后优势节律（PDR）预测的深度学习模型、无监督的伪影去除以及专家设计的异常检测算法。在 PDR 预测方面，采用了 1530 个有标记的脑电图，最优集成模型的平均绝对误差（MAE）为 0.237，均方根误差（RMSE）为 0.359，在 0.6Hz 误差内准确率达 91.8%，在 1.2Hz 误差内准确率达 99%。该 AI 系统在检测广泛性背景减慢方面明显优于神经科医生（p = 0.02；F1：AI 为 0.93，神经科医生为 0.82），在局灶性异常检测方面有所改进，不过统计学上不显著（p = 0.79；F1：AI 为 0.71，神经科医生为 0.55）。在内部数据集和坦普尔大学异常脑电图语料库上的验证表现出一致的性能（F1 分别为 0.884 和 0.835；p = 0.66），证实了其通用性。使用大型语言模型（LLMs）生成报告的准确率达 100%，并得到另外三个独立的 LLMs 验证。这种混合 AI 系统为资源有限的场景下的脑电图解读提供了一种易于扩展且精准的解决方案，助力神经科医生提升诊断准确率，降低误诊率。

> Electroencephalography (EEG) plays a crucial role in the diagnosis of various neurological disorders. However, small hospitals and clinics often lack advanced EEG signal analysis systems and are prone to misinterpretation in manual EEG reading. This study proposes an innovative hybrid artificial intelligence (AI) system for automatic interpretation of EEG background activity and report generation. The system combines deep learning models for posterior dominant rhythm (PDR) prediction, unsupervised artifact removal, and expert-designed algorithms for abnormality detection. For PDR prediction, 1530 labeled EEGs were used, and the best ensemble model achieved a mean absolute error (MAE) of 0.237, a root mean square error (RMSE) of 0.359, an accuracy of 91.8% within a 0.6Hz error, and an accuracy of 99% within a 1.2Hz error. The AI system significantly outperformed neurologists in detecting generalized background slowing (p = 0.02; F1: AI 0.93, neurologists 0.82) and demonstrated improved focal abnormality detection, although not statistically significant (p = 0.79; F1: AI 0.71, neurologists 0.55). Validation on both an internal dataset and the Temple University Abnormal EEG Corpus showed consistent performance (F1: 0.884 and 0.835, respectively; p = 0.66), demonstrating generalizability. The use of large language models (LLMs) for report generation demonstrated 100% accuracy, verified by three other independent LLMs. This hybrid AI system provides an easily scalable and accurate solution for EEG interpretation in resource-limited settings, assisting neurologists in improving diagnostic accuracy and reducing misdiagnosis rates.

[Arxiv](https://arxiv.org/abs/2411.09874)