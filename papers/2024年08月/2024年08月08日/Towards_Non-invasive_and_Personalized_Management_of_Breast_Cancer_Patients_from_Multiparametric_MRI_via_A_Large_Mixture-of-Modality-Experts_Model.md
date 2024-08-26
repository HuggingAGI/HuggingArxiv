# 利用大型混合模态专家模型，我们致力于实现基于多参数MRI的乳腺癌患者非侵入性和个性化管理。

发布时间：2024年08月08日

`LLM应用

解释：虽然这篇论文主要关注的是乳腺MRI和AI模型的应用，而不是直接讨论大型语言模型（LLM），但它涉及到的MOME模型是一个多模态的AI模型，可以被视为LLM在医疗影像分析领域的一个应用实例。因此，我将这篇论文分类为“LLM应用”，因为它展示了如何将先进的AI技术（类似于LLM的处理能力）应用于特定的医疗问题，从而提高诊断和管理的效率和准确性。` `人工智能`

> Towards Non-invasive and Personalized Management of Breast Cancer Patients from Multiparametric MRI via A Large Mixture-of-Modality-Experts Model

# 摘要

> 乳腺MRI因其高敏感性成为检测乳腺癌的首选影像技术，尤其适用于高风险女性。尽管乳腺MRI采用多参数协议，但AI研究多依赖单一序列且验证不足。我们开发的MOME模型，整合多参数MRI信息，提供无创个性化乳腺癌管理。通过涉及5,205名患者的最大规模多参数乳腺MRI数据集，MOME在乳腺癌识别上表现卓越，与资深放射科医生媲美，显著超越初级医生。此外，MOME能减少部分患者的活检需求，精准分类三阴性乳腺癌，并预测化疗反应。该模型还支持可扩展和可解释的推理，适应数据缺失并提供决策依据。MOME作为区分性、稳健、可扩展和可解释的多模态模型，为非侵入性个性化乳腺癌管理开辟了新途径。

> Breast magnetic resonance imaging (MRI) is the imaging technique with the highest sensitivity for detecting breast cancer and is routinely used for women at high risk. Despite the comprehensive multiparametric protocol of breast MRI, existing artificial intelligence-based studies predominantly rely on single sequences and have limited validation. Here we report a large mixture-of-modality-experts model (MOME) that integrates multiparametric MRI information within a unified structure, offering a noninvasive method for personalized breast cancer management. We have curated the largest multiparametric breast MRI dataset, involving 5,205 patients from three hospitals in the north, southeast, and southwest of China, for the development and extensive evaluation of our model. MOME demonstrated accurate and robust identification of breast cancer. It achieved comparable performance for malignancy recognition to that of four senior radiologists and significantly outperformed a junior radiologist, with 0.913 AUROC, 0.948 AUPRC, 0.905 F1 score, and 0.723 MCC. Our findings suggest that MOME could reduce the need for biopsies in BI-RADS 4 patients with a ratio of 7.3%, classify triple-negative breast cancer with an AUROC of 0.709, and predict pathological complete response to neoadjuvant chemotherapy with an AUROC of 0.694. The model further supports scalable and interpretable inference, adapting to missing modalities and providing decision explanations by highlighting lesions and measuring modality contributions. MOME exemplifies a discriminative, robust, scalable, and interpretable multimodal model, paving the way for noninvasive, personalized management of breast cancer patients based on multiparametric breast imaging data.

[Arxiv](https://arxiv.org/abs/2408.12606)