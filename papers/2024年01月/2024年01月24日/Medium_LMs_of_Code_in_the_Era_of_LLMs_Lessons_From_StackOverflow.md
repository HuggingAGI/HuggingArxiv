# 在大型语言模型（LLMs）盛行的时代，我们探讨了“中等规模”的代码语言模型（"Medium" LMs of Code），并从 StackOverflow 的经验中汲取教训。

发布时间：2024年01月24日

`LLM应用` `软件工程`

> "Medium" LMs of Code in the Era of LLMs: Lessons From StackOverflow

# 摘要

> 大型预训练神经语言模型极大地推动了自然语言处理和软件工程的发展。OpenAI的GPT系列模型超越了Google的BERT和Meta的RoBERTa，后者曾刷新了多项NLP应用的性能记录。这些模型通过海量网络爬取的多样化数据进行训练，从而掌握了通用的语言模式和语义联系。尽管如此，最大规模的模型不仅训练成本高昂，而且往往是闭源的，限制了我们对其数据和设计选择的了解。我们认为，对于这种大型通用模型的依赖应当辅以特定用途、规模适中的预训练模型。本研究以StackOverflow（SO）为案例，利用其丰富的代码和文本数据进行研究。我们遵循预训练大型语言模型的常规方法，采用大上下文尺寸（2,048个标记）、大批量尺寸（0.5M个标记）和庞大的训练集（27B个标记），并结合Megatron-LM这一强大工具，训练了两个模型：SOBertBase（109M参数）和SOBertLarge（762M参数），每个模型的预算分别仅为187美元和800美元。我们对这两个模型在四个SO特定的下游任务上的表现进行了评估，包括问题质量预测、封闭式问题预测、命名实体识别和过时预测（我们新引入的任务）。我们的模型在所有比较中均优于现有基准，且较小的模型已足够取得优异成绩。目前，这两个模型均已公开发布。这些成果证明了在特定领域数据上进行全面且恰当的预训练，可以成为利用闭源通用模型的有力且经济的替代方案。

> Large pre-trained neural language models have brought immense progress to both NLP and software engineering. Models in OpenAI's GPT series now dwarf Google's BERT and Meta's RoBERTa, which previously set new benchmarks on a wide range of NLP applications. These models are trained on massive corpora of heterogeneous data from web crawls, which enables them to learn general language patterns and semantic relationships. However, the largest models are both expensive to train and deploy and are often closed-source, so we lack access to their data and design decisions. We argue that this trend towards large, general-purpose models should be complemented with single-purpose, more modestly sized pre-trained models. In this work, we take StackOverflow (SO) as a domain example in which large volumes of rich aligned code and text data is available. We adopt standard practices for pre-training large language models, including using a very large context size (2,048 tokens), batch size (0.5M tokens) and training set (27B tokens), coupled with a powerful toolkit (Megatron-LM), to train two models: SOBertBase, with 109M parameters, and SOBertLarge with 762M parameters, at a budget of just $\$187$ and $\$800$ each. We compare the performance of our models with both the previous SOTA model trained on SO data exclusively as well general-purpose BERT models and OpenAI's ChatGPT on four SO-specific downstream tasks - question quality prediction, closed question prediction, named entity recognition and obsoletion prediction (a new task we introduce). Not only do our models consistently outperform all baselines, the smaller model is often sufficient for strong results. Both models are released to the public. These results demonstrate that pre-training both extensively and properly on in-domain data can yield a powerful and affordable alternative to leveraging closed-source general-purpose models.

[Arxiv](https://arxiv.org/abs/2306.03268)