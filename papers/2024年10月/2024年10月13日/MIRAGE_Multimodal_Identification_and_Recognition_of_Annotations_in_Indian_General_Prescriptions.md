# MIRAGE：印度通用处方中多模态注释的识别与解析

发布时间：2024年10月13日

`LLM应用` `光学字符识别`

> MIRAGE: Multimodal Identification and Recognition of Annotations in Indian General Prescriptions

# 摘要

> 尽管电子病历 (EMR) 已经普及，医院仍大量使用手写处方，这不仅阻碍了长期药物效果的分析，还影响了统计分析和记录检索。手写处方识别面临独特挑战，需要专门数据来训练模型。当前方法多采用 2-D LSTMs，但最新研究转向使用大型语言模型 (LLM) 进行光学字符识别 (OCR)。基于此，我们开发了 MIRAGE 方法，通过微调 LLaVA 1.6 和 Idefics2 模型，从医疗记录中提取药物信息。我们使用了 Medyug Technology 提供的 743,118 份高分辨率模拟记录，涵盖 1,133 名印度医生的数据。实验结果显示，MIRAGE 在药物名称和剂量提取上准确率达 82%。我们还详细介绍了研究方法和结果，并发布了一个包含 100 份带标签记录的小数据集，供进一步研究使用。

> Hospitals generate thousands of handwritten prescriptions, a practice that remains prevalent despite the availability of Electronic Medical Records (EMR). This method of record-keeping hinders the examination of long-term medication effects, impedes statistical analysis, and makes the retrieval of records challenging. Handwritten prescriptions pose a unique challenge, requiring specialized data for training models to recognize medications and their patterns of recommendation. While current handwriting recognition approaches typically employ 2-D LSTMs, recent studies have explored the use of Large Language Models (LLMs) for Optical Character Recognition (OCR). Building on this approach, we focus on extracting medication names from medical records. Our methodology MIRAGE (Multimodal Identification and Recognition of Annotations in indian GEneral prescriptions) involves fine-tuning the LLaVA 1.6 and Idefics2 models. Our research utilizes a dataset provided by Medyug Technology, consisting of 743,118 fully annotated high-resolution simulated medical records from 1,133 doctors across India. We demonstrate that our methodology exhibits 82% accuracy in medication name and dosage extraction. We provide a detailed account of our research methodology and results, notes about HWR with Multimodal LLMs, and release a small dataset of 100 medical records with labels.

[Arxiv](https://arxiv.org/abs/2410.09729)