# LlamaCare：大型医疗语言模型，助力医疗知识共享

发布时间：2024年06月04日

`LLM应用

这篇论文介绍了专门为医疗领域微调的大型语言模型（LLMs）——LlamaCare，以及Extended Classification Integration（ECI）模块，旨在解决LLMs在医疗领域的分类问题。论文中提到的成果包括微调模型的环境友好性、ECI模块对分类性能的提升，以及公开的数据集支持高效训练。这些内容直接关联到LLMs在特定应用领域的优化和改进，因此属于LLM应用分类。` `语言模型微调`

> LlamaCare: A Large Medical Language Model for Enhancing Healthcare Knowledge Sharing

# 摘要

> 大型语言模型（LLMs）虽在知识记忆和呈现上表现卓越，但在特定领域如医疗，其精确回答能力不足。此外，尽管通过指令调整希望LLMs能直接分类，结果却常不尽人意。为此，我们推出了LlamaCare，一款专为医疗领域微调的语言模型，以及Extended Classification Integration（ECI）模块，专门解决LLMs的分类难题。我们的成果有三：首先，我们以极低的碳排放量微调了医疗语言模型，性能媲美ChatGPT，仅需24G GPU；其次，通过ECI模块，我们有效减少了分类答案的冗余，提升了LLMs的表现；最后，我们公开了处理后的数据集，支持PubMedQA和USMLE等基准的一次性和少量样本训练，效果接近顶尖模型，且GPU资源消耗更少。详情及资源请访问https://github.com/Stephen-SMJ/LLamaCare。

> Large language models (LLMs) have shown amazing capabilities in knowledge memorization and present. However, when it comes to domain-specific knowledge and downstream tasks like medical, general LLMs are often unable to give precise answers. In addition, when people want LLMs to answer classification questions, they usually go through instruction tuning first, however, LLMs do not always give a direct index of the categorization after instruction tuning. In this paper, we proposed LlamaCare, a fine-tuned medical language model, and Extended Classification Integration(ECI), a module to handle classification problems of LLMs. Our contributions are : (i) We fine-tuned a large language model of medical knowledge with very low carbon emissions and achieved similar performance with ChatGPT by a 24G GPU. (ii) We solved the problem of redundant categorical answers and improved the performance of LLMs by proposing a new module called Extended Classification Integration. (iii) We released our processed data for one-shot and few-shot training for some benchmarks such as PubMedQA and USMLE 1-3 step. Our method achieves a close effect with the state-of-the-art model in benchmarks while costing lower GPU resources compared to LLMs with the same quantity of parameters. Our models, codes, and datasets can be found in https://github.com/Stephen-SMJ/LLamaCare

[Arxiv](https://arxiv.org/abs/2406.02350)