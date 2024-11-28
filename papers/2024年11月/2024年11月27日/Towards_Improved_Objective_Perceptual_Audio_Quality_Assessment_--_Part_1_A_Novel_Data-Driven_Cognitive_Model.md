# 向着改进客观感知音频质量评估迈进——第 1 部分：一种新型的数据驱动认知模型

发布时间：2024年11月27日

`其他` `机器学习`

> Towards Improved Objective Perceptual Audio Quality Assessment -- Part 1: A Novel Data-Driven Cognitive Model

# 摘要

> 高效的音频质量评估对于优化音频编解码器的开发至关重要。一直以来，客观评估工具不断发展，能够依据算法从作为质量评判黄金标准的主观评估中预测质量评级。众多此类工具借助感知听觉模型提取音频特征，并以机器学习算法和主观分数为训练数据，将其映射到基本的音频质量得分预测上。然而，现有的工具在质量预测的泛化方面存在难题，尤其在面对未知信号和失真类型时。使用非波形保留参数技术编码的信号存在时，这一问题尤为突出。为应对这些挑战，此项分为两部分的工作对音频质量感知评估（PEAQ - ITU-R BS.1387-1）建议予以扩展。第一部分着重提升泛化能力，第二部分针对音频编码中精确的空间音频质量测量。
  为增强预测的泛化能力，本文（第一部分）引入了一种创新的机器学习方法，利用主观数据对音频质量感知的认知层面进行建模。所提方法通过自适应为不同的失真度量加权，来对可听失真的感知严重程度加以建模。权重通过能捕捉失真显著度和认知效果关系的交互成本函数确定。与其他机器学习方法及已有的工具相比，所提出的架构在先前未见过的主观质量分数的大型数据库上，实现了更高的预测准确率。基于感知的模型为通用机器学习算法提供了更易管理的替代方案，使得在无需完全重新训练的情况下，能够对多维质量测量进行潜在的扩展和改进。

> Efficient audio quality assessment is vital for streamlining audio codec development. Objective assessment tools have been developed over time to algorithmically predict quality ratings from subjective assessments, the gold standard for quality judgment. Many of these tools use perceptual auditory models to extract audio features that are mapped to a basic audio quality score prediction using machine learning algorithms and subjective scores as training data. However, existing tools struggle with generalization in quality prediction, especially when faced with unknown signal and distortion types. This is particularly evident in the presence of signals coded using non-waveform-preserving parametric techniques. Addressing these challenges, this two-part work proposes extensions to the Perceptual Evaluation of Audio Quality (PEAQ - ITU-R BS.1387-1) recommendation. Part 1 focuses on increasing generalization, while Part 2 targets accurate spatial audio quality measurement in audio coding.
  To enhance prediction generalization, this paper (Part 1) introduces a novel machine learning approach that uses subjective data to model cognitive aspects of audio quality perception. The proposed method models the perceived severity of audible distortions by adaptively weighting different distortion metrics. The weights are determined using an interaction cost function that captures relationships between distortion salience and cognitive effects. Compared to other machine learning methods and established tools, the proposed architecture achieves higher prediction accuracy on large databases of previously unseen subjective quality scores. The perceptually-motivated model offers a more manageable alternative to general-purpose machine learning algorithms, allowing potential extensions and improvements to multi-dimensional quality measurement without complete retraining.

[Arxiv](https://arxiv.org/abs/2411.18222)