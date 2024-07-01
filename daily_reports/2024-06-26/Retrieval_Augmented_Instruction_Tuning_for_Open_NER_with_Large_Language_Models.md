# 大型语言模型下的开放命名实体识别：基于检索增强的指令调优策略
发布时间：2024年06月25日

`知识图谱`
> Retrieval Augmented Instruction Tuning for Open NER with Large Language Models
>
> 大型语言模型（LLMs）的强大能力在信息提取（IE）领域展现出色，无论是通过检索增强提示还是指令调优（IT）。但如何最佳地结合信息与LLMs进行IE，这一问题仍待解答。本文深入探讨了针对IE的检索增强指令调优（RA-IT），特别聚焦于开放命名实体识别（NER）任务。我们为每个训练样本从训练数据集中提取语义相似的示例作为上下文，并将其前置于原始指令的输入。为了全面评估RA-IT，我们创建了一个中文IT数据集，并在英语和中文环境下对其进行了测试。实验结果证实了RA-IT在不同数据规模及双语环境下的有效性。此外，我们还深入分析了RA-IT框架中不同检索策略的影响。相关代码和数据已公开分享于：https://github.com/Emma1066/Retrieval-Augmented-IT-OpenNER
>
> https://arxiv.org/abs/2406.17305

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.17305/method_0616.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.17305/x1.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.17305/x2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.17305/x3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.17305/x4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.17305/zh_data_construction_prompt.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.17305](https://arxiv.org/abs/2406.17305)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 加入社群，公众号回复LLM
- 最新论文订阅体验：公众号号菜单回复1