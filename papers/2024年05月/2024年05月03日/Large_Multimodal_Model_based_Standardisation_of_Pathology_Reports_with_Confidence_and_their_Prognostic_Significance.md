# 利用大型多模态模型对病理报告进行标准化处理，同时评估其置信度和对疾病预后的影响。

发布时间：2024年05月03日

`分类：LLM应用

这篇论文的摘要描述了一种利用大型多模态模型（LMMs）自动识别扫描的病理报告图像的方法，以创建标准化报告并评估各字段的准确性。这种方法涉及到信息提取和验证，以及对提取字段的置信度评分。虽然论文中没有明确提到“大型语言模型”（LLM），但LMMs通常是基于LLMs构建的，因此这篇论文可以归类为LLM应用。此外，这项研究在医疗领域的应用也展示了LLM在实际问题解决中的潜力。` `人工智能`

> Large Multimodal Model based Standardisation of Pathology Reports with Confidence and their Prognostic Significance

# 摘要

> 病理报告细节丰富，却多以自由文本呈现，其非结构化特性极大地限制了信息的获取。本研究提出了一种创新方法，利用大型多模态模型（LMMs）自动识别扫描的病理报告图像，旨在创建标准化报告，明确各字段的价值及其准确性的置信估计。此方法突破了传统技术的局限，不再局限于未对提取字段进行置信度评分的缺陷。我们的框架通过两阶段的提示，引导LMM进行信息提取与验证，不仅适用于多个医疗中心的文本报告，也适用于旧版病理报告的扫描图像。研究证实，置信度评估能有效指示信息提取的准确性，从而筛选出精确度更高的字段。此外，我们还探讨了病理报告中结构化与非结构化数据的预后重要性，并发现自动提取的字段值在患者分层中具有重要的预后意义。该框架的评估可通过以下网址进行：https://labieb.dcs.warwick.ac.uk/。

> Pathology reports are rich in clinical and pathological details but are often presented in free-text format. The unstructured nature of these reports presents a significant challenge limiting the accessibility of their content. In this work, we present a practical approach based on the use of large multimodal models (LMMs) for automatically extracting information from scanned images of pathology reports with the goal of generating a standardised report specifying the value of different fields along with estimated confidence about the accuracy of the extracted fields. The proposed approach overcomes limitations of existing methods which do not assign confidence scores to extracted fields limiting their practical use. The proposed framework uses two stages of prompting a Large Multimodal Model (LMM) for information extraction and validation. The framework generalises to textual reports from multiple medical centres as well as scanned images of legacy pathology reports. We show that the estimated confidence is an effective indicator of the accuracy of the extracted information that can be used to select only accurately extracted fields. We also show the prognostic significance of structured and unstructured data from pathology reports and show that the automatically extracted field values significant prognostic value for patient stratification. The framework is available for evaluation via the URL: https://labieb.dcs.warwick.ac.uk/.

[Arxiv](https://arxiv.org/abs/2405.02040)