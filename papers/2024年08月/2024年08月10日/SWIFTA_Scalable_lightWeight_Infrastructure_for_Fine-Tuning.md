# SWIFT：一款专为微调设计的可扩展轻量级基础设施

发布时间：2024年08月10日

`LLM应用` `人工智能` `软件开发`

> SWIFT:A Scalable lightWeight Infrastructure for Fine-Tuning

# 摘要

> 大型语言模型 (LLM) 和多模态大型语言模型 (MLLM) 的最新进展，借助基于注意力的 Transformer 架构，实现了卓越性能和泛化能力，覆盖了传统学习任务的广泛领域。例如，文本分类、序列标注等文本任务，以及视觉问答 (VQA) 和光学字符识别 (OCR) 等多模态任务，现在都能基于一个基础模型解决。因此，LLM 和 MLLM 的训练与轻量级微调，尤其是基于 Transformer 架构的，变得尤为关键。为满足这些迫切需求，我们开发了 SWIFT，一个为大型模型提供一站式定制基础设施的开源框架。它支持超过 300 个 LLM 和 50 个 MLLM，为大型模型的微调提供了最全面的支持，尤其是首个为 MLLM 提供系统支持的训练框架。SWIFT 不仅集成了核心的微调功能，还整合了推理、评估和模型量化等训练后流程，助力大型模型在多样应用场景中的快速部署。通过系统集成多种训练技术，SWIFT 提供了大型模型训练技术的基准比较等实用工具。对于专注于代理框架的微调模型，我们通过在 SWIFT 上使用定制数据集训练，实现了 ToolBench 排行榜上的显著提升，Act.EM 指标提升 5.2%-21.8%，幻觉减少 1.6%-14.1%，平均性能提升 8%-17%。

> Recent development in Large Language Models (LLMs) and Multi-modal Large Language Models (MLLMs) have leverage Attention-based Transformer architectures and achieved superior performance and generalization capabilities. They have since covered extensive areas of traditional learning tasks. For instance, text-based tasks such as text-classification and sequence-labeling, as well as multi-modal tasks like Visual Question Answering (VQA) and Optical Character Recognition (OCR), which were previously addressed using different models, can now be tackled based on one foundation model. Consequently, the training and lightweight fine-tuning of LLMs and MLLMs, especially those based on Transformer architecture, has become particularly important. In recognition of these overwhelming needs, we develop SWIFT, a customizable one-stop infrastructure for large models. With support of over $300+$ LLMs and $50+$ MLLMs, SWIFT stands as the open-source framework that provide the \textit{most comprehensive support} for fine-tuning large models. In particular, it is the first training framework that provides systematic support for MLLMs. In addition to the core functionalities of fine-tuning, SWIFT also integrates post-training processes such as inference, evaluation, and model quantization, to facilitate fast adoptions of large models in various application scenarios. With a systematic integration of various training techniques, SWIFT offers helpful utilities such as benchmark comparisons among different training techniques for large models. For fine-tuning models specialized in agent framework, we show that notable improvements on the ToolBench leader-board can be achieved by training with customized dataset on SWIFT, with an increase of 5.2\%-21.8\% in the Act.EM metric over various baseline models, a reduction in hallucination by 1.6\%-14.1\%, and an average performance improvement of 8\%-17\%.

[Arxiv](https://arxiv.org/abs/2408.05517)