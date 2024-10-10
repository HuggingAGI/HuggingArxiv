# KnowledgeSG：通过服务器知识蒸馏实现隐私保护的合成文本生成

发布时间：2024年10月08日

`LLM应用`

> KnowledgeSG: Privacy-Preserving Synthetic Text Generation with Knowledge Distillation from Server

# 摘要

> 大型语言模型 (LLM) 的成功促使各方在其私有数据上进行微调，但这也引发了隐私问题。现有解决方案难以兼顾性能提升与隐私保护，要么依赖本地模型导致性能下降，要么通过 API 直接暴露数据。为此，我们提出了 \textit{KnowledgeSG}，一种创新的客户端-服务器框架，通过差分隐私 (DP) 学习本地知识并从服务器提取专业知识，在确保隐私的同时提升合成数据质量和模型性能。我们还借鉴联邦学习，在客户端和服务器之间传输模型而非数据，以防止隐私泄露。在医疗和金融领域的实验充分验证了 KnowledgeSG 的有效性。代码已公开，详见 https://github.com/wwh0411/KnowledgeSG。

> The success of large language models (LLMs) facilitate many parties to fine-tune LLMs on their own private data. However, this practice raises privacy concerns due to the memorization of LLMs. Existing solutions, such as utilizing synthetic data for substitution, struggle to simultaneously improve performance and preserve privacy. They either rely on a local model for generation, resulting in a performance decline, or take advantage of APIs, directly exposing the data to API servers. To address this issue, we propose \textit{KnowledgeSG}, a novel client-server framework which enhances synthetic data quality and improves model performance while ensuring privacy. We achieve this by learning local knowledge from the private data with differential privacy (DP) and distilling professional knowledge from the server. Additionally, inspired by federated learning, we transmit models rather than data between the client and server to prevent privacy leakage. Extensive experiments in medical and financial domains demonstrate the effectiveness of KnowledgeSG. Our code is now publicly available at https://github.com/wwh0411/KnowledgeSG.

[Arxiv](https://arxiv.org/abs/2410.05725)