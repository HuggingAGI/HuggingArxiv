# 借助LLM代理，突破文本转图像模型的限制
发布时间：2024年08月01日

`多模态大模型`
> Jailbreaking Text-to-Image Models with LLM-Based Agents
>
> 近期进展大幅提升了基于大型语言模型 (LLM) 的自主代理解决自动化任务的能力。但多数 LLM 代理集中于对话、编程或特定领域，忽视了生成式 AI 安全任务的挑战。本文提出 Atlas，一个集成高效模糊测试的多代理框架，专攻带有安全过滤器的文本到图像 (T2I) 模型越狱攻击。Atlas 运用视觉语言模型 (VLM) 检测提示是否触发安全过滤器，并协同 LLM 和 VLM 迭代生成绕过过滤器的提示。此外，Atlas 通过多代理通信、上下文学习 (ICL) 记忆机制和思维链 (COT) 方法，强化了 LLM 在攻击场景中的推理能力。评估表明，Atlas 在黑盒环境下成功越狱了多个顶尖 T2I 模型，并在查询效率和图像质量上超越现有方法。
>
> https://arxiv.org/abs/2408.00523

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/cat-1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/cat-3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/dog-2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/dog-1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/bypass_1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/bypass_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/bypass_3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/reuse_1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/reuse_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/reuse_3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/fid_1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/fid_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/fid_3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/query_1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/query_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/query_3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/agent_num_bypass_1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/agent_num_bypass_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/agent_num_bypass_3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/agent_query_1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/agent_query_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.00523/agent_query_3.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.00523](https://arxiv.org/abs/2408.00523)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)