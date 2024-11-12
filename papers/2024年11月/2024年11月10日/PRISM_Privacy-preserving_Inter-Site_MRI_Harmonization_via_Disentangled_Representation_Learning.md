# PRISM：通过解缠表示学习实现跨站点 MRI 协调的隐私保护

发布时间：2024年11月10日

`其他` `MRI 研究`

> PRISM: Privacy-preserving Inter-Site MRI Harmonization via Disentangled Representation Learning

# 摘要

> 多站点 MRI 研究经常受到因方法、硬件和采集协议的差异而产生的站点特定变化的影响，从而损害了临床 AI/ML 任务的准确性和可靠性。我们提出了 PRISM（保护隐私的站点间 MRI 协调），这是一个用于协调多个站点的结构性脑 MRI 同时保护数据隐私的新型深度学习框架。PRISM 采用具有对比学习和变分推理的双分支自动编码器，将解剖特征与风格和站点特定变化分离，能够在无需受试者移动或多种 MRI 模式的情况下实现未配对的图像转换。我们的模块化设计允许协调到任何目标站点，并在无需重新训练或微调的情况下无缝集成新站点。使用多站点结构性 MRI 数据，我们展示了 PRISM 在诸如脑组织分割等下游任务中的有效性，并通过多次实验验证了其协调性能。我们的框架解决了医学 AI/ML 中的关键挑战，包括数据隐私、分布变化、模型泛化性和可解释性。代码可在 https://github.com/saranggalada/PRISM 获得。

> Multi-site MRI studies often suffer from site-specific variations arising from differences in methodology, hardware, and acquisition protocols, thereby compromising accuracy and reliability in clinical AI/ML tasks. We present PRISM (Privacy-preserving Inter-Site MRI Harmonization), a novel Deep Learning framework for harmonizing structural brain MRI across multiple sites while preserving data privacy. PRISM employs a dual-branch autoencoder with contrastive learning and variational inference to disentangle anatomical features from style and site-specific variations, enabling unpaired image translation without traveling subjects or multiple MRI modalities. Our modular design allows harmonization to any target site and seamless integration of new sites without the need for retraining or fine-tuning. Using multi-site structural MRI data, we demonstrate PRISM's effectiveness in downstream tasks such as brain tissue segmentation and validate its harmonization performance through multiple experiments. Our framework addresses key challenges in medical AI/ML, including data privacy, distribution shifts, model generalizability and interpretability. Code is available at https://github.com/saranggalada/PRISM

[Arxiv](https://arxiv.org/abs/2411.06513)