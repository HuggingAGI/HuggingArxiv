# 实时个性化：基于人类反馈的知识图谱调优大型语言模型
发布时间：2024年05月30日

`知识图谱`
> Knowledge Graph Tuning: Real-time Large Language Model Personalization based on Human Feedback
>
> 大型语言模型（LLMs）在众多自然语言处理任务中表现出色。当这些模型投入使用时，它们会接触到拥有个性化知识的用户，并通过交互持续反映这些知识。为了优化用户体验，实时个性化模型变得至关重要，它使LLMs能够根据用户反馈调整特定知识。然而，现有方法通常依赖于高成本的反向传播来微调模型，且缺乏透明度，长期使用可能导致模型性能的不确定性。为此，我们开发了知识图谱调优（KGT），一种创新方法，它利用知识图谱（KGs）来个性化LLMs，无需修改模型参数。KGT通过提取用户查询和反馈中的个性化知识，优化KGs，避免了反向传播，提高了效率，并确保了调整的可解释性。实验证明，KGT不仅提升了包括GPT-2、Llama2和Llama3在内的顶级LLMs的个性化性能，还降低了延迟和GPU内存成本。总之，KGT为实现用户与LLMs交互中的实时、高效且透明的个性化提供了一个有前景的解决方案。
>
> https://arxiv.org/abs/2405.19686

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19686/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19686/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19686/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.19686/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.19686](https://arxiv.org/abs/2405.19686)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886