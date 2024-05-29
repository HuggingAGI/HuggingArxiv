# 高效成本的大型语言模型知识问答
发布时间：2024年05月27日

`RAG`
> Cost-efficient Knowledge-based Question Answering with Large Language Models
>
> 基于知识的问答（KBQA）在众多领域知识驱动的场景中得到广泛应用。大型语言模型（LLMs）为KBQA开辟了新机遇，但高昂的成本和预训练中缺乏特定领域知识是其短板。我们探索将LLMs与知识图谱上的小型模型（KGMs）融合，旨在提升推理准确性同时降低成本。然而，将这两个目标融合在优化过程中颇具挑战，且模型选择因知识多样性而变得复杂。为此，我们创新性地提出了Coke策略，一种专为KBQA设计的成本效益方案，通过定制的多臂老虎机模型，在预算限制下最小化对LLMs的依赖。我们采用集群级Thompson采样设定准确性预期，并通过上下文感知策略优化，根据问题语义精准选择模型。决策过程受历史失败成本的约束，确保成本效益。实验结果表明，Coke不仅在基准数据集上提升了2.74%的准确性，还节省了高达20.89%的GPT-4费用，显著推动了性能与成本的平衡。
>
> https://arxiv.org/abs/2405.17337

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17337/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17337/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17337/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17337/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.17337/x5.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.17337](https://arxiv.org/abs/2405.17337)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886