# EffiQA：策略性多模型协作，知识图谱上的高效问答之道
发布时间：2024年06月03日

`知识图谱`
> EffiQA: Efficient Question-Answering with Strategic Multi-Model Collaboration on Knowledge Graphs
>
> 大型语言模型（LLMs）虽在自然语言处理领域表现出色，但在涉及知识图谱（KGs）的复杂推理任务上仍显不足。现有方法要么未能充分发挥LLMs的推理潜力，要么因紧密结合导致计算成本过高。为此，我们推出了EffiQA这一创新协作框架，旨在通过迭代过程在性能与效率间找到平衡点。EffiQA分为三个阶段：全局规划、高效KG探索及自我反思。它首先利用LLMs的常识推理能力进行全局规划，探索可能的推理路径；随后，将语义剪枝任务交由小型插件模型处理，以提升KG探索效率；最后，通过LLMs的自我反思，不断优化规划与探索过程。在多个KBQA基准测试中，EffiQA展现了其卓越性能，巧妙平衡了推理精度与计算开销。我们期待EffiQA能重新定义LLMs与KGs的融合方式，为知识密集型查询提供新思路，并推动基于知识的问答研究向前发展。
>
> https://arxiv.org/abs/2406.01238

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01238/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01238/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01238/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.01238/myplot.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.01238](https://arxiv.org/abs/2406.01238)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886