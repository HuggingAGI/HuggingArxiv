# 光影交织：数字重建放射图像助力疾病分类

发布时间：2024年06月05日

`LLM应用

这篇论文介绍了DRR-RATE数据集，这是一个大规模的合成胸部X光数据集，用于支持多模态研究和提高病理识别能力。虽然数据集本身并不直接涉及Agent、RAG或LLM理论，但其应用场景（如在CheXnet上的训练和病理识别能力的提升）与大型语言模型（LLM）的应用领域相关。因此，将其归类为LLM应用是合适的，因为它展示了如何利用大规模数据集来改进和应用现有的机器学习模型，特别是在医疗图像分析领域。` `放射学`

> Shadow and Light: Digitally Reconstructed Radiographs for Disease Classification

# 摘要

> 本文介绍了DRR-RATE，一个基于CT-RATE数据集的大规模合成胸部X光数据集，包含50,188张来自21,304名患者的正面数字重建放射图像，每张图像均附有放射学报告和18种病理的二元标签。DRR-RATE的可控生成特性使其能轻松加入侧视图及任意视角的图像，为多模态研究提供了新机遇。我们验证了DRR-RATE与现有资源如CheXpert和CheXnet的兼容性，实验显示CheXnet在DRR-RATE上训练后，对六种常见病理的识别能力显著。此外，即使在非典型情况下，CheXnet也能准确识别多种病理，证明了DRR图像能有效反映CT图像的病理特征。数据集和标签已公开，地址为https://huggingface.co/datasets/farrell236/DRR-RATE。

> In this paper, we introduce DRR-RATE, a large-scale synthetic chest X-ray dataset derived from the recently released CT-RATE dataset. DRR-RATE comprises of 50,188 frontal Digitally Reconstructed Radiographs (DRRs) from 21,304 unique patients. Each image is paired with a corresponding radiology text report and binary labels for 18 pathology classes. Given the controllable nature of DRR generation, it facilitates the inclusion of lateral view images and images from any desired viewing position. This opens up avenues for research into new and novel multimodal applications involving paired CT, X-ray images from various views, text, and binary labels. We demonstrate the applicability of DRR-RATE alongside existing large-scale chest X-ray resources, notably the CheXpert dataset and CheXnet model. Experiments demonstrate that CheXnet, when trained and tested on the DRR-RATE dataset, achieves sufficient to high AUC scores for the six common pathologies cited in common literature: Atelectasis, Cardiomegaly, Consolidation, Lung Lesion, Lung Opacity, and Pleural Effusion. Additionally, CheXnet trained on the CheXpert dataset can accurately identify several pathologies, even when operating out of distribution. This confirms that the generated DRR images effectively capture the essential pathology features from CT images. The dataset and labels are publicly accessible at https://huggingface.co/datasets/farrell236/DRR-RATE.

[Arxiv](https://arxiv.org/abs/2406.03688)