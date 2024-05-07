# MedDoc-Bot：一款针对儿童高血压指南情境下，用于对比分析大型语言模型的智能聊天工具。

发布时间：2024年05月06日

`LLM应用`

> MedDoc-Bot: A Chat Tool for Comparative Analysis of Large Language Models in the Context of the Pediatric Hypertension Guideline

# 摘要

> 本研究旨在评估几款非商业开源的大型语言模型（LLMs），包括Meditron、MedAlpaca、Mistral和Llama-2，它们在解读PDF格式保存的医疗指南方面的效能。以欧洲心脏病学会（ESC）发布的儿童和青少年高血压指南为测试案例，我们利用Python库Streamlit开发了一个易于使用的医疗文档聊天机器人工具——MedDoc-Bot。该工具允许授权用户上传PDF文件并提问，由四个本地存储的LLMs提供解释性回答。一位儿科专家通过提出问题并从ESC指南中提取答案，为评估设定了基准。专家根据回答的准确性和相关性对模型生成的回答进行评分。我们还通过METEOR和chrF指标来评估模型回答与参考答案的相似度。研究发现，Llama-2和Mistral在指标评估上表现优异，尽管Llama-2在处理文本和表格数据时稍显缓慢。在人类评估中，Mistral、Meditron和Llama-2生成的回答在准确性和相关性上都达到了合理水平。这项研究为LLMs在医学文档解读领域的未来发展提供了深刻的洞见。开源代码链接：https://github.com/yaseen28/MedDoc-Bot

> This research focuses on evaluating the non-commercial open-source large language models (LLMs) Meditron, MedAlpaca, Mistral, and Llama-2 for their efficacy in interpreting medical guidelines saved in PDF format. As a specific test scenario, we applied these models to the guidelines for hypertension in children and adolescents provided by the European Society of Cardiology (ESC). Leveraging Streamlit, a Python library, we developed a user-friendly medical document chatbot tool (MedDoc-Bot). This tool enables authorized users to upload PDF files and pose questions, generating interpretive responses from four locally stored LLMs. A pediatric expert provides a benchmark for evaluation by formulating questions and responses extracted from the ESC guidelines. The expert rates the model-generated responses based on their fidelity and relevance. Additionally, we evaluated the METEOR and chrF metric scores to assess the similarity of model responses to reference answers. Our study found that Llama-2 and Mistral performed well in metrics evaluation. However, Llama-2 was slower when dealing with text and tabular data. In our human evaluation, we observed that responses created by Mistral, Meditron, and Llama-2 exhibited reasonable fidelity and relevance. This study provides valuable insights into the strengths and limitations of LLMs for future developments in medical document interpretation. Open-Source Code: https://github.com/yaseen28/MedDoc-Bot

[Arxiv](https://arxiv.org/abs/2405.03359)