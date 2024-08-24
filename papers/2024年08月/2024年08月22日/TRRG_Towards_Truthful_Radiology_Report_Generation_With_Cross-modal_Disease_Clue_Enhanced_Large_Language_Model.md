# TRRG：借助跨模态疾病线索，打造更真实放射报告的大型语言模型

发布时间：2024年08月22日

`LLM应用` `人工智能`

> TRRG: Towards Truthful Radiology Report Generation With Cross-modal Disease Clue Enhanced Large Language Model

# 摘要

> 多模态大型语言模型的视觉语言能力备受瞩目，但在医疗领域，放射报告生成仍因数据不平衡和对齐粗糙而面临挑战。为此，我们提出了TRRG框架，通过阶段式训练跨模态注入疾病线索，提升模型感知疾病细节的能力。预训练中，对比学习强化了视觉编码器的细粒度感知；微调阶段，线索注入模块显著提升了模型的疾病导向感知。跨模态线索交互模块则实现了视觉与疾病线索的多粒度交互，大幅提升了报告生成与临床效能。实验显示，TRRG在IU-Xray和MIMIC-CXR等数据集上表现卓越，有效提升了模型对疾病的感知与临床应用效果。

> The vision-language modeling capability of multi-modal large language models has attracted wide attention from the community. However, in medical domain, radiology report generation using vision-language models still faces significant challenges due to the imbalanced data distribution caused by numerous negated descriptions in radiology reports and issues such as rough alignment between radiology reports and radiography. In this paper, we propose a truthful radiology report generation framework, namely TRRG, based on stage-wise training for cross-modal disease clue injection into large language models. In pre-training stage, During the pre-training phase, contrastive learning is employed to enhance the ability of visual encoder to perceive fine-grained disease details. In fine-tuning stage, the clue injection module we proposed significantly enhances the disease-oriented perception capability of the large language model by effectively incorporating the robust zero-shot disease perception. Finally, through the cross-modal clue interaction module, our model effectively achieves the multi-granular interaction of visual embeddings and an arbitrary number of disease clue embeddings. This significantly enhances the report generation capability and clinical effectiveness of multi-modal large language models in the field of radiology reportgeneration. Experimental results demonstrate that our proposed pre-training and fine-tuning framework achieves state-of-the-art performance in radiology report generation on datasets such as IU-Xray and MIMIC-CXR. Further analysis indicates that our proposed method can effectively enhance the model to perceive diseases and improve its clinical effectiveness.

[Arxiv](https://arxiv.org/abs/2408.12141)