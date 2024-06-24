# GIEBench：大型语言模型群体身份同理心评估的综合框架

发布时间：2024年06月21日

`LLM应用

这篇论文介绍了GIEBench，一个专门设计来评估大型语言模型（LLMs）在面对特定群体身份时的同理心反应的基准。它关注的是LLMs在理解和尊重不同群体身份多样性方面的应用，而不是理论探讨或模型架构的改进。因此，它属于LLM应用分类。` `社会科学` `人工智能`

> GIEBench: Towards Holistic Evaluation of Group Indentity-based Empathy for Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的进步，其对不同群体展现同理心并理解其观点的能力愈发关键。现有的评估基准多聚焦于普遍情感，忽视了群体身份的背景。为此，我们开发了GIEBench，一个包含11个身份维度、涵盖97个群体身份及999个相关单选题的全面基准，旨在评估LLMs在面对特定群体身份时的同理心反应。我们的研究发现，尽管LLMs能理解不同身份立场，但在无明确指示下，它们在不同身份上的同理心表现并不一致，这表明需要进一步优化LLMs以适应多元价值观，更好地理解和尊重人类身份的多样性。数据集已公开于https://github.com/GIEBench/GIEBench。

> As large language models (LLMs) continue to develop and gain widespread application, the ability of LLMs to exhibit empathy towards diverse group identities and understand their perspectives is increasingly recognized as critical. Most existing benchmarks for empathy evaluation of LLMs focus primarily on universal human emotions, such as sadness and pain, often overlooking the context of individuals' group identities. To address this gap, we introduce GIEBench, a comprehensive benchmark that includes 11 identity dimensions, covering 97 group identities with a total of 999 single-choice questions related to specific group identities. GIEBench is designed to evaluate the empathy of LLMs when presented with specific group identities such as gender, age, occupation, and race, emphasizing their ability to respond from the standpoint of the identified group. This supports the ongoing development of empathetic LLM applications tailored to users with different identities. Our evaluation of 23 LLMs revealed that while these LLMs understand different identity standpoints, they fail to consistently exhibit equal empathy across these identities without explicit instructions to adopt those perspectives. This highlights the need for improved alignment of LLMs with diverse values to better accommodate the multifaceted nature of human identities. Our datasets are available at https://github.com/GIEBench/GIEBench.

[Arxiv](https://arxiv.org/abs/2406.14903)