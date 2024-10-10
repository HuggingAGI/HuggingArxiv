# RespLLM：融合音频与文本的多模态 LLM，助力广义呼吸健康预测

发布时间：2024年10月07日

`LLM应用` `健康诊断`

> RespLLM: Unifying Audio and Text with Multimodal LLMs for Generalized Respiratory Health Prediction

# 摘要

> 呼吸系统疾病的高发病率和死亡率凸显了早期筛查的重要性。机器学习模型通过自动化临床咨询和听诊，在这一领域提供了重要支持。然而，涉及的数据复杂多样，现有方法往往依赖有限数据和简单技术，缺乏普遍性。为此，我们提出了 RespLLM，一种多模态大型语言模型，统一了文本和音频表示，利用预训练知识实现高效融合。通过指令调优，RespLLM 整合多源数据，确保广泛适用性。实验表明，RespLLM 在多个数据集上表现优异，为呼吸健康诊断提供了可扩展的解决方案。

> The high incidence and mortality rates associated with respiratory diseases underscores the importance of early screening. Machine learning models can automate clinical consultations and auscultation, offering vital support in this area. However, the data involved, spanning demographics, medical history, symptoms, and respiratory audio, are heterogeneous and complex. Existing approaches are insufficient and lack generalizability, as they typically rely on limited training data, basic fusion techniques, and task-specific models. In this paper, we propose RespLLM, a novel multimodal large language model (LLM) framework that unifies text and audio representations for respiratory health prediction. RespLLM leverages the extensive prior knowledge of pretrained LLMs and enables effective audio-text fusion through cross-modal attentions. Instruction tuning is employed to integrate diverse data from multiple sources, ensuring generalizability and versatility of the model. Experiments on five real-world datasets demonstrate that RespLLM outperforms leading baselines by an average of 4.6% on trained tasks, 7.9% on unseen datasets, and facilitates zero-shot predictions for new tasks. Our work lays the foundation for multimodal models that can perceive, listen to, and understand heterogeneous data, paving the way for scalable respiratory health diagnosis.

[Arxiv](https://arxiv.org/abs/2410.05361)