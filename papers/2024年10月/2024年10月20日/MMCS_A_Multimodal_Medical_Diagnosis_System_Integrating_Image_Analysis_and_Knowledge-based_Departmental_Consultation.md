# MMCS：一款融合图像分析与知识咨询的多模态医学诊断系统

发布时间：2024年10月20日

`RAG` `人工智能`

> MMCS: A Multimodal Medical Diagnosis System Integrating Image Analysis and Knowledge-based Departmental Consultation

# 摘要

> 我们推出了 MMCS 系统，该系统不仅能识别医学图像和患者面部特征，还能提供专业的医疗诊断。系统包含两大核心模块：首先是医学图像与视频的分析模块。我们训练了一个多模态医学模型，该模型不仅能解读医学影像，还能精准分析患者的面部情绪及瘫痪状况。在 FER2013 数据集上，该模型在面部情绪识别中达到了 72.59% 的准确率，其中识别快乐情绪的准确率高达 91.1%。在面部瘫痪识别方面，模型的准确率达到了 92%，比 GPT-4o 高出 30%。基于此，我们还开发了一个解析器，用于分析面部瘫痪患者的运动视频，实现对瘫痪程度的精准分级。在 30 个测试视频中，系统的分级准确率达到了 83.3%。其次是专业医疗响应生成模块。我们整合了大型语言模型与医学知识库，根据分析结果生成专业诊断。特别之处在于，我们设计了一个部门特定的知识库路由机制，使得模型能按部门分类数据，并在检索时选择合适的知识库，从而大幅提升 RAG 过程中的检索准确性。在 MedQA 数据集上，这一机制为各类大型语言模型带来了平均 4 个百分点的准确率提升。MMCS 的代码已开源，详见：https://github.com/renllll/MMCS。

> We present MMCS, a system capable of recognizing medical images and patient facial details, and providing professional medical diagnoses. The system consists of two core components: The first component is the analysis of medical images and videos. We trained a specialized multimodal medical model capable of interpreting medical images and accurately analyzing patients' facial emotions and facial paralysis conditions. The model achieved an accuracy of 72.59% on the FER2013 facial emotion recognition dataset, with a 91.1% accuracy in recognizing the happy emotion. In facial paralysis recognition, the model reached an accuracy of 92%, which is 30% higher than that of GPT-4o. Based on this model, we developed a parser for analyzing facial movement videos of patients with facial paralysis, achieving precise grading of the paralysis severity. In tests on 30 videos of facial paralysis patients, the system demonstrated a grading accuracy of 83.3%.The second component is the generation of professional medical responses. We employed a large language model, integrated with a medical knowledge base, to generate professional diagnoses based on the analysis of medical images or videos. The core innovation lies in our development of a department-specific knowledge base routing management mechanism, in which the large language model categorizes data by medical departments and, during the retrieval process, determines the appropriate knowledge base to query. This significantly improves retrieval accuracy in the RAG (retrieval-augmented generation) process. This mechanism led to an average increase of 4 percentage points in accuracy for various large language models on the MedQA dataset.Our code is open-sourced and available at: https://github.com/renllll/MMCS.

[Arxiv](https://arxiv.org/abs/2410.15403)