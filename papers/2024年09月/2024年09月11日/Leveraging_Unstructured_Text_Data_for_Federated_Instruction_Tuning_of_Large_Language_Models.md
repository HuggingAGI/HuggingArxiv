# 借助非结构化文本数据，实现大型语言模型的联邦指令调优

发布时间：2024年09月11日

`LLM应用`

> Leveraging Unstructured Text Data for Federated Instruction Tuning of Large Language Models

# 摘要

> 联邦指令微调让多个客户端能够协作微调一个共享的 LLM，使其遵循人类指令，而无需共享原始数据。然而，现有方法要求所有客户端都准备好结构化的指令-响应对数据，这需要大量人工标注，因为客户端数据通常是非结构化的。为此，我们提出了 FedIT-U2S 框架，它能自动将非结构化语料转换为结构化数据，用于联邦指令微调。FedIT-U2S 包含两个关键步骤：首先，通过少样本生成指令-响应对，并采用基于检索的示例选择技术，自动选择相关示例；其次，基于生成数据进行联邦指令微调。只要客户端持有有价值的文本语料，FedIT-U2S 就能应用于各种场景，扩大了联邦指令微调的应用范围。我们在医学、知识和数学领域进行了实验，结果显示 FedIT-U2S 能持续显著提升基础 LLM 的性能。

> Federated instruction tuning enables multiple clients to collaboratively fine-tune a shared large language model (LLM) that can follow humans' instructions without directly sharing raw data. However, existing literature impractically requires that all the clients readily hold instruction-tuning data (i.e., structured instruction-response pairs), which necessitates massive human annotations since clients' data is usually unstructured text instead. Addressing this, we propose a novel and flexible framework FedIT-U2S, which can automatically transform unstructured corpus into structured data for federated instruction tuning. FedIT-U2S consists two key steps: (1) few-shot instruction-tuning data generation, where each unstructured data piece together with several examples is combined to prompt an LLM in generating an instruction-response pair. To further enhance the flexibility, a retrieval-based example selection technique is proposed, where the examples are automatically selected based on the relatedness between the client's data piece and example pool, bypassing the need of determining examples in advance. (2) A typical federated instruction tuning process based on the generated data. Overall, FedIT-U2S can be applied to diverse scenarios as long as the client holds valuable text corpus, broadening the application scope of federated instruction tuning. We conduct a series of experiments on three domains (medicine, knowledge, and math), showing that our proposed FedIT-U2S can consistently and significantly brings improvement over the base LLM.

[Arxiv](https://arxiv.org/abs/2409.07136)