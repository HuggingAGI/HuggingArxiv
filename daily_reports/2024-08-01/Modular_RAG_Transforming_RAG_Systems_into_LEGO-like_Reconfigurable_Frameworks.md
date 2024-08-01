# 模块化RAG：打造如同乐高般的可重构RAG系统框架
发布时间：2024年07月25日

`RAG`
> Modular RAG: Transforming RAG Systems into LEGO-like Reconfigurable Frameworks
>
> RAG 技术通过增强检索能力，显著提升了 LLM 在知识密集型任务中的表现。随着应用需求的增加，RAG 不断进化，整合了尖端检索技术、LLM 及其他互补技术，使其系统愈发复杂。然而，技术快速进步使得基础 RAG 范式面临挑战，特别是在“检索-生成”流程的统一性上。本文深入分析了现有 RAG 的局限，并提出了模块化 RAG 框架，通过分解系统为独立模块和专业操作，构建了一个高度灵活的框架。模块化 RAG 不仅超越了传统线性结构，还引入了先进的路由、调度和融合设计。本文还详细分析了四种常见 RAG 模式——线性、条件、分支和循环——的实现细节。模块化 RAG 为 RAG 系统的创新和部署开辟了新路径。最后，本文探讨了未来可能出现的新操作符和范式，为 RAG 技术的持续发展提供了理论支撑和实践指南。
>
> https://arxiv.org/abs/2407.21059

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/base_case.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/case_modular.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/RAG_paradigm_compare.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/Seq_Pattern.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/rrr.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/conditional.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/pre_banch.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/post_branch.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/Replug.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/Loop.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/Iter_retgen.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/ToC.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/Flare.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/Self-RAG.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/RetriverFT-521.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/GeneratorFT.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2407.21059/DualFT.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2407.21059](https://arxiv.org/abs/2407.21059)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)