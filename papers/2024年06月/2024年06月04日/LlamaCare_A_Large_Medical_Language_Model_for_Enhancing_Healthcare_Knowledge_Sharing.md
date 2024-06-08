# LlamaCare：大型医学语言模型，助力医疗知识共享

发布时间：2024年06月04日

`LLM应用

这篇论文介绍了针对医疗领域的特定需求，开发并微调了一个大型语言模型（LlamaCare），并引入了Extended Classification Integration（ECI）模块来优化分类问题的解决。这一工作专注于提升LLMs在特定领域的应用性能，特别是在医疗领域，通过微调和模块优化，提高了模型的分类能力和整体性能。此外，论文还提到了公开的数据集和资源，这进一步支持了其在实际应用中的价值。因此，这篇论文属于LLM应用分类。` `语言模型微调`

> LlamaCare: A Large Medical Language Model for Enhancing Healthcare Knowledge Sharing

# 摘要

> 大型语言模型（LLMs）虽在知识记忆和呈现上表现卓越，但在特定领域如医疗领域，其精确回答能力不足。此外，尽管通过指令调整，LLMs在分类问题上的表现仍不尽人意。为此，我们开发了LlamaCare，一款专为医疗领域微调的语言模型，并引入了Extended Classification Integration（ECI）模块，有效解决了分类问题。我们的研究成果包括：(i) 利用低能耗的24G GPU，成功微调了医疗知识语言模型，性能媲美ChatGPT。(ii) 通过ECI模块，优化了分类答案，显著提升了LLMs的性能。(iii) 我们公开了处理后的数据集，支持PubMedQA和USMLE等基准测试的一击和少击训练，实现了与顶尖模型相媲美的效果，同时大幅降低了GPU资源消耗。所有模型、代码及数据集均可在https://github.com/Stephen-SMJ/LLamaCare获取。

> Large language models (LLMs) have shown amazing capabilities in knowledge memorization and present. However, when it comes to domain-specific knowledge and downstream tasks like medical, general LLMs are often unable to give precise answers. In addition, when people want LLMs to answer classification questions, they usually go through instruction tuning first, however, LLMs do not always give a direct index of the categorization after instruction tuning. In this paper, we proposed LlamaCare, a fine-tuned medical language model, and Extended Classification Integration(ECI), a module to handle classification problems of LLMs. Our contributions are : (i) We fine-tuned a large language model of medical knowledge with very low carbon emissions and achieved similar performance with ChatGPT by a 24G GPU. (ii) We solved the problem of redundant categorical answers and improved the performance of LLMs by proposing a new module called Extended Classification Integration. (iii) We released our processed data for one-shot and few-shot training for some benchmarks such as PubMedQA and USMLE 1-3 step. Our method achieves a close effect with the state-of-the-art model in benchmarks while costing lower GPU resources compared to LLMs with the same quantity of parameters. Our models, codes, and datasets can be found in https://github.com/Stephen-SMJ/LLamaCare

[Arxiv](https://arxiv.org/abs/2406.02350)