# 通过提问和回答，我们能够抽取事件及其论元的结构。

发布时间：2024年04月25日

`LLM应用` `事件抽取`

> Asking and Answering Questions to Extract Event-Argument Structures

# 摘要

> 本研究介绍了一种基于问答的文档级事件-论元结构提取方法。我们针对每个事件可能涉及的论元类型，自动生成并回答相关问题。这些问题利用预先定义的模板和生成式变换器来构建。模板问题通过上下文文档中的角色特定 wh-words 和事件触发器来生成，而变换器问题则依赖于经过训练的大型语言模型，这些模型能够根据给定段落和预期答案来构建问题。此外，我们还开发了创新的数据增强策略，专注于加强句子间的事件-论元关系。通过简单的跨度交换技术、共指消解以及大型语言模型，我们扩充了训练样本。这种方法支持无需针对特定语料库进行修改的迁移学习，并在 RAMS 数据集上取得了优异的成绩，超越了先前的研究。它特别擅长提取那些与事件触发器位于不同句子中的论元。我们还提供了详尽的定量和定性分析，深入探讨了我们最先进模型所犯的常见错误。

> This paper presents a question-answering approach to extract document-level event-argument structures. We automatically ask and answer questions for each argument type an event may have. Questions are generated using manually defined templates and generative transformers. Template-based questions are generated using predefined role-specific wh-words and event triggers from the context document. Transformer-based questions are generated using large language models trained to formulate questions based on a passage and the expected answer. Additionally, we develop novel data augmentation strategies specialized in inter-sentential event-argument relations. We use a simple span-swapping technique, coreference resolution, and large language models to augment the training instances. Our approach enables transfer learning without any corpora-specific modifications and yields competitive results with the RAMS dataset. It outperforms previous work, and it is especially beneficial to extract arguments that appear in different sentences than the event trigger. We also present detailed quantitative and qualitative analyses shedding light on the most common errors made by our best model.

[Arxiv](https://arxiv.org/abs/2404.16413)