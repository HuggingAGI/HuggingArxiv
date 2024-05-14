# MedConceptsQA - 开源医学概念问答标杆，旨在为医学领域的知识问答提供一个公开、可验证的评估平台。

发布时间：2024年05月12日

`LLM应用

这篇论文介绍了MedConceptsQA，一个专为医学概念问答设计的开源基准，并评估了多种大型语言模型在该基准上的表现。这表明论文关注的是大型语言模型在特定应用领域（医学）的实际应用和性能评估，因此属于LLM应用分类。` `医学教育` `医疗诊断`

> MedConceptsQA -- Open Source Medical Concepts QA Benchmark

# 摘要

> 我们推出了MedConceptsQA，一个专为医学概念问答设计的开源基准。它涵盖了从诊断到治疗再到药物的各类医学问题，难度分为简单、中等和困难三个层次。我们通过多种大型语言模型对该基准进行了评估，发现尽管预训练的临床语言模型在医学数据上有所准备，但在这个测试上的表现仅略高于随机猜测。相比之下，GPT-4在零-shot和少-shot学习中分别实现了27%和37%的显著提升。我们的MedConceptsQA是评估大型语言模型医学理解和推理能力的宝贵工具，现已开放访问于https://huggingface.co/datasets/ofir408/MedConceptsQA。

> We present MedConceptsQA, a dedicated open source benchmark for medical concepts question answering. The benchmark comprises of questions of various medical concepts across different vocabularies: diagnoses, procedures, and drugs. The questions are categorized into three levels of difficulty: easy, medium, and hard. We conducted evaluations of the benchmark using various Large Language Models. Our findings show that pre-trained clinical Large Language Models achieved accuracy levels close to random guessing on this benchmark, despite being pre-trained on medical data. However, GPT-4 achieves an absolute average improvement of nearly 27%-37% (27% for zero-shot learning and 37% for few-shot learning) when compared to clinical Large Language Models. Our benchmark serves as a valuable resource for evaluating the understanding and reasoning of medical concepts by Large Language Models. Our benchmark is available at https://huggingface.co/datasets/ofir408/MedConceptsQA

[Arxiv](https://arxiv.org/abs/2405.07348)