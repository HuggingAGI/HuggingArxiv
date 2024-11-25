# UniHGKR：统一的指令感知型异构知识检索器

发布时间：2024年10月26日

`LLM应用` `信息检索` `问答系统`

> UniHGKR: Unified Instruction-aware Heterogeneous Knowledge Retrievers

# 摘要

> 现有的信息检索（IR）模型往往假定知识源和用户查询是同质结构，这在检索本就异质且多样的现实场景中限制了其适用性。本文中，我们推出了 UniHGKR，这是一个统一的指令感知异构知识检索器，它（1）为异构知识构建统一的检索空间，（2）依照不同的用户指令来检索特定类型的知识。UniHGKR 包含三个主要阶段：异构自监督预训练、文本锚定嵌入对齐以及指令感知检索器微调，使其能够在各类检索情境中通用。该框架具有高度可扩展性，有基于 BERT 的版本和在大型语言模型上训练的 UniHGKR-7B 版本。另外，我们引入了 CompMix-IR，这是首个原生的异构知识检索基准。它涵盖了两种带有各种指令的检索场景、超过 9400 个问答（QA）对以及一个包含 1000 万条目的语料库，涉及四种不同类型的数据。大量实验表明，UniHGKR 在 CompMix-IR 上始终优于前沿方法，在两种场景中分别实现了高达 6.36％和 54.23％的相对提升。最后，为开放域异构 QA 系统配备我们的检索器后，我们在热门的 ConvMix 任务上取得了新的前沿成果，绝对提升高达 4.80 分。

> Existing information retrieval (IR) models often assume a homogeneous structure for knowledge sources and user queries, limiting their applicability in real-world settings where retrieval is inherently heterogeneous and diverse. In this paper, we introduce UniHGKR, a unified instruction-aware heterogeneous knowledge retriever that (1) builds a unified retrieval space for heterogeneous knowledge and (2) follows diverse user instructions to retrieve knowledge of specified types. UniHGKR consists of three principal stages: heterogeneous self-supervised pretraining, text-anchored embedding alignment, and instruction-aware retriever fine-tuning, enabling it to generalize across varied retrieval contexts. This framework is highly scalable, with a BERT-based version and a UniHGKR-7B version trained on large language models. Also, we introduce CompMix-IR, the first native heterogeneous knowledge retrieval benchmark. It includes two retrieval scenarios with various instructions, over 9,400 question-answer (QA) pairs, and a corpus of 10 million entries, covering four different types of data. Extensive experiments show that UniHGKR consistently outperforms state-of-the-art methods on CompMix-IR, achieving up to 6.36% and 54.23% relative improvements in two scenarios, respectively. Finally, by equipping our retriever for open-domain heterogeneous QA systems, we achieve a new state-of-the-art result on the popular ConvMix task, with an absolute improvement of up to 4.80 points.

[Arxiv](https://arxiv.org/abs/2410.20163)