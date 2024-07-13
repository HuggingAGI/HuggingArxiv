# Rectifier：利用 LLM 实现代码翻译与校正
发布时间：2024年07月10日

`代码编写`
> Rectifier: Code Translation with Corrector via LLMs
>
> 随着软件与社会的进步，软件迁移日益受到重视。早期研究多依赖手工规则进行语言间的代码转换，这一过程既易错又耗时。近年来，研究者开始尝试利用预训练的大型语言模型（LLM）进行代码翻译，但此复杂任务中LLM常犯的错误包括编译、运行时、功能性及非终止执行错误。这些错误的根源相似，如包导入失败、循环边界失误、操作符错误等。为此，我们提出了通用校正器Rectifier，一个微型且普适的错误修复模型，它能从LLM的错误中学习，并广泛应用于纠正各类LLM的翻译错误。实验表明，Rectifier在C++、Java与Python间的代码翻译中展现了出色的修复能力，交叉实验亦证实了其方法的稳健性。
>
> https://arxiv.org/abs/2407.07472

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x12.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.07472/x13.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.07472](https://arxiv.org/abs/2407.07472)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1