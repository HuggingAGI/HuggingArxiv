# 从基本原理出发，对大型语言模型进行多轮上下文越狱攻击
发布时间：2024年08月08日

`模型安全`
> Multi-Turn Context Jailbreak Attack on Large Language Models From First Principles
>
> 大型语言模型（LLM）在智能对话和文本生成等众多应用中展现出卓越性能，但其固有的安全漏洞，尤其是在越狱攻击方面，已成为严峻挑战。攻击者能绕过安全机制，引发有害输出。针对多轮语义越狱攻击，我们发现现有方法未充分考虑多轮对话在攻击中的作用，导致交互中的语义偏差。为此，本文为多轮攻击奠定理论基础，并提出一种名为上下文融合攻击（CFA）的新型黑盒攻击方法。CFA 通过筛选目标关键词、构建上下文场景、动态融合目标并替换恶意关键词，巧妙隐藏恶意意图。实验表明，CFA 在成功率、分歧和危害性方面均优于其他多轮攻击策略，尤其在 Llama3 和 GPT-4 上表现突出。
>
> https://arxiv.org/abs/2408.04686

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.04686/x9.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.04686](https://arxiv.org/abs/2408.04686)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)