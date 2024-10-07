# 运动生成将何去何从？从大型语言模型迈向大型运动模型。

发布时间：2024年10月04日

`LLM应用` `运动科学` `人工智能`

> Quo Vadis, Motion Generation? From Large Language Models to Large Motion Models

# 摘要

> 受 LLM 成功启发，人体运动理解领域正转向开发大型运动模型。尽管有所进展，但现有最先进模型仍远未实现通用性，主要因缺乏大规模高质量运动数据。为此，我们推出 MotionBase，首个百万级运动生成基准，数据量是之前最大数据集的 15 倍，并包含层次化详细文本描述的多模态数据。利用此数据集，我们的大型运动模型在广泛动作品类中表现优异，包括未见动作。通过系统研究，我们强调了扩展数据和模型规模的重要性，合成数据和伪标签在降低数据获取成本中起关键作用。此外，我们揭示了现有评估指标的局限性，特别是处理域外文本指令的问题。我们还提出了一种新颖的 2D 无查找运动令牌化方法，保留运动信息并扩展码本容量，进一步增强模型代表能力。MotionBase 的发布及研究见解，有望推动更强大多功能运动生成模型的发展。

> Inspired by the recent success of LLMs, the field of human motion understanding has increasingly shifted towards the development of large motion models. Despite some progress, current state-of-the-art works remain far from achieving truly generalist models, largely due to the lack of large-scale, high-quality motion data. To address this, we present MotionBase, the first million-level motion generation benchmark, offering 15 times the data volume of the previous largest dataset, and featuring multimodal data with hierarchically detailed text descriptions. By leveraging this vast dataset, our large motion model demonstrates strong performance across a broad range of motions, including unseen ones. Through systematic investigation, we underscore the importance of scaling both data and model size, with synthetic data and pseudo labels playing a crucial role in mitigating data acquisition costs. Moreover, our research reveals the limitations of existing evaluation metrics, particularly in handling out-of-domain text instructions -- an issue that has long been overlooked. In addition to these, we introduce a novel 2D lookup-free approach for motion tokenization, which preserves motion information and expands codebook capacity, further enhancing the representative ability of large motion models. The release of MotionBase and the insights gained from this study are expected to pave the way for the development of more powerful and versatile motion generation models.

[Arxiv](https://arxiv.org/abs/2410.03311)