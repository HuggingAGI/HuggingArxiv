# 针对发动机故障声音事件的精准识别，本研究采用多模态信号技术，旨在实现对各类微小故障声音细节的敏锐捕捉与精确判断。

发布时间：2024年03月16日

`Agent` `汽车工程` `声音事件检测`

> Fine-Grained Engine Fault Sound Event Detection Using Multimodal Signals

# 摘要

> 在音频研究领域，声音事件检测（SED）致力于捕捉声音事件的发生时刻。本论文创新性地将SED技术应用于汽车发动机故障识别，构建了一个结合音频与加速度计振动记录的多模态SED框架，可精确识别各类车辆发动机内部的细粒度故障。首先，我们在一个包含丰富车型、且经过专家标注的发动机故障声音事件数据集上定义问题。随后，我们提出了一个SED模型，以实时检测十大类发生在引擎内部的细微故障，并探索了一种基于大规模弱标签故障数据集的预训练方法。经多次验证，我们的新框架在发动机故障声音事件检测方面表现出色。最终，我们深入探究了音频与振动两种模态之间的互动关系及其各自特性，发现融合二者特征能有效提升整体的发动机故障SED性能。

> Sound event detection (SED) is an active area of audio research that aims to detect the temporal occurrence of sounds. In this paper, we apply SED to engine fault detection by introducing a multimodal SED framework that detects fine-grained engine faults of automobile engines using audio and accelerometer-recorded vibration. We first introduce the problem of engine fault SED on a dataset collected from a large variety of vehicles with expertly-labeled engine fault sound events. Next, we propose a SED model to temporally detect ten fine-grained engine faults that occur within vehicle engines and further explore a pretraining strategy using a large-scale weakly-labeled engine fault dataset. Through multiple evaluations, we show our proposed framework is able to effectively detect engine fault sound events. Finally, we investigate the interaction and characteristics of each modality and show that fusing features from audio and vibration improves overall engine fault SED capabilities.

![针对发动机故障声音事件的精准识别，本研究采用多模态信号技术，旨在实现对各类微小故障声音细节的敏锐捕捉与精确判断。](../../../paper_images/2403.11037/modeldiag_twopart_v4.jpg)

![针对发动机故障声音事件的精准识别，本研究采用多模态信号技术，旨在实现对各类微小故障声音细节的敏锐捕捉与精确判断。](../../../paper_images/2403.11037/positive_qual_final.jpg)

![针对发动机故障声音事件的精准识别，本研究采用多模态信号技术，旨在实现对各类微小故障声音细节的敏锐捕捉与精确判断。](../../../paper_images/2403.11037/negative_qual_final.jpg)

[Arxiv](https://arxiv.org/abs/2403.11037)