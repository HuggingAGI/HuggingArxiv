# 结合半结构化知识与基于三元组预过滤的LLM，提升问答能力
发布时间：2024年09月01日

`知识图谱`
> Harnessing the Power of Semi-Structured Knowledge and LLMs with Triplet-Based Prefiltering for Question Answering
>
> 大型语言模型（LLM）往往缺乏特定领域知识，即便经过微调也易产生错误信息。为此，我们引入了4StepFocus流程，特别是其预处理步骤，旨在大幅提升LLM的答案准确性。该流程通过引导模型利用其捕捉关系和基础推理的能力，有效整合外部知识。具体而言，4StepFocus通过在半结构化知识库中进行基于三元组的搜索，以直接且可追溯的方式筛选潜在正确答案，随后基于非结构化数据对候选答案进行排序。这一方法与仅依赖潜在表示的方法形成鲜明对比。4StepFocus的步骤包括：1) 利用LLM生成三元组提取关系数据，2) 通过知识图谱替换三元组中的变量以缩小候选答案范围，3) 利用向量相似性搜索结合非结构化数据对候选答案进行排序，4) 结合背景数据由LLM对最佳候选进行重新排序。实验结果显示，该方法在医学、产品推荐及学术论文搜索等领域表现出色，不仅增强了信息的可追溯性，更在性能上超越了现有顶尖方法。本文开辟了一个新的研究方向，为未来的深入探索提供了广阔空间。相关源代码已公开在https://github.com/kramerlab/4StepFocus。
>
> https://arxiv.org/abs/2409.00861

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.00861](https://arxiv.org/abs/2409.00861)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)