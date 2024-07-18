# ASTPrompter：通过弱监督自动化手段，对语言模型进行红队测试，以识别潜在的有毒提示。
发布时间：2024年07月12日

`模型安全`
> ASTPrompter: Weakly Supervised Automated Language Model Red-Teaming to Identify Likely Toxic Prompts
>
> 我们提出了一种强化学习方法，用于自动化测试大型语言模型（LLM）的安全性，专注于发现既能触发有毒输出又能保持低困惑度的提示。这种方法通过在 GPT-2 和 GPT-2 XL 模型上应用一种新颖的在线和弱监督的身份偏好优化（IPO）变体来实现。我们的策略不仅能生成可能的提示，还能触发有毒性，从而在正常使用模型时更可能出现。我们还对学习到的策略、可能性和有毒性之间的权衡进行了定性分析，并讨论了其潜在影响。项目源代码已公开，可在 GitHub 上获取。
>
> https://arxiv.org/abs/2407.09447

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09447/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.09447/x2.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.09447](https://arxiv.org/abs/2407.09447)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1