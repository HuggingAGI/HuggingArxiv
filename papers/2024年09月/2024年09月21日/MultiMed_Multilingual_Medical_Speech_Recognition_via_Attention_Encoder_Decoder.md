# MultiMed：利用注意力编码器解码器实现多语言医学语音识别

发布时间：2024年09月21日

`LLM应用` `语音识别`

> MultiMed: Multilingual Medical Speech Recognition via Attention Encoder Decoder

# 摘要

> 医疗领域的多语言自动语音识别 (ASR) 是语音翻译、口语理解和语音助手等应用的基础。MultiMed 项目通过跨越语言障碍的高效沟通、缓解专业人员短缺以及提升诊断和治疗，特别是在疫情期间，显著改善了患者护理。MultiMed 涵盖了越南语、英语、德语、法语和普通话五种语言的端到端 ASR 模型，并配备了相应的真实数据集，是迄今为止最大的多语言医疗 ASR 数据集。我们还建立了基线，进行了首次可重复的多语言医疗 ASR 研究，并提供了详细的语言学分析。所有资源均可在线获取。

> Multilingual automatic speech recognition (ASR) in the medical domain serves as a foundational task for various downstream applications such as speech translation, spoken language understanding, and voice-activated assistants. This technology enhances patient care by enabling efficient communication across language barriers, alleviating specialized workforce shortages, and facilitating improved diagnosis and treatment, particularly during pandemics. In this work, we introduce MultiMed, a collection of small-to-large end-to-end ASR models for the medical domain, spanning five languages: Vietnamese, English, German, French, and Mandarin Chinese, together with the corresponding real-world ASR dataset. To our best knowledge, MultiMed stands as the largest and the first multilingual medical ASR dataset, in terms of total duration, number of speakers, diversity of diseases, recording conditions, speaker roles, unique medical terms, accents, and ICD-10 codes. Secondly, we establish the empirical baselines, present the first reproducible study of multilinguality in medical ASR, conduct a layer-wise ablation study for end-to-end ASR training, and provide the first linguistic analysis for multilingual medical ASR. All code, data, and models are available online https://github.com/leduckhai/MultiMed/tree/master/MultiMed

[Arxiv](https://arxiv.org/abs/2409.14074)