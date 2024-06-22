# R^2AG：融合检索信息的增强生成技术
发布时间：2024年06月19日

`RAG`
> R^2AG: Incorporating Retrieval Information into Retrieval Augmented Generation
>
> 检索增强生成（RAG）已广泛应用于各种情境，旨在通过外部文档增强大型语言模型（LLMs）的能力。然而，由于训练目标和架构的不同，LLMs与检索器之间存在语义鸿沟，导致LLMs在生成过程中被动接受并需辨别检索器提供的文档。为此，本文创新性地提出了R²AG框架，通过整合检索信息来弥合这一鸿沟。R²AG巧妙地利用检索器的细微特征，并通过R²-Former捕捉这些信息，进而设计了一种检索感知的提示策略，将这些信息融入LLMs的生成过程。特别地，R²AG在LLMs和检索器固定的低资源环境下表现出色。通过跨五个数据集的广泛实验，R²AG展现了其有效性、鲁棒性和效率。分析表明，检索信息如同锚点，助力LLMs在生成中填补语义鸿沟。
>
> https://arxiv.org/abs/2406.13249

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.13249/x8.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.13249](https://arxiv.org/abs/2406.13249)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2