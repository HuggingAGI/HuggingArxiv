# AIDBench：评估大型语言模型作者身份识别能力的基准

发布时间：2024年11月20日

`LLM应用` `隐私保护`

> AIDBench: A benchmark for evaluating the authorship identification capability of large language models

# 摘要

> 随着大型语言模型（LLMs）快速发展并融入日常生活，其带来的隐私风险愈发受到关注。我们聚焦于一种特定的隐私风险，即LLMs可能会助力识别匿名文本的作者身份，这对诸如匿名同行评审系统等现实世界中的匿名有效性形成挑战。为探究这些风险，我们推出了AIDBench，这一新基准整合了若干作者身份识别数据集，涵盖电子邮件、博客、评论、文章及研究论文等。AIDBench运用了两种评估方式：一对一作者身份识别，用于判定两篇文本是否出自同一作者；一对多作者身份识别，即给定一个查询文本和一个候选文本列表，找出最有可能与查询文本为同一作者所写的候选文本。我们还引入了基于检索增强生成（RAG）的方法来提升LLMs的大规模作者身份识别能力，特别是在输入长度超出模型的上下文窗口时，由此为利用LLMs进行作者身份识别确立了新的基准。我们通过AIDBench开展的实验表明，LLMs能够正确猜测作者身份的几率远高于随机水平，揭示了这些强大模型所带来的新隐私风险。源代码和数据在被接收后将予以公开。

> As large language models (LLMs) rapidly advance and integrate into daily life, the privacy risks they pose are attracting increasing attention. We focus on a specific privacy risk where LLMs may help identify the authorship of anonymous texts, which challenges the effectiveness of anonymity in real-world systems such as anonymous peer review systems. To investigate these risks, we present AIDBench, a new benchmark that incorporates several author identification datasets, including emails, blogs, reviews, articles, and research papers. AIDBench utilizes two evaluation methods: one-to-one authorship identification, which determines whether two texts are from the same author; and one-to-many authorship identification, which, given a query text and a list of candidate texts, identifies the candidate most likely written by the same author as the query text. We also introduce a Retrieval-Augmented Generation (RAG)-based method to enhance the large-scale authorship identification capabilities of LLMs, particularly when input lengths exceed the models' context windows, thereby establishing a new baseline for authorship identification using LLMs. Our experiments with AIDBench demonstrate that LLMs can correctly guess authorship at rates well above random chance, revealing new privacy risks posed by these powerful models. The source code and data will be made publicly available after acceptance.

[Arxiv](https://arxiv.org/abs/2411.13226)