# PRIMUS：通过多模态自监督来预训练 IMU 编码器

发布时间：2024年11月22日

`其他` `健康与保健` `人体动作感知`

> PRIMUS: Pretraining IMU Encoders with Multimodal Self-Supervision

# 摘要

> 通过个人设备中嵌入的惯性测量单元（IMUs）来感知人体动作，在健康与保健领域已促成重大应用。然而，有标签的 IMU 数据稀缺，我们能够收集无标签或弱标签的 IMU 数据来对人体动作进行建模。就视频或文本模式而言，“预训练与适应”的方法借助大量无标签或弱标签数据进行预训练，构建强大的特征提取器，再利用有限的有标签数据适应特定任务。此方法在 IMU 领域未被广泛运用，原因有二：其一，在 IMU 情境中对预训练方法认识不足；其二，能跨数据集通用的开源预训练模型鲜少公开可得。本文中，我们通过提出 PRIMUS（一种预训练 IMU 编码器的方法）来解决第一个问题。我们对各类自监督和多模态学习预训练目标展开了系统且统一的评估。我们的发现表明，采用融合了自监督、多模态监督和最近邻监督的 PRIMUS，能显著提升下游性能。在每个类别有标签样本少于 500 个的情况下，相较于最先进的多模态训练方法，PRIMUS 在留存的测试数据中能将下游性能有效提高多达 15％。为惠及更广大的群体，我们的代码和预训练的 IMU 编码器在发布时将在 github.com/nokia-bell-labs 上公开。

> Sensing human motions through Inertial Measurement Units (IMUs) embedded in personal devices has enabled significant applications in health and wellness. While labeled IMU data is scarce, we can collect unlabeled or weakly labeled IMU data to model human motions. For video or text modalities, the "pretrain and adapt" approach utilizes large volumes of unlabeled or weakly labeled data for pretraining, building a strong feature extractor, followed by adaptation to specific tasks using limited labeled data. This approach has not been widely adopted in the IMU domain for two reasons: (1) pretraining methods are poorly understood in the context of IMU, and (2) open-source pretrained models that generalize across datasets are rarely publicly available. In this paper, we aim to address the first issue by proposing PRIMUS, a method for PRetraining IMU encoderS. We conduct a systematic and unified evaluation of various self-supervised and multimodal learning pretraining objectives. Our findings indicate that using PRIMUS, which combines self-supervision, multimodal supervision, and nearest-neighbor supervision, can significantly enhance downstream performance. With fewer than 500 labeled samples per class, PRIMUS effectively enhances downstream performance by up to 15% in held-out test data, compared to the state-of-the-art multimodal training method. To benefit the broader community, our code and pre-trained IMU encoders will be made publicly available at github.com/nokia-bell-labs upon publication.

[Arxiv](https://arxiv.org/abs/2411.15127)