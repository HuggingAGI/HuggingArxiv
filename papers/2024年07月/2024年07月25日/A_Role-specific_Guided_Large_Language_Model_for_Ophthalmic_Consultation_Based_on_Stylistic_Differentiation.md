# 针对眼科咨询，我们开发了一种基于风格差异的特定角色引导大型语言模型，以提升咨询效率和质量。

发布时间：2024年07月25日

`LLM应用` `人工智能`

> A Role-specific Guided Large Language Model for Ophthalmic Consultation Based on Stylistic Differentiation

# 摘要

> 眼科咨询对眼病的诊断、治疗和预防至关重要，但需求的增长已超过眼科医生的供应。我们利用大型预训练语言模型，为特定场景设计有效对话，辅助咨询。传统的问答任务微调策略因模型规模增大而变得不切实际，且常忽视咨询中的患者-医生角色功能。本文提出EyeDoctor，一个通过医生-患者角色感知和外部疾病信息增强知识库的眼科医学问答模型。实验表明，EyeDoctor在眼科咨询中问答精度更高，尤其在多轮数据集上，Rouge-1分数和F1分数分别提升7.25%和10.16%，凸显了角色区分和知识库动态扩展的重要性。EyeDoc还提供免费网络服务，源代码可于https://github.com/sperfu/EyeDoc获取。

> Ophthalmology consultations are crucial for diagnosing, treating, and preventing eye diseases. However, the growing demand for consultations exceeds the availability of ophthalmologists. By leveraging large pre-trained language models, we can design effective dialogues for specific scenarios, aiding in consultations. Traditional fine-tuning strategies for question-answering tasks are impractical due to increasing model size and often ignoring patient-doctor role function during consultations. In this paper, we propose EyeDoctor, an ophthalmic medical questioning large language model that enhances accuracy through doctor-patient role perception guided and an augmented knowledge base with external disease information. Experimental results show EyeDoctor achieves higher question-answering precision in ophthalmology consultations. Notably, EyeDoctor demonstrated a 7.25% improvement in Rouge-1 scores and a 10.16% improvement in F1 scores on multi-round datasets compared to second best model ChatGPT, highlighting the importance of doctor-patient role differentiation and dynamic knowledge base expansion for intelligent medical consultations. EyeDoc also serves as a free available web based service and souce code is available at https://github.com/sperfu/EyeDoc.

[Arxiv](https://arxiv.org/abs/2407.18483)