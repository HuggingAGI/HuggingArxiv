# 大规模跨模态预训练模型提升了从心电图中对心血管状态的估算以及心肌病的检测能力：这是一项关于人工智能系统开发和多中心验证的研究

发布时间：2024年11月19日

`其他` `心血管疾病`

> Large-scale cross-modality pretrained model enhances cardiovascular state estimation and cardiomyopathy detection from electrocardiograms: An AI system development and multi-center validation study

# 摘要

> 心血管疾病（CVDs）给早期精准诊断带来了严峻挑战。虽说心脏磁共振成像（CMR）是评估心脏功能及诊断心血管疾病的金标准，但其高昂的成本和复杂的技术限制了其普及性。相较而言，心电图（ECG）为大规模早期筛查带来了曙光。本研究推出了 CardiacNets 这一创新模型，它借助跨模态对比学习和生成式预训练，利用 CMR 的诊断优势来强化 ECG 分析。CardiacNets 具备两大主要功能：其一，利用 ECG 输入评估详尽的心脏功能指标，并筛查潜在的心血管疾病，涵盖冠状动脉疾病、心肌病、心包炎、心力衰竭和肺动脉高压；其二，通过从 ECG 数据生成高质量的 CMR 图像来增强可解释性。我们在两个大规模公共数据集（拥有 41,519 个个体的英国生物银行和包含 501,172 个样本的 MIMIC-IV-ECG）以及三个私有数据集（拥有 410 个个体的 FAHZU、拥有 464 个个体的 SAHZU 和拥有 338 个个体的 QPH）上对所提出的 CardiacNets 进行了训练和验证，结果显示 CardiacNets 始终优于传统的仅用 ECG 的模型，大幅提升了筛查准确率。此外，生成的 CMR 图像为各级经验的医生提供了宝贵的诊断支持。此项概念验证研究凸显了 ECG 如何助力实现对心脏功能评估的跨模态洞察，为在人群层面强化心血管疾病的筛查和诊断开辟了道路。

> Cardiovascular diseases (CVDs) present significant challenges for early and accurate diagnosis. While cardiac magnetic resonance imaging (CMR) is the gold standard for assessing cardiac function and diagnosing CVDs, its high cost and technical complexity limit accessibility. In contrast, electrocardiography (ECG) offers promise for large-scale early screening. This study introduces CardiacNets, an innovative model that enhances ECG analysis by leveraging the diagnostic strengths of CMR through cross-modal contrastive learning and generative pretraining. CardiacNets serves two primary functions: (1) it evaluates detailed cardiac function indicators and screens for potential CVDs, including coronary artery disease, cardiomyopathy, pericarditis, heart failure and pulmonary hypertension, using ECG input; and (2) it enhances interpretability by generating high-quality CMR images from ECG data. We train and validate the proposed CardiacNets on two large-scale public datasets (the UK Biobank with 41,519 individuals and the MIMIC-IV-ECG comprising 501,172 samples) as well as three private datasets (FAHZU with 410 individuals, SAHZU with 464 individuals, and QPH with 338 individuals), and the findings demonstrate that CardiacNets consistently outperforms traditional ECG-only models, substantially improving screening accuracy. Furthermore, the generated CMR images provide valuable diagnostic support for physicians of all experience levels. This proof-of-concept study highlights how ECG can facilitate cross-modal insights into cardiac function assessment, paving the way for enhanced CVD screening and diagnosis at a population level.

[Arxiv](https://arxiv.org/abs/2411.13602)