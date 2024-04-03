# 本研究探讨了运用开源临床大型语言模型对癌症阶段进行精确分类的方法。

发布时间：2024年04月01日

`LLM应用`

> Classifying Cancer Stage with Open-Source Clinical Large Language Models

# 摘要

> 癌症的准确分期对于制定癌症患者的治疗方案和护理计划极为关键。分期信息常散布在电子健康档案中的临床报告、病理分析、放射科报告等非结构化文本里，提取这些信息需要大量的劳动。本研究证实，即便没有经过标记训练数据，开源的临床大型语言模型（LLMs）也能成功从真实世界的病理报告中抽取出病理版的肿瘤-淋巴结-转移（pTNM）分期资料。我们通过实验对LLMs和利用标记数据进行精细调整的BERT模型进行了比较。研究结果显示，尽管LLMs在肿瘤（T）分类方面仍显不足，但通过恰当的提示策略，它们在转移（M）分类上能取得相近的表现，并在淋巴结（N）分类上有所进步。

> Cancer stage classification is important for making treatment and care management plans for oncology patients. Information on staging is often included in unstructured form in clinical, pathology, radiology and other free-text reports in the electronic health record system, requiring extensive work to parse and obtain. To facilitate the extraction of this information, previous NLP approaches rely on labeled training datasets, which are labor-intensive to prepare. In this study, we demonstrate that without any labeled training data, open-source clinical large language models (LLMs) can extract pathologic tumor-node-metastasis (pTNM) staging information from real-world pathology reports. Our experiments compare LLMs and a BERT-based model fine-tuned using the labeled data. Our findings suggest that while LLMs still exhibit subpar performance in Tumor (T) classification, with the appropriate adoption of prompting strategies, they can achieve comparable performance on Metastasis (M) classification and improved performance on Node (N) classification.

[Arxiv](https://arxiv.org/abs/2404.01589)