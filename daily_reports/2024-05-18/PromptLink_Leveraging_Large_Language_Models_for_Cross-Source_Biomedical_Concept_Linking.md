# PromptLink：借助大型语言模型实现跨源生物医学概念的精准链接
发布时间：2024年05月13日

`提示工程`
> PromptLink: Leveraging Large Language Models for Cross-Source Biomedical Concept Linking
>
> 在多样数据源中对齐生物医学概念，为综合分析开辟了新途径，但命名惯例的差异使得这一过程颇具挑战。尽管已有基于字符串匹配、手工词典和机器学习的方法，但它们受限于先验知识的匮乏，难以广泛应用。大型语言模型（LLMs）凭借其深厚的知识储备和零-shot预测能力，在生物医学NLP领域大放异彩，但高昂成本、短上下文和预测不稳定性仍是其软肋。为此，我们推出了PromptLink，一种创新的生物医学概念链接框架，巧妙地利用了LLMs。它首先通过生物医学专用的预训练语言模型，筛选出适合LLM上下文窗口的候选概念，随后通过两阶段提示机制，引导LLM利用其内在的生物医学知识进行概念链接，并通过自我反思提升预测的可靠性。实证研究表明，PromptLink在链接两个EHR数据集与外部生物医学知识图谱的概念时表现出色。更重要的是，PromptLink不依赖额外知识、上下文或训练数据，适用于各种数据源，其源代码已公开于https://github.com/constantjxyz/PromptLink。
>
> https://arxiv.org/abs/2405.07500

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.07500/figure1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.07500/figure2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.07500/nil.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.07500](https://arxiv.org/abs/2405.07500)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 5122581114152544