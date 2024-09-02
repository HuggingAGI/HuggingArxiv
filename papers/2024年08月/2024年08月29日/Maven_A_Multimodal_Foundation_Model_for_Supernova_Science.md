# Maven：超新星科学的多模态基石模型

发布时间：2024年08月29日

`LLM应用` `天文学` `时域天体物理学`

> Maven: A Multimodal Foundation Model for Supernova Science

# 摘要

> 在天文学领域，高质量观测数据稀缺，而低质量或合成数据丰富。时域天体物理学中，光度观测的超新星数量远超光谱观测，差距巨大。目前，尚无模型能在共同背景下理解这些观测数据。对比学习，因其能将不同数据模态对齐，为解决此问题提供了新思路。我们推出了 Maven，首个超新星科学基础模型。通过预训练对齐合成超新星的光度和光谱，再在实际观测数据上微调，Maven 在分类和红移估计上表现卓越。研究表明，预训练提升整体性能。未来，Maven 将成为处理大型、未标记、多模态时域数据的关键工具。

> A common setting in astronomy is the availability of a small number of high-quality observations, and larger amounts of either lower-quality observations or synthetic data from simplified models. Time-domain astrophysics is a canonical example of this imbalance, with the number of supernovae observed photometrically outpacing the number observed spectroscopically by multiple orders of magnitude. At the same time, no data-driven models exist to understand these photometric and spectroscopic observables in a common context. Contrastive learning objectives, which have grown in popularity for aligning distinct data modalities in a shared embedding space, provide a potential solution to extract information from these modalities. We present Maven, the first foundation model for supernova science. To construct Maven, we first pre-train our model to align photometry and spectroscopy from 0.5M synthetic supernovae using a constrastive objective. We then fine-tune the model on 4,702 observed supernovae from the Zwicky Transient Facility. Maven reaches state-of-the-art performance on both classification and redshift estimation, despite the embeddings not being explicitly optimized for these tasks. Through ablation studies, we show that pre-training with synthetic data improves overall performance. In the upcoming era of the Vera C. Rubin Observatory, Maven serves as a Rosetta Stone for leveraging large, unlabeled and multimodal time-domain datasets.

[Arxiv](https://arxiv.org/abs/2408.16829)