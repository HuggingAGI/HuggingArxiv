# 审查链：揭秘大型语言模型中的后门攻击
发布时间：2024年06月09日

`模型安全`
> Chain-of-Scrutiny: Detecting Backdoor Attacks for Large Language Models
>
> 后门攻击对大型语言模型（LLMs）构成严重威胁，尤其是在第三方服务提供API集成和提示工程日益增多的情况下。不可信的第三方可能植入后门，通过在用户查询中嵌入恶意指令来危害用户。一旦输入中包含攻击者预设的特定触发器，被后门感染的LLM便会生成恶意内容。传统的防御方法，如模型参数微调和梯度计算，因计算量大和数据需求高，对LLMs来说并不适用。为此，我们提出了一种名为“审查链”（CoS）的新型防御机制。后门攻击通过创建从触发器到目标输出的捷径，缺乏推理支持。CoS则引导LLMs生成详细的推理步骤，并审查这些步骤以确保与最终答案的一致性，任何不一致都可能是攻击的迹象。CoS仅需对LLM的黑盒访问权限，特别适用于通过API访问的LLMs，且用户友好，允许用户自行执行防御。整个防御过程透明，由自然语言驱动。我们通过在多种任务和LLMs上进行的广泛实验验证了CoS的有效性，并发现它对更强大的LLMs更为有益。
>
> https://arxiv.org/abs/2406.05948

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.05948/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.05948/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.05948/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.05948/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.05948](https://arxiv.org/abs/2406.05948)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886