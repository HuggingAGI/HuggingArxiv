# MuJo：探索人体活动识别中的多模态联合特征空间学习

发布时间：2024年06月06日

`Agent

理由：这篇论文主要关注的是人类活动识别（HAR），并通过多模态对比预训练提升识别性能。它提出了一种新的方法（MuJo），该方法学习了一个融合多种数据类型的多模态联合特征空间，并结合了对比与多任务学习。这种方法可以被视为一个智能Agent，因为它能够处理和理解多种类型的输入数据，并在此基础上做出决策或识别活动。此外，论文中提到的模型在资源有限和模态缺失情况下的鲁棒性，以及其在不同数据集上的泛化能力，都表明这是一个高效的Agent系统。因此，这篇论文更适合归类为Agent。`

> MuJo: Multimodal Joint Feature Space Learning for Human Activity Recognition

# 摘要

> 人类活动识别（HAR）是AI领域的一个经典难题，广泛应用于医疗、体育、安全、人机交互及机器人等多个领域。HAR的实际表现高度依赖于输入信号的类型和质量。在拥有清晰高质量摄像头视角的场景中，结合基础模型（如CLIP）的计算机视觉系统能可靠地识别复杂活动。然而，使用可穿戴传感器等模态进行识别则更具挑战，因为这些信号信息量较少，且标注数据获取不易。本研究通过多模态对比预训练，显著提升了不同模态的HAR性能。我们的MuJo方法学习了一个融合视频、语言、姿态和IMU传感器数据的多模态联合特征空间，结合对比与多任务学习，探索了学习共享表示的多任务策略。我们还推出了一个包含丰富平行数据的大型数据集，并评估了多模态联合空间在模态缺失和资源有限情况下的鲁棒性。在MM-Fit数据集上，我们的模型在仅用2%训练数据时，Macro F1-Score高达0.992，全量数据下更是达到了0.999。即便面对未见数据集，我们的模型也展现了高达0.638的泛化能力。

> Human Activity Recognition is a longstanding problem in AI with applications in a broad range of areas: from healthcare, sports and fitness, security, and human computer interaction to robotics. The performance of HAR in real-world settings is strongly dependent on the type and quality of the input signal that can be acquired. Given an unobstructed, high-quality camera view of a scene, computer vision systems, in particular in conjunction with foundational models (e.g., CLIP), can today fairly reliably distinguish complex activities. On the other hand, recognition using modalities such as wearable sensors (which are often more broadly available, e.g, in mobile phones and smartwatches) is a more difficult problem, as the signals often contain less information and labeled training data is more difficult to acquire. In this work, we show how we can improve HAR performance across different modalities using multimodal contrastive pretraining. Our approach MuJo (Multimodal Joint Feature Space Learning), learns a multimodal joint feature space with video, language, pose, and IMU sensor data. The proposed approach combines contrastive and multitask learning methods and analyzes different multitasking strategies for learning a compact shared representation. A large dataset with parallel video, language, pose, and sensor data points is also introduced to support the research, along with an analysis of the robustness of the multimodal joint space for modal-incomplete and low-resource data. On the MM-Fit dataset, our model achieves an impressive Macro F1-Score of up to 0.992 with only 2% of the train data and 0.999 when using all available training data for classification tasks. Moreover, in the scenario where the MM-Fit dataset is unseen, we demonstrate a generalization performance of up to 0.638.

[Arxiv](https://arxiv.org/abs/2406.03857)