# 光影交织：数字重建放射图像助力疾病分类

发布时间：2024年06月05日

`Agent

理由：这篇论文介绍了一个名为DRR-RATE的大规模合成胸部X光数据集，并探讨了其在多模态研究和病理识别中的应用。虽然涉及到了数据集的创建和使用，但主要关注的是数据集的生成和其在特定任务（如病理识别）中的应用，而不是深入探讨语言模型（LLM）的理论或应用。此外，论文中提到的数据集的生成和使用更偏向于一个工具或资源，用于辅助机器学习模型（如CheXnet）的训练和评估，这与Agent的定义更为接近，即一个能够执行任务并与其他系统交互的实体。因此，将其归类为Agent更为合适。` `放射学`

> Shadow and Light: Digitally Reconstructed Radiographs for Disease Classification

# 摘要

> 本文介绍了DRR-RATE，一个基于CT-RATE数据集的大规模合成胸部X光数据集，包含50,188张来自21,304名患者的正面数字重建放射图像，每张图像均附有放射学报告和18种病理的二元标签。DRR生成的可控性使其能轻松加入侧视图及任意视角的图像，为多模态研究提供了新机遇。我们验证了DRR-RATE与现有资源（如CheXpert和CheXnet）的兼容性，并发现CheXnet在DRR-RATE上训练后，对六种常见病理的识别效果显著。此外，即使在分布外，CheXnet也能准确识别多种病理，证明DRR图像能有效反映CT图像的病理特征。数据集和标签已公开，地址为https://huggingface.co/datasets/farrell236/DRR-RATE。

> In this paper, we introduce DRR-RATE, a large-scale synthetic chest X-ray dataset derived from the recently released CT-RATE dataset. DRR-RATE comprises of 50,188 frontal Digitally Reconstructed Radiographs (DRRs) from 21,304 unique patients. Each image is paired with a corresponding radiology text report and binary labels for 18 pathology classes. Given the controllable nature of DRR generation, it facilitates the inclusion of lateral view images and images from any desired viewing position. This opens up avenues for research into new and novel multimodal applications involving paired CT, X-ray images from various views, text, and binary labels. We demonstrate the applicability of DRR-RATE alongside existing large-scale chest X-ray resources, notably the CheXpert dataset and CheXnet model. Experiments demonstrate that CheXnet, when trained and tested on the DRR-RATE dataset, achieves sufficient to high AUC scores for the six common pathologies cited in common literature: Atelectasis, Cardiomegaly, Consolidation, Lung Lesion, Lung Opacity, and Pleural Effusion. Additionally, CheXnet trained on the CheXpert dataset can accurately identify several pathologies, even when operating out of distribution. This confirms that the generated DRR images effectively capture the essential pathology features from CT images. The dataset and labels are publicly accessible at https://huggingface.co/datasets/farrell236/DRR-RATE.

[Arxiv](https://arxiv.org/abs/2406.03688)