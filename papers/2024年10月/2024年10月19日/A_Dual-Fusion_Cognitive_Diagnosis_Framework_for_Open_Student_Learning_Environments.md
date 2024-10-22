# 开放学生学习环境中的双融合认知诊断框架

发布时间：2024年10月19日

`LLM应用` `智能教育`

> A Dual-Fusion Cognitive Diagnosis Framework for Open Student Learning Environments

# 摘要

> 认知诊断模型 (CDM) 在智能教育中至关重要，旨在通过历史答题记录推断学生水平。然而，现有 CDM 多采用基于 ID 的嵌入方式，这在开放学习环境中效果不佳，因为难以直接推断新学生水平或利用新练习和知识。文本语义信息因其统一性和易获取性，有助于缓解这一问题。但直接结合语义信息可能无法提升 CDM 效果，因为它忽略了与答题相关的特征，从而丢失了学生的个体差异。为此，本文提出双融合认知诊断框架 (DFCD)，旨在融合文本语义和答题相关特征。具体来说，DFCD 首先通过大型语言模型精炼练习和知识概念，然后使用文本嵌入模型提取语义信息。对于答题相关特征，我们设计了新的响应矩阵以全面整合答题记录中的信息。最后，DFCD 通过双融合模块整合这两类特征。最终的表示不仅适用于开放学习环境，还可与现有 CDM 兼容。实验证明，DFCD 通过整合多模态信息，在开放学习环境中表现出色。

> Cognitive diagnosis model (CDM) is a fundamental and upstream component in intelligent education. It aims to infer students' mastery levels based on historical response logs. However, existing CDMs usually follow the ID-based embedding paradigm, which could often diminish the effectiveness of CDMs in open student learning environments. This is mainly because they can hardly directly infer new students' mastery levels or utilize new exercises or knowledge without retraining. Textual semantic information, due to its unified feature space and easy accessibility, can help alleviate this issue. Unfortunately, directly incorporating semantic information may not benefit CDMs, since it does not capture response-relevant features and thus discards the individual characteristics of each student. To this end, this paper proposes a dual-fusion cognitive diagnosis framework (DFCD) to address the challenge of aligning two different modalities, i.e., textual semantic features and response-relevant features. Specifically, in DFCD, we first propose the exercise-refiner and concept-refiner to make the exercises and knowledge concepts more coherent and reasonable via large language models. Then, DFCD encodes the refined features using text embedding models to obtain the semantic information. For response-related features, we propose a novel response matrix to fully incorporate the information within the response logs. Finally, DFCD designs a dual-fusion module to merge the two modal features. The ultimate representations possess the capability of inference in open student learning environments and can be also plugged in existing CDMs. Extensive experiments across real-world datasets show that DFCD achieves superior performance by integrating different modalities and strong adaptability in open student learning environments.

[Arxiv](https://arxiv.org/abs/2410.15054)