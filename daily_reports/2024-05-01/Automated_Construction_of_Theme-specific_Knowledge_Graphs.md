![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 自动化构建针对性主题的知识图谱
发布时间：2024年04月29日

`知识图谱`
> 知识图谱在问答和智能对话系统等任务中应用广泛，但现有知识图谱在信息细节和即时性上存在不足，尤其在专业研究和快速变化的情境如突发新闻追踪中，这些不足严重影响了知识的检索与分析。为此，我们提出了一个针对特定主题的知识图谱（ThemeKG），并设计了一个无监督的构建框架（TKGCon）。该框架能够从特定主题的原始语料库中提炼出包含关键实体和关系的高质量知识图谱。我们首先利用维基百科中的实体本体作为起点，然后利用大型语言模型（LLMs）探索候选关系，形成关系本体。在处理主题语料库的文档时，我们将实体对与本体映射，筛选出候选关系。最终，结合上下文和本体，我们巩固了实体对之间的关系。我们发现，直接向GPT-4查询特定主题的知识图谱会导致实体识别不准确，关系描述模糊或错误。而我们的模型通过逐步构建主题知识图谱，在准确性上超越了GPT-4。实验结果显示，我们的框架在各项评估中均优于传统知识图谱构建方法。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.19146/intro8.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.19146/overview11.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2404.19146/cased.png)


- 论文原文: [https://arxiv.org/abs/2404.19146](https://arxiv.org/abs/2404.19146)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)