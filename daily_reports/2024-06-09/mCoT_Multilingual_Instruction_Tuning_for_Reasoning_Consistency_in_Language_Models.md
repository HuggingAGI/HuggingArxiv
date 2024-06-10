# mCoT：通过多语言指令调优，确保语言模型推理的一致性
发布时间：2024年06月04日

`提示工程`
> mCoT: Multilingual Instruction Tuning for Reasoning Consistency in Language Models
>
> 思维链（CoT）技术赋予大型语言模型（LLMs）强大的推理能力，助力其在多种下游任务中表现卓越。然而，当前研究多聚焦于英语，对多语言环境的探索尚显不足，这使得不同语言中推理能力的可靠性成为待解之谜。为此，我们采用流行开源LLMs，深入研究了多语言间的推理一致性。首先，我们创建了首个大规模多语言数学推理数据集mCoT-MATH，涵盖11种语言。接着，通过多语言CoT指令调整，我们提升了模型在不同语言间的推理能力，增强了模型的一致性。尽管现有LLMs在不同语言间表现差异显著，尤其在资源较少的语言上表现不佳，但我们的7B参数模型mCoT在跨语言一致性上表现出色，性能甚至超越或媲美更大规模的闭源和开源模型。
>
> https://arxiv.org/abs/2406.02301

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x5.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x6.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x9.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x10.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.02301/x11.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.02301](https://arxiv.org/abs/2406.02301)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886