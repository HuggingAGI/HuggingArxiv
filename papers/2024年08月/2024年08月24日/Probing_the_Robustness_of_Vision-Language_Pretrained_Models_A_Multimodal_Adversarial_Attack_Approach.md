# 探索视觉-语言预训练模型的稳健性：采用多模态对抗攻击策略

发布时间：2024年08月24日

`LLM应用` `人工智能` `计算机视觉`

> Probing the Robustness of Vision-Language Pretrained Models: A Multimodal Adversarial Attack Approach

# 摘要

> 视觉-语言预训练（VLP）结合变换器在多模态任务中表现出色，但其对抗鲁棒性研究不足。本文探讨了VLP变换器的对抗脆弱性，并创新设计了联合多模态变换器特征攻击（JMTFA），在白盒环境下同时干扰视觉和文本模态。JMTFA通过瞄准注意力分数，有效破坏各模态关键特征，生成对抗样本，误导模型预测。实验显示，该方法在视觉-语言任务中攻击成功率显著高于现有技术。研究发现，文本模态对VLP变换器的复杂融合过程影响重大，且模型大小与对抗鲁棒性无直接关联。这些发现强调了对抗鲁棒性的新视角，并警示多模态AI系统部署的风险。

> Vision-language pretraining (VLP) with transformers has demonstrated exceptional performance across numerous multimodal tasks. However, the adversarial robustness of these models has not been thoroughly investigated. Existing multimodal attack methods have largely overlooked cross-modal interactions between visual and textual modalities, particularly in the context of cross-attention mechanisms. In this paper, we study the adversarial vulnerability of recent VLP transformers and design a novel Joint Multimodal Transformer Feature Attack (JMTFA) that concurrently introduces adversarial perturbations in both visual and textual modalities under white-box settings. JMTFA strategically targets attention relevance scores to disrupt important features within each modality, generating adversarial samples by fusing perturbations and leading to erroneous model predictions. Experimental results indicate that the proposed approach achieves high attack success rates on vision-language understanding and reasoning downstream tasks compared to existing baselines. Notably, our findings reveal that the textual modality significantly influences the complex fusion processes within VLP transformers. Moreover, we observe no apparent relationship between model size and adversarial robustness under our proposed attacks. These insights emphasize a new dimension of adversarial robustness and underscore potential risks in the reliable deployment of multimodal AI systems.

[Arxiv](https://arxiv.org/abs/2408.13461)