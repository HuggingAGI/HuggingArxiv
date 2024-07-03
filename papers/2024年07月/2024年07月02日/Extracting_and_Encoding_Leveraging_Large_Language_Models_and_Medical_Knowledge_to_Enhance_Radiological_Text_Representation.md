# 借助大型语言模型与医学知识，我们致力于提升放射学文本的表达力。

发布时间：2024年07月02日

`LLM应用` `人工智能`

> Extracting and Encoding: Leveraging Large Language Models and Medical Knowledge to Enhance Radiological Text Representation

# 摘要

> 在医学等专业领域，由于缺乏专家注释，表示学习的进步面临挑战。为此，我们设计了一个两阶段框架，从放射学报告中提取高质量事实，以优化文本编码器的性能。首先，我们利用LLM从精选数据集中提取事实。接着，我们基于BERT模型，通过特定目标函数微调，引入CXRFE编码器。此外，我们还开发了CXRFEScore度量，用于评估胸部X射线文本生成系统。实验表明，我们的方法在多个任务中超越了现有技术，且CXRFEScore比传统度量更稳健有效。项目代码已公开在\url{https://github.com/PabloMessina/CXR-Fact-Encoder}。

> Advancing representation learning in specialized fields like medicine remains challenging due to the scarcity of expert annotations for text and images. To tackle this issue, we present a novel two-stage framework designed to extract high-quality factual statements from free-text radiology reports in order to improve the representations of text encoders and, consequently, their performance on various downstream tasks. In the first stage, we propose a \textit{Fact Extractor} that leverages large language models (LLMs) to identify factual statements from well-curated domain-specific datasets. In the second stage, we introduce a \textit{Fact Encoder} (CXRFE) based on a BERT model fine-tuned with objective functions designed to improve its representations using the extracted factual data. Our framework also includes a new embedding-based metric (CXRFEScore) for evaluating chest X-ray text generation systems, leveraging both stages of our approach. Extensive evaluations show that our fact extractor and encoder outperform current state-of-the-art methods in tasks such as sentence ranking, natural language inference, and label extraction from radiology reports. Additionally, our metric proves to be more robust and effective than existing metrics commonly used in the radiology report generation literature. The code of this project is available at \url{https://github.com/PabloMessina/CXR-Fact-Encoder}.

[Arxiv](https://arxiv.org/abs/2407.01948)