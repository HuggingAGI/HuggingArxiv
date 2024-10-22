# 微调基础模型，从兽医健康记录中精准诊断代码

发布时间：2024年10月19日

`LLM应用`

> Fine-tuning foundational models to code diagnoses from veterinary health records

# 摘要

> 兽医医疗记录是兽医和One Health临床研究的重要数据资源，但数据互操作性问题限制了其应用。通过标准化医学术语进行临床编码，可以提升记录质量并促进跨平台互操作。先前研究如DeepTag和VetTag，利用NLP技术自动编码兽医诊断，取得了一定成果。本研究在此基础上，整合了CSU VTH认可的所有SNOMED-CT诊断代码，并利用预训练LLMs进行微调，显著提升了性能。实验表明，大规模标记数据和大型临床LLMs能带来最佳效果，但有限资源和非临床LLMs也能取得可观成果。这项研究不仅提升了兽医EHRs的质量，还为跨物种和机构的综合健康数据库建设提供了支持，推动了动物和人类健康研究的发展。

> Veterinary medical records represent a large data resource for application to veterinary and One Health clinical research efforts. Use of the data is limited by interoperability challenges including inconsistent data formats and data siloing. Clinical coding using standardized medical terminologies enhances the quality of medical records and facilitates their interoperability with veterinary and human health records from other sites. Previous studies, such as DeepTag and VetTag, evaluated the application of Natural Language Processing (NLP) to automate veterinary diagnosis coding, employing long short-term memory (LSTM) and transformer models to infer a subset of Systemized Nomenclature of Medicine - Clinical Terms (SNOMED-CT) diagnosis codes from free-text clinical notes. This study expands on these efforts by incorporating all 7,739 distinct SNOMED-CT diagnosis codes recognized by the Colorado State University (CSU) Veterinary Teaching Hospital (VTH) and by leveraging the increasing availability of pre-trained large language models (LLMs). Ten freely-available pre-trained LLMs were fine-tuned on the free-text notes from 246,473 manually-coded veterinary patient visits included in the CSU VTH's electronic health records (EHRs), which resulted in superior performance relative to previous efforts. The most accurate results were obtained when expansive labeled data were used to fine-tune relatively large clinical LLMs, but the study also showed that comparable results can be obtained using more limited resources and non-clinical LLMs. The results of this study contribute to the improvement of the quality of veterinary EHRs by investigating accessible methods for automated coding and support both animal and human health research by paving the way for more integrated and comprehensive health databases that span species and institutions.

[Arxiv](https://arxiv.org/abs/2410.15186)