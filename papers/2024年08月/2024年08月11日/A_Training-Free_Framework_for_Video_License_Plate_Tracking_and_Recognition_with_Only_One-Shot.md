# 本研究提出一种无需训练的视频车牌追踪与识别框架，仅需一次学习即可实现。

发布时间：2024年08月11日

`LLM应用` `智能交通系统` `车牌识别`

> A Training-Free Framework for Video License Plate Tracking and Recognition with Only One-Shot

# 摘要

> 传统车牌识别模型受限于封闭数据集，难以应对各地车牌格式的多样性。而大规模预训练模型则展现出卓越的泛化能力，支持少样本和零样本学习。为此，我们推出了OneShotLP框架，该框架无需训练，利用先进模型实现视频车牌检测与识别。方法从视频首帧的车牌位置出发，通过点跟踪模块在后续帧中持续追踪，形成提示轨迹。这些提示被送入分割模块，利用大型分割模型生成车牌区域的局部掩码。随后，多模态大型语言模型对分割区域进行处理，确保车牌识别的准确性。OneShotLP不仅无需大量训练数据，还能适应多种车牌样式，展现出显著优势。在UFPR-ALPR和SSIG-SegPlate数据集上的实验结果表明，我们的方法在准确性上超越了传统方法，凸显了预训练模型在智能交通系统中多样化应用的潜力。代码已公开，详见https://github.com/Dinghaoxuan/OneShotLP。

> Traditional license plate detection and recognition models are often trained on closed datasets, limiting their ability to handle the diverse license plate formats across different regions. The emergence of large-scale pre-trained models has shown exceptional generalization capabilities, enabling few-shot and zero-shot learning. We propose OneShotLP, a training-free framework for video-based license plate detection and recognition, leveraging these advanced models. Starting with the license plate position in the first video frame, our method tracks this position across subsequent frames using a point tracking module, creating a trajectory of prompts. These prompts are input into a segmentation module that uses a promptable large segmentation model to generate local masks of the license plate regions. The segmented areas are then processed by multimodal large language models (MLLMs) for accurate license plate recognition. OneShotLP offers significant advantages, including the ability to function effectively without extensive training data and adaptability to various license plate styles. Experimental results on UFPR-ALPR and SSIG-SegPlate datasets demonstrate the superior accuracy of our approach compared to traditional methods. This highlights the potential of leveraging pre-trained models for diverse real-world applications in intelligent transportation systems. The code is available at https://github.com/Dinghaoxuan/OneShotLP.

[Arxiv](https://arxiv.org/abs/2408.05729)