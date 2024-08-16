# 利用增强检索功能的大型语言模型生成攻击图
发布时间：2024年08月11日

`RAG`
> Using Retriever Augmented Large Language Models for Attack Graph Generation
>
> 随着系统复杂性日益增加，评估其安全性的重要性也随之提升。攻击图作为网络安全专家的重要工具，能全面展示系统内潜在的攻击路径。传统方法依赖专家知识与手动操作，难以覆盖不断变化的威胁全貌。本文探索了利用大型语言模型（如ChatGPT）自动生成攻击图的新途径，通过智能链接漏洞信息（CVEs），并展示了如何从威胁报告中构建攻击图。
>
> https://arxiv.org/abs/2408.05855

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/CVE_Description.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/SolarwindsAttack.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/System_Model_Input.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/Flowchart_Preprocessing.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/Flowchart_Generation.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/WithoutContextDefinedSystem.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/Attack_Graph_Defined_System.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/SolarwindsEvasionTechniques.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/defined_system_GPT_3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/defined_system_BARD.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/Kubernets_gpt4.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.05855/kubernets_bard.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.05855](https://arxiv.org/abs/2408.05855)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)