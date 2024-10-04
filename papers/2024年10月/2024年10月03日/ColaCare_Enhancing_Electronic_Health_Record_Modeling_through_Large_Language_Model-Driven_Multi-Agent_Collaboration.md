# ColaCare：借助大型语言模型驱动的多智能体协作，提升电子健康记录的建模效果。

发布时间：2024年10月03日

`Agent` `人工智能`

> ColaCare: Enhancing Electronic Health Record Modeling through Large Language Model-Driven Multi-Agent Collaboration

# 摘要

> 我们推出了 ColaCare，一个通过大型语言模型 (LLM) 驱动的多代理协作来提升电子健康记录 (EHR) 建模的框架。ColaCare 巧妙结合了领域专家模型与 LLM，填补了结构化 EHR 数据与文本推理之间的鸿沟。借鉴临床咨询模式，ColaCare 使用 DoctorAgent 和 MetaAgent 两种代理，协同分析患者数据。专家模型负责处理数值 EHR 数据并生成预测，而 LLM 代理则在协作框架内提供推理依据和决策报告。此外，我们还引入了默克诊断与治疗手册 (MSD) 医学指南，通过检索增强生成 (RAG) 模块，为决策提供权威支持。在四个不同 EHR 数据集上的实验显示，ColaCare 在死亡率预测任务中表现卓越，预示着其将革新临床决策支持系统，推动个性化精准医疗的发展。相关代码、提示模板及更多案例研究已公开，访问链接：https://colacare.netlify.app。

> We introduce ColaCare, a framework that enhances Electronic Health Record (EHR) modeling through multi-agent collaboration driven by Large Language Models (LLMs). Our approach seamlessly integrates domain-specific expert models with LLMs to bridge the gap between structured EHR data and text-based reasoning. Inspired by clinical consultations, ColaCare employs two types of agents: DoctorAgent and MetaAgent, which collaboratively analyze patient data. Expert models process and generate predictions from numerical EHR data, while LLM agents produce reasoning references and decision-making reports within the collaborative consultation framework. We additionally incorporate the Merck Manual of Diagnosis and Therapy (MSD) medical guideline within a retrieval-augmented generation (RAG) module for authoritative evidence support. Extensive experiments conducted on four distinct EHR datasets demonstrate ColaCare's superior performance in mortality prediction tasks, underscoring its potential to revolutionize clinical decision support systems and advance personalized precision medicine. The code, complete prompt templates, more case studies, etc. are publicly available at the anonymous link: https://colacare.netlify.app.

[Arxiv](https://arxiv.org/abs/2410.02551)