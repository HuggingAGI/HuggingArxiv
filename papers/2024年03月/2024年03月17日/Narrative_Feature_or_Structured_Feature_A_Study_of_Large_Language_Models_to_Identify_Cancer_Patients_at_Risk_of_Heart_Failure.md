# 探究大型语言模型在识别心脏病风险癌症患者方面，究竟是叙事特征更具优势，还是结构化特征更胜一筹。本研究针对这一问题，对大型语言模型进行深入分析，旨在揭示其在处理不同类型特征时，在识别癌症患者并发心力衰竭风险上的效能差异。

发布时间：2024年03月17日

`LLM应用` `癌症治疗` `电子健康记录`

> Narrative Feature or Structured Feature? A Study of Large Language Models to Identify Cancer Patients at Risk of Heart Failure

# 摘要

> 众所周知，癌症疗法易导致心脏毒性问题，从而降低疗效和生存质量。为了优化癌症治疗效果与安全，识别具有心脏衰竭风险的癌症患者至关重要。本次研究借助电子健康记录，运用多种机器学习模型进行此类高危患者识别，其中包括传统ML模型、考虑时间因素的T-LSTM模型及采用新颖结构化医学代码衍生叙事特征的大规模语言模型LLMs。研究对象来源于佛罗里达大学健康系统，共筛选出12,806例肺癌、乳腺癌和结直肠癌患者，其中有1,602例患者在癌症治疗后出现了心脏衰竭。其中，LLM模型GatorTron-3.9B表现卓越，其F1得分超越了传统支持向量机39%，比T-LSTM深度学习模型高出7%，相较于广泛应用的BERT转换器模型提升5.6%。研究揭示，创新提出的叙事特征极大地增强了特征稠密性，并有效提升了模型性能。

> Cancer treatments are known to introduce cardiotoxicity, negatively impacting outcomes and survivorship. Identifying cancer patients at risk of heart failure (HF) is critical to improving cancer treatment outcomes and safety. This study examined machine learning (ML) models to identify cancer patients at risk of HF using electronic health records (EHRs), including traditional ML, Time-Aware long short-term memory (T-LSTM), and large language models (LLMs) using novel narrative features derived from the structured medical codes. We identified a cancer cohort of 12,806 patients from the University of Florida Health, diagnosed with lung, breast, and colorectal cancers, among which 1,602 individuals developed HF after cancer. The LLM, GatorTron-3.9B, achieved the best F1 scores, outperforming the traditional support vector machines by 39%, the T-LSTM deep learning model by 7%, and a widely used transformer model, BERT, by 5.6%. The analysis shows that the proposed narrative features remarkably increased feature density and improved performance.

[Arxiv](https://arxiv.org/abs/2403.11425)