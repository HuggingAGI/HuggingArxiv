# DAC：文本转SQL的分解式自动校正
发布时间：2024年08月16日

`代码编写`
> DAC: Decomposed Automation Correction for Text-to-SQL
>
> Text-to-SQL 任务通过自动生成 SQL 查询，帮助人们轻松获取数据库信息。基于大型语言模型 (LLM) 的方法因其卓越性能成为主流。自动纠正是提升性能的关键，但现有方法直接让 LLM 纠正 SQL 错误，效果不佳。本文提出分解纠正法 (DAC)，通过分解 Text-to-SQL 任务，先识别并修正子任务错误，再整合生成正确 SQL。实验表明，DAC 在多个数据集上平均提升性能 3.7%，显著优于传统方法。
>
> https://arxiv.org/abs/2408.08779

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08779/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08779/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08779/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.08779/x4.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.08779](https://arxiv.org/abs/2408.08779)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)