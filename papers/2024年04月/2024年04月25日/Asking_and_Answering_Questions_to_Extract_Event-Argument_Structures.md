# 通过提问和回答的方式来抽取事件及其论元结构。

发布时间：2024年04月25日

`分类：LLM应用

这篇论文的摘要描述了一种基于问答的文档级事件-论元结构提取方法，其中使用了大型语言模型（LLM）来生成问题，并通过数据增强策略来提高模型性能。这表明该研究主要关注于如何将大型语言模型应用于实际问题，即事件-论元结构提取，因此可以归类为LLM应用。` `事件抽取`

> Asking and Answering Questions to Extract Event-Argument Structures

# 摘要

> 本研究介绍了一种基于问答的文档级事件-论元结构提取方法。我们自动针对事件可能涉及的每种论元类型提出并解答问题，这些问题通过手动设计的模板和生成式变换器来生成。模板问题利用文档上下文中的预定义角色特定疑问词和事件触发词来构建。而变换器问题则是利用训练有素的大型语言模型，根据段落内容和预期答案来生成问题。我们还开发了创新的数据增强策略，专注于加强句子间事件-论元关系的理解。通过简单的跨度交换技术、共指消解以及大型语言模型，我们扩充了训练样本。该方法支持无需针对特定语料库进行修改的迁移学习，并在 RAMS 数据集上取得了优异的成绩，超越了先前的研究，尤其是在抽取那些与事件触发词位于不同句子中的论元时表现出色。此外，我们还进行了深入的定量和定性分析，揭示了我们模型最常见的错误类型。

> This paper presents a question-answering approach to extract document-level event-argument structures. We automatically ask and answer questions for each argument type an event may have. Questions are generated using manually defined templates and generative transformers. Template-based questions are generated using predefined role-specific wh-words and event triggers from the context document. Transformer-based questions are generated using large language models trained to formulate questions based on a passage and the expected answer. Additionally, we develop novel data augmentation strategies specialized in inter-sentential event-argument relations. We use a simple span-swapping technique, coreference resolution, and large language models to augment the training instances. Our approach enables transfer learning without any corpora-specific modifications and yields competitive results with the RAMS dataset. It outperforms previous work, and it is especially beneficial to extract arguments that appear in different sentences than the event trigger. We also present detailed quantitative and qualitative analyses shedding light on the most common errors made by our best model.

[Arxiv](https://arxiv.org/abs/2404.16413)