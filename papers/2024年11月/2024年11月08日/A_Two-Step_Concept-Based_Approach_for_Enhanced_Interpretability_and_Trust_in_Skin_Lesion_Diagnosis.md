# 一种用于增强皮肤病变诊断的可解释性和信任度的两步基于概念的方法

发布时间：2024年11月08日

`LLM应用` `临床诊断`

> A Two-Step Concept-Based Approach for Enhanced Interpretability and Trust in Skin Lesion Diagnosis

# 摘要

> 在临床环境中采用基于深度学习的系统的主要挑战是标注数据的稀缺以及对这些系统缺乏可解释性和信任。概念瓶颈模型（CBMs）通过将最终的疾病预测限制在一组人类可理解的概念上提供了内在的可解释性。然而，这种内在的可解释性是以更大的标注负担为代价的。此外，添加新的概念需要重新训练整个系统。在这项工作中，我们引入了一种新颖的两步方法来解决这两个挑战。通过模拟 CBM 的两个阶段，我们利用预训练的视觉语言模型（VLM）自动预测临床概念，并利用大型语言模型（LLM）根据预测的概念生成疾病诊断。我们在三个皮肤病变数据集上验证了我们的方法，表明它优于传统的 CBM 和最先进的可解释方法，所有这些都不需要任何训练，并且仅使用了几个标注示例。代码可在 https://github.com/CristianoPatricio/2-step-concept-based-skin-diagnosis 获得。

> The main challenges hindering the adoption of deep learning-based systems in clinical settings are the scarcity of annotated data and the lack of interpretability and trust in these systems. Concept Bottleneck Models (CBMs) offer inherent interpretability by constraining the final disease prediction on a set of human-understandable concepts. However, this inherent interpretability comes at the cost of greater annotation burden. Additionally, adding new concepts requires retraining the entire system. In this work, we introduce a novel two-step methodology that addresses both of these challenges. By simulating the two stages of a CBM, we utilize a pretrained Vision Language Model (VLM) to automatically predict clinical concepts, and a Large Language Model (LLM) to generate disease diagnoses based on the predicted concepts. We validate our approach on three skin lesion datasets, demonstrating that it outperforms traditional CBMs and state-of-the-art explainable methods, all without requiring any training and utilizing only a few annotated examples. The code is available at https://github.com/CristianoPatricio/2-step-concept-based-skin-diagnosis.

[Arxiv](https://arxiv.org/abs/2411.05609)