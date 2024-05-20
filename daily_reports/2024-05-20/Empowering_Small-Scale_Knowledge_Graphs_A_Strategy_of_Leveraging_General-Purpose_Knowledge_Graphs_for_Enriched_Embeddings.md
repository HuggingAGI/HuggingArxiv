# 小型知识图谱的强化策略：借助通用知识图谱，提升嵌入丰富度
发布时间：2024年05月17日

`知识图谱`
> Empowering Small-Scale Knowledge Graphs: A Strategy of Leveraging General-Purpose Knowledge Graphs for Enriched Embeddings
>
> 知识密集型任务对机器学习技术构成挑战，大型语言模型等常用方法在此类任务中常显局限。为此，研究者们正通过知识图谱增强LLMs，以缓解这一问题。尽管知识图谱在知识表示上优势明显，但其高昂的开发成本限制了其广泛应用。为此，我们提出了一种框架，通过通用目的知识图谱来增强小型特定领域知识图谱的嵌入。实验表明，当特定领域KG与大型通用目的KG相连时，下游任务性能可提升高达44%。这一研究方向有望推动知识图谱在知识密集型任务中的更广泛应用，从而实现更稳健、可靠的机器学习解决方案，减少幻觉现象。关键词：知识图谱，知识图谱补全，实体对齐，表示学习，机器学习
>
> https://arxiv.org/abs/2405.10745

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10745/alignment.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10745/overview.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10745/boost.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10745/results_WN18RR.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10745/results_FB15K237.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10745/results_WD50K.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.10745/loss_comparison.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.10745](https://arxiv.org/abs/2405.10745)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 公众号回复关键词获取论文原文： 1522485185481182