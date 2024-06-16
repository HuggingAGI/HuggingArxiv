# 探究文档级关系抽取模型在实体名称变化下的稳健性
发布时间：2024年06月11日

`知识图谱`
> On the Robustness of Document-Level Relation Extraction Models to Entity Name Variations
>
> 随着对跨句子和大规模关系抽取的需求日益增长，文档级关系抽取（DocRE）成为了研究热点。尽管现有模型性能不断提升，但当文档中的实体名称被替换时，这些模型往往会出现更多错误，限制了对新实体名称的适应性。为此，我们深入探讨了DocRE模型对实体名称变化的鲁棒性。我们设计了一套流程，利用Wikidata中的名称替换文档中的原始实体名称，从而创建了Env-DocRED和Env-Re-DocRED两个新的鲁棒性测试基准。实验揭示，无论是三种主流的DocRE模型还是两种基于上下文学习的大型语言模型，在处理实体名称变化时都显示出鲁棒性的不足，尤其是在涉及跨句关系和实体较多的文档中。为此，我们开发了一种增强鲁棒性的训练方法，不仅提升了模型对实体变化的抵抗力，还加强了其理解和推理能力。此外，这种方法的核心理念也被证实适用于DocRE的上下文学习。
>
> https://arxiv.org/abs/2406.07444

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07444/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07444/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07444/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07444/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.07444/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.07444](https://arxiv.org/abs/2406.07444)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2