# 构建综合框架，助力三维脑CT报告生成中的多模态大型语言模型发展

发布时间：2024年07月02日

`LLM应用` `放射学`

> Towards a Holistic Framework for Multimodal Large Language Models in Three-dimensional Brain CT Report Generation

# 摘要

> 多模态大型语言模型（MLLMs）在医疗领域的应用，尤其是放射学报告生成方面，已展现出巨大潜力。然而，二维放射学字幕的初步成功并不能完全反映三维解剖学中的实际诊断挑战。为此，我们针对现有文献中的三大限制——数据复杂性、模型容量和评估指标的忠实度，收集了18,885个文本-扫描对的3D-BrainCT数据集，并采用临床视觉指令调优（CVIT）训练BrainGPT模型，以生成高质量的3D脑CT报告。内部测试显示，BrainGPT在多项指标上表现优异，如BLEU-1得分44.35，BLEU-4得分20.38，METEOR得分30.13，ROUGE-L得分47.6，CIDEr-R得分211.77，并在外部验证CQ500数据集上的字幕中线偏移准确性达到0.91。我们发现，传统评估指标仅能衡量文本表面相似性，未能深入评估诊断信息密度。因此，我们提出了创新的面向特征的放射学任务评估（FORTE），以更准确地衡量报告的临床相关性。BrainGPT模型在FORTE评估中平均F1-分数达到0.71，显示出其在病变特征和地标识别方面的优异性能。此外，通过图灵测试，我们证实了BrainGPT模型生成的报告与人类编写的报告难以区分，证明了其生成类似人类放射学报告的能力。我们的研究不仅展示了3D脑CT数据集的策划经验，还推动了解剖学敏感语言模型的微调及放射学评估指标的创新。

> Multi-modal large language models (MLLMs) have been given free rein to explore exciting medical applications with a primary focus on radiology report generation. Nevertheless, the preliminary success in 2D radiology captioning is incompetent to reflect the real-world diagnostic challenge in the volumetric 3D anatomy. To mitigate three crucial limitation aspects in the existing literature, including (1) data complexity, (2) model capacity, and (3) evaluation metric fidelity, we collected an 18,885 text-scan pairs 3D-BrainCT dataset and applied clinical visual instruction tuning (CVIT) to train BrainGPT models to generate radiology-adherent 3D brain CT reports. Statistically, our BrainGPT scored BLEU-1 = 44.35, BLEU-4 = 20.38, METEOR = 30.13, ROUGE-L = 47.6, and CIDEr-R = 211.77 during internal testing and demonstrated an accuracy of 0.91 in captioning midline shifts on the external validation CQ500 dataset. By further inspecting the captioned report, we reported that the traditional metrics appeared to measure only the surface text similarity and failed to gauge the information density of the diagnostic purpose. To close this gap, we proposed a novel Feature-Oriented Radiology Task Evaluation (FORTE) to estimate the report's clinical relevance (lesion feature and landmarks). Notably, the BrainGPT model scored an average FORTE F1-score of 0.71 (degree=0.661; landmark=0.706; feature=0.693; impression=0.779). To demonstrate that BrainGPT models possess objective readiness to generate human-like radiology reports, we conducted a Turing test that enrolled 11 physician evaluators, and around 74% of the BrainGPT-generated captions were indistinguishable from those written by humans. Our work embodies a holistic framework that showcased the first-hand experience of curating a 3D brain CT dataset, fine-tuning anatomy-sensible language models, and proposing robust radiology evaluation metrics.

[Arxiv](https://arxiv.org/abs/2407.02235)