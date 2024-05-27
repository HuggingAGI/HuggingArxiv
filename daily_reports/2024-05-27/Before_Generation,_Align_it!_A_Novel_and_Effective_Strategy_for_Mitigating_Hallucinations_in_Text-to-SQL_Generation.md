# 生成文本到SQL前，先进行内容对齐！这一新颖而高效的策略，旨在有效缓解生成过程中的幻觉问题。
发布时间：2024年05月24日

`代码编写`
> Before Generation, Align it! A Novel and Effective Strategy for Mitigating Hallucinations in Text-to-SQL Generation
>
> ICL驱动的大型语言模型在文本到SQL任务中表现出色，但LLMs的泛化缺陷常导致幻觉，限制了其潜力。我们首先识别并分类了文本到SQL各阶段常见的幻觉类型，并提出了任务对齐策略 (TA)，旨在减少幻觉。TA让LLMs借鉴类似任务经验，而非从头开始，有效减轻了幻觉。基于此，我们开发了TA-SQL框架，实验证明其有效且稳健，显著提升了GPT-4在BIRD dev上的性能，并在多个复杂基准测试中取得了显著进步。
>
> https://arxiv.org/abs/2405.15307

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15307/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15307/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15307/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15307/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15307/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15307/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.15307/x7.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.15307](https://arxiv.org/abs/2405.15307)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886