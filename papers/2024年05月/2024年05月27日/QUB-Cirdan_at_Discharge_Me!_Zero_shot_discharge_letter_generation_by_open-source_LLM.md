# QUB-Cirdan 参与的 "Discharge Me!" 项目，利用开源大型语言模型，成功实现了零-shot 出院信的自动生成。

发布时间：2024年05月27日

`RAG

理由：这篇论文主要介绍了在 BioNLP ACL'24 共享任务中使用 Llama3 8B 量化模型结合零-shot 与检索增强生成（RAG）技术来生成关键的出院文档。RAG技术是论文的核心方法，用于优化字数预测和文档生成，因此将其归类为RAG。虽然涉及到了大型语言模型的应用，但主要焦点是RAG技术的应用和效果，而不是LLM的理论探讨或Agent的设计与应用。`

> QUB-Cirdan at "Discharge Me!": Zero shot discharge letter generation by open-source LLM

# 摘要

> BioNLP ACL'24 共享任务旨在通过自动化关键出院文档的生成，减轻临床医生的行政负担。我们采用 Llama3 8B 量化模型，结合零-shot 与检索增强生成（RAG）技术，精准生成“简要住院过程”及“出院指导”。本研究不仅开发了基于模板的可靠生成策略，还融入了 RAG 技术以优化字数预测。此外，我们分享了探索过程中的失败实验，以揭示我们的研究路径。实验结果表明，我们的方法在多个评估指标上均表现出色，既高效又有效。

> The BioNLP ACL'24 Shared Task on Streamlining Discharge Documentation aims to reduce the administrative burden on clinicians by automating the creation of critical sections of patient discharge letters. This paper presents our approach using the Llama3 8B quantized model to generate the "Brief Hospital Course" and "Discharge Instructions" sections. We employ a zero-shot method combined with Retrieval-Augmented Generation (RAG) to produce concise, contextually accurate summaries. Our contributions include the development of a curated template-based approach to ensure reliability and consistency, as well as the integration of RAG for word count prediction. We also describe several unsuccessful experiments to provide insights into our pathway for the competition. Our results demonstrate the effectiveness and efficiency of our approach, achieving high scores across multiple evaluation metrics.

![QUB-Cirdan 参与的 "Discharge Me!" 项目，利用开源大型语言模型，成功实现了零-shot 出院信的自动生成。](../../../paper_images/2406.00041/bionlp_diagram.png)

![QUB-Cirdan 参与的 "Discharge Me!" 项目，利用开源大型语言模型，成功实现了零-shot 出院信的自动生成。](../../../paper_images/2406.00041/word_distribution.png)

![QUB-Cirdan 参与的 "Discharge Me!" 项目，利用开源大型语言模型，成功实现了零-shot 出院信的自动生成。](../../../paper_images/2406.00041/bhc_features.png)

![QUB-Cirdan 参与的 "Discharge Me!" 项目，利用开源大型语言模型，成功实现了零-shot 出院信的自动生成。](../../../paper_images/2406.00041/di_features.png)

[Arxiv](https://arxiv.org/abs/2406.00041)