# 在白盒语言模型的有监督微调中的主动隐私审计

发布时间：2024年11月11日

`LLM应用` `隐私保护`

> On Active Privacy Auditing in Supervised Fine-tuning for White-Box Language Models

# 摘要

> 预训练和微调方法已成为各种自然语言处理（NLP）应用的领先技术。然而，最近的研究表明，由于微调数据的敏感性、特定领域的特征和可识别性，它们引发了重大的隐私问题。为了帮助开发更具隐私弹性的微调模型，我们引入了一个新颖的主动隐私审计框架，称为 Parsing，旨在识别和量化语言模型（LMs）监督微调（SFT）期间的隐私泄露风险。该框架利用改进的白盒成员推理攻击（MIAs）作为核心技术，利用新颖的学习目标和两阶段管道来监控 LMs 微调过程的隐私，最大限度地暴露隐私风险。此外，我们提高了 MIAs 在包括 GPT-2、Llama2 及其某些变体在内的大型 LMs 上的有效性。我们的研究旨在为 LMs 的 SFT 社区提供一个可靠、即用的隐私审计工具，并为微调过程中的隐私保护提供有价值的见解。实验结果证实了该框架在各种模型和任务中的效率，强调了微调过程中显著的隐私问题。项目代码可在 https://github.com/mapleleavesss/PARSING 获得。

> The pretraining and fine-tuning approach has become the leading technique for various NLP applications. However, recent studies reveal that fine-tuning data, due to their sensitive nature, domain-specific characteristics, and identifiability, pose significant privacy concerns. To help develop more privacy-resilient fine-tuning models, we introduce a novel active privacy auditing framework, dubbed Parsing, designed to identify and quantify privacy leakage risks during the supervised fine-tuning (SFT) of language models (LMs). The framework leverages improved white-box membership inference attacks (MIAs) as the core technology, utilizing novel learning objectives and a two-stage pipeline to monitor the privacy of the LMs' fine-tuning process, maximizing the exposure of privacy risks. Additionally, we have improved the effectiveness of MIAs on large LMs including GPT-2, Llama2, and certain variants of them. Our research aims to provide the SFT community of LMs with a reliable, ready-to-use privacy auditing tool, and to offer valuable insights into safeguarding privacy during the fine-tuning process. Experimental results confirm the framework's efficiency across various models and tasks, emphasizing notable privacy concerns in the fine-tuning process. Project code available for https://github.com/mapleleavesss/PARSING.

[Arxiv](https://arxiv.org/abs/2411.07070)