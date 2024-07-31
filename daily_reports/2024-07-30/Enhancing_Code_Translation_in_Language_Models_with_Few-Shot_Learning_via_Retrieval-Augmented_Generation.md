# 借助检索增强生成技术，少量样本学习能有效提升语言模型中的代码翻译能力。
发布时间：2024年07月28日

`RAG`
> Enhancing Code Translation in Language Models with Few-Shot Learning via Retrieval-Augmented Generation
>
> 大型语言模型 (LLM) 的兴起极大地推动了代码翻译领域，实现了编程语言间的自动化转换。然而，这些模型在处理复杂任务时，因上下文理解不足而常显疲态。本文提出了一种创新方法，结合少样本学习和基于检索的技术，通过动态利用现有代码翻译库中的相关示例，指导模型进行新代码段的翻译。基于检索增强生成 (RAG) 的方法，通过实时提供的上下文示例，大幅提升了翻译质量。相较于传统微调方法，RAG 能利用现有代码库或本地代码语料库，无需大规模重新训练即可适应多样翻译任务。在包括 Starcoder、Llama3-70B Instruct 等开源模型及 GPT-3.5 Turbo 等商业模型在内的多样化数据集上进行的实验，显示了我们的方法在 Fortran 和 CPP 翻译中的显著优势。此外，我们还测试了不同数量的示例和嵌入模型，以验证方法的鲁棒性和有效性。
>
> https://arxiv.org/abs/2407.19619


<hr />

- 论文原文: [https://arxiv.org/abs/2407.19619](https://arxiv.org/abs/2407.19619)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1