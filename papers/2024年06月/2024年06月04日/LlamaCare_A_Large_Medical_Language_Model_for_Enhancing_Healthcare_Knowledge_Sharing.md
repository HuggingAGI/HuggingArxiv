# LlamaCare：大型医疗语言模型，助力医疗知识共享

发布时间：2024年06月04日

`LLM应用

这篇论文主要介绍了针对医疗领域的特定需求，对大型语言模型（LLMs）进行微调和优化，以提高其在该领域的精确回答能力。具体来说，论文提出了名为LlamaCare的语言模型和Extended Classification Integration（ECI）模块，这些技术旨在改善LLMs在医疗分类问题上的表现。此外，论文还强调了其在资源效率方面的优势，即在保持高性能的同时，显著降低了GPU资源的消耗。这些内容表明，该论文属于LLM应用类别，因为它专注于特定领域的应用和模型优化，而不是理论研究或Agent、RAG相关的研究。` `语言模型微调`

> LlamaCare: A Large Medical Language Model for Enhancing Healthcare Knowledge Sharing

# 摘要

> 大型语言模型（LLMs）虽在知识记忆和呈现上表现卓越，但在特定领域如医疗领域，其精确回答能力常显不足。此外，尽管指令调整能帮助LLMs回答分类问题，但分类结果的直接索引并不总是明确。为此，我们提出了LlamaCare，一个专为医疗领域微调的语言模型，以及Extended Classification Integration（ECI）模块，专门解决LLMs的分类问题。我们的研究成果包括：(i) 在极低碳排放下，我们成功微调了一个医疗知识语言模型，其性能与ChatGPT相当，且仅使用24G GPU。(ii) 通过ECI模块，我们有效减少了分类答案的冗余，并提升了LLMs的性能。(iii) 我们公开了处理后的数据集，支持PubMedQA和USMLE等基准测试的一击和少击训练。我们的方法在保持与顶尖模型相近效果的同时，相比同等参数量的LLMs，显著降低了GPU资源消耗。所有模型、代码及数据集均可在https://github.com/Stephen-SMJ/LLamaCare获取。

> Large language models (LLMs) have shown amazing capabilities in knowledge memorization and present. However, when it comes to domain-specific knowledge and downstream tasks like medical, general LLMs are often unable to give precise answers. In addition, when people want LLMs to answer classification questions, they usually go through instruction tuning first, however, LLMs do not always give a direct index of the categorization after instruction tuning. In this paper, we proposed LlamaCare, a fine-tuned medical language model, and Extended Classification Integration(ECI), a module to handle classification problems of LLMs. Our contributions are : (i) We fine-tuned a large language model of medical knowledge with very low carbon emissions and achieved similar performance with ChatGPT by a 24G GPU. (ii) We solved the problem of redundant categorical answers and improved the performance of LLMs by proposing a new module called Extended Classification Integration. (iii) We released our processed data for one-shot and few-shot training for some benchmarks such as PubMedQA and USMLE 1-3 step. Our method achieves a close effect with the state-of-the-art model in benchmarks while costing lower GPU resources compared to LLMs with the same quantity of parameters. Our models, codes, and datasets can be found in https://github.com/Stephen-SMJ/LLamaCare

[Arxiv](https://arxiv.org/abs/2406.02350)