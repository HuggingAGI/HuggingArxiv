# 科学问答系统：答案可验证
发布时间：2024年07月16日

`RAG`
> Scientific QA System with Verifiable Answers
>
> 本文介绍了VerifAI项目，这是一个前沿的开源科学问答系统，旨在提供不仅基于参考文献，还经过自动审查和验证的答案。系统包含三个核心部分：（1）结合语义和词汇搜索技术的信息检索系统，覆盖科学论文（如PubMed）；（2）利用微调生成模型（如Mistral 7B）和检索文章的检索增强生成（RAG）模块，生成附有来源文章引用的声明；（3）基于在SciFACT数据集上微调的DeBERTa和XLM-RoBERTa模型的验证引擎，确保生成的声明与来源文章一致，无幻觉产生。Verif.ai通过信息检索和RAG模块，从众多科学资源中提炼事实信息，而验证引擎则严格复核这些信息，确保其精确可靠。这一双重验证流程在确保信息准确性方面至关重要，极大提升了信息质量。我们的方法不仅提升科学家工作效率，还增强了在科学领域内使用生成语言模型的信任度，因为该领域不容许幻觉和错误信息的存在。
>
> https://arxiv.org/abs/2407.11485


<hr />

- 论文原文: [https://arxiv.org/abs/2407.11485](https://arxiv.org/abs/2407.11485)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1