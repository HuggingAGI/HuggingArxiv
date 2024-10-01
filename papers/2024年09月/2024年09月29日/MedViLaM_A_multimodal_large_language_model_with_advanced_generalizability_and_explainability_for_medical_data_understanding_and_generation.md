# MedViLaM：一款具备卓越泛化性和可解释性的多模态大型语言模型，专为医学数据的理解与生成而设计。

发布时间：2024年09月29日

`LLM应用` `人工智能`

> MedViLaM: A multimodal large language model with advanced generalizability and explainability for medical data understanding and generation

# 摘要

> 医学领域天然具备多模态和多任务的特性，涉及文本、影像等多种数据形式。然而，现有模型多为单模态单任务，缺乏泛化性和解释性。为此，我们推出了 MedViLaM，一个能够统一处理临床语言和影像的多模态视觉语言模型，所有处理均基于同一组模型权重。为支持这一多任务模型的开发，我们创建了 MultiMedBench，一个包含连续问答、多标签疾病分类等任务的综合预训练数据集和基准。MedViLaM 在这些任务中表现卓越，显著领先于其他通用模型。此外，我们还展示了其在零样本泛化、任务间迁移学习以及零样本医学推理方面的潜力。

> Medicine is inherently multimodal and multitask, with diverse data modalities spanning text, imaging. However, most models in medical field are unimodal single tasks and lack good generalizability and explainability. In this study, we introduce MedViLaM, a unified vision-language model towards a generalist model for medical data that can flexibly encode and interpret various forms of medical data, including clinical language and imaging, all using the same set of model weights. To facilitate the creation of such multi-task model, we have curated MultiMedBench, a comprehensive pretaining dataset and benchmark consisting of several distinct tasks, i.e., continuous question-answering, multi-label disease classification, disease localization, generation and summarization of radiology reports. MedViLaM demonstrates strong performance across all MultiMedBench tasks, frequently outpacing other generalist models by a significant margin. Additionally, we present instances of zero-shot generalization to new medical concepts and tasks, effective transfer learning across different tasks, and the emergence of zero-shot medical reasoning.

[Arxiv](https://arxiv.org/abs/2409.19684)