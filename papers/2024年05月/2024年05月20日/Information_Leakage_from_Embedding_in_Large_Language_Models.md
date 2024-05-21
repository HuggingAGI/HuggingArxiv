# 大型语言模型嵌入中的信息泄露

发布时间：2024年05月20日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）中的数据隐私问题，特别是通过输入重构攻击侵犯隐私的风险。论文提出了一种新的方法——“嵌入鹦鹉”，用于从深层嵌入中精准重构输入，并设计了一种防御机制来防止隐私泄露。这些内容直接关联到LLM的实际应用中的安全性和隐私保护问题，因此属于LLM应用分类。` `数据隐私` `网络安全`

> Information Leakage from Embedding in Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的普及，数据隐私问题日益凸显。本研究深入探讨了通过输入重构攻击侵犯隐私的风险，揭示了恶意模型提供者可能从嵌入中恢复用户输入的潜在威胁。我们首先提出了两种基本方法，用于从模型的隐藏状态重构原始文本，发现这些方法在浅层嵌入上效果显著，但在深层嵌入上效果减弱。为此，我们创新性地提出了基于Transformer的“嵌入鹦鹉”方法，专门用于从深层嵌入中精准重构输入。实验证明，“嵌入鹦鹉”在ChatGLM-6B和Llama2-7B模型上表现出色，无论令牌长度和数据分布如何变化，均能稳定重构原始输入。为了防范隐私泄露，我们设计了一种防御机制，有效阻止了对嵌入重构过程的滥用。本研究不仅强调了在分布式学习系统中保护用户隐私的紧迫性，也为提升此类环境的安全性提供了重要启示。

> The widespread adoption of large language models (LLMs) has raised concerns regarding data privacy. This study aims to investigate the potential for privacy invasion through input reconstruction attacks, in which a malicious model provider could potentially recover user inputs from embeddings. We first propose two base methods to reconstruct original texts from a model's hidden states. We find that these two methods are effective in attacking the embeddings from shallow layers, but their effectiveness decreases when attacking embeddings from deeper layers. To address this issue, we then present Embed Parrot, a Transformer-based method, to reconstruct input from embeddings in deep layers. Our analysis reveals that Embed Parrot effectively reconstructs original inputs from the hidden states of ChatGLM-6B and Llama2-7B, showcasing stable performance across various token lengths and data distributions. To mitigate the risk of privacy breaches, we introduce a defense mechanism to deter exploitation of the embedding reconstruction process. Our findings emphasize the importance of safeguarding user privacy in distributed learning systems and contribute valuable insights to enhance the security protocols within such environments.

[Arxiv](https://arxiv.org/abs/2405.11916)