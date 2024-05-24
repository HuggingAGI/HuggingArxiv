# KG-RAG：连接知识与创意的桥梁
发布时间：2024年05月20日

`RAG`
> KG-RAG: Bridging the Gap Between Knowledge and Creativity
>
> 在智能代理系统的发展中，如何在保持大型语言模型代理（LMAs）创造性的同时确保事实准确性，是一个重大挑战。LMAs在处理知识密集型任务时，常遭遇信息幻觉、灾难性遗忘及长上下文处理的限制。本文提出的KG-RAG（知识图谱-检索增强生成）框架，通过结合结构化知识图谱与LLMs功能，大幅降低了对LLMs潜在知识的依赖，从而强化了LMAs的知识处理能力。该框架首先从非结构化文本构建知识图谱，随后在新图上进行信息检索，以执行知识图谱问答（KGQA）。检索过程中采用的“探索链（CoE）”算法，利用LLMs的推理能力，在知识图谱中逐步探索节点与关系。初步实验结果显示，在减少幻觉内容方面取得了显著成效，为开发擅长处理知识密集任务的智能系统开辟了新路径。
>
> https://arxiv.org/abs/2405.12035

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.12035/agent_workflow.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.12035/hyperobject_diagram.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.12035/hyperobject_example.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.12035/coe_diagram_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.12035/llm_vs_rag_vs_coe.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2405.12035](https://arxiv.org/abs/2405.12035)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886