# OpenScholar：借助检索增强型语言模型来合成科学文献

发布时间：2024年11月21日

`LLM应用` `科学研究` `文献检索`

> OpenScholar: Synthesizing Scientific Literature with Retrieval-augmented LMs

# 摘要

> 科学的进步取决于研究人员综合日益增多的文献资料的能力。大型语言模型（LMs）能否助力科学家完成此项任务？我们推出了 OpenScholar，这是一款专门的检索增强型 LM，它能从 4500 万篇开放获取的论文中识别相关段落，并综合出有引文支持的回答来解答科学问题。为评估 OpenScholar，我们开发了 ScholarQABench，这是首个用于文献搜索的大规模多领域基准，涵盖了 2967 个专家编写的问题以及 208 个横跨计算机科学、物理学、神经科学和生物医学的长篇回答。在 ScholarQABench 上，OpenScholar-8B 的正确性比 GPT-4o 高 5%，比 PaperQA2 高 7%，尽管它是一个规模更小的开放模型。GPT4o 在 78%至 90%的时间里会虚构引文，而 OpenScholar 的引文准确性与人类专家相当。OpenScholar 的数据存储、检索器和自反馈推理循环也提升了现成的 LMs：比如，OpenScholar-GPT4o 让 GPT-4o 的正确性提高了 12%。在人类评估中，专家分别有 51%和 70%的时间更青睐 OpenScholar-8B 和 OpenScholar-GPT4o 的回答，而 GPT4o 仅为 32%。我们将所有的代码、模型、数据存储、数据以及一个公共演示进行了开源。

> Scientific progress depends on researchers' ability to synthesize the growing body of literature. Can large language models (LMs) assist scientists in this task? We introduce OpenScholar, a specialized retrieval-augmented LM that answers scientific queries by identifying relevant passages from 45 million open-access papers and synthesizing citation-backed responses. To evaluate OpenScholar, we develop ScholarQABench, the first large-scale multi-domain benchmark for literature search, comprising 2,967 expert-written queries and 208 long-form answers across computer science, physics, neuroscience, and biomedicine. On ScholarQABench, OpenScholar-8B outperforms GPT-4o by 5% and PaperQA2 by 7% in correctness, despite being a smaller, open model. While GPT4o hallucinates citations 78 to 90% of the time, OpenScholar achieves citation accuracy on par with human experts. OpenScholar's datastore, retriever, and self-feedback inference loop also improves off-the-shelf LMs: for instance, OpenScholar-GPT4o improves GPT-4o's correctness by 12%. In human evaluations, experts preferred OpenScholar-8B and OpenScholar-GPT4o responses over expert-written ones 51% and 70% of the time, respectively, compared to GPT4o's 32%. We open-source all of our code, models, datastore, data and a public demo.

[Arxiv](https://arxiv.org/abs/2411.14199)