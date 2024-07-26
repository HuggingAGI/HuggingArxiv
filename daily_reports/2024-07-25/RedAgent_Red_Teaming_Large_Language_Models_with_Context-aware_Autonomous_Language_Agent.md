# RedAgent：通过上下文感知的自主语言代理，对大型语言模型进行红队挑战。
发布时间：2024年07月23日

`模型安全`
> RedAgent: Red Teaming Large Language Models with Context-aware Autonomous Language Agent
>
> 近期，GPT-4 等先进大型语言模型（LLM）已广泛应用于 Code Copilot 等实际场景，大幅增加了 LLM 的安全风险。特别是通过特定提示引发有害输出的“越狱攻击”，引起了严重安全问题。为应对这些威胁，越来越多的红队测试通过设计越狱提示来模拟攻击场景。但现有方法未能充分考虑 LLM 在不同情境下的特定弱点，且依赖有限的变异操作改进越狱模板，缺乏适应性和自动化。为此，我们提出“越狱策略”概念，并开发了 RedAgent 系统，该系统利用这些策略生成情境感知的越狱提示。通过在额外内存中自我反思，RedAgent 不断优化策略，有效突破特定情境下的 LLM 防御。实验显示，RedAgent 仅需五次查询即可攻破多数黑盒 LLM，效率提升一倍。此外，它还能更高效地针对定制 LLM 应用进行越狱。我们通过向 GPT 应用发送情境感知提示，仅用两次查询就发现了 60 个严重漏洞，并已向 OpenAI 和 Meta 报告，推动漏洞修复。
>
> https://arxiv.org/abs/2407.16667

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/illegal_category_strategy_heatmap_vicuna-7b_14_category_70.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/illegal_category_strategy_heatmap_gpt-3.5-turbo-1106_14_category_70.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/illegal_category_strategy_heatmap_gemini-pro_14_category_70.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.16667/x13.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.16667](https://arxiv.org/abs/2407.16667)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1