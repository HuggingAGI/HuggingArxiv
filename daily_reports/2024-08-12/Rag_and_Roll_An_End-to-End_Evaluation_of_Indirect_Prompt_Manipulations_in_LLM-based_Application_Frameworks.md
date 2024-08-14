# Rag and Roll：探索基于 LLM 应用框架中，间接提示操作的全面评估之旅
发布时间：2024年08月12日

`RAG`
> Rag and Roll: An End-to-End Evaluation of Indirect Prompt Manipulations in LLM-based Application Frameworks
>
> RAG技术通过收集、索引、检索和提供信息，为模型赋予了分布外知识。尽管因其灵活性和低成本而日益流行，但其安全问题却鲜有研究。本文探讨了RAG系统面对端到端间接提示操纵的脆弱性。我们首先分析了现有RAG框架，识别出关键配置参数，并回顾了攻击者可能利用的技术。通过实施Rag n Roll框架，我们评估了攻击效果，发现尽管攻击者能提升恶意文档排名，但成功率仅约40%，若将模糊答案视为成功，则可达60%。使用未优化文档的攻击者，通过部署多个文档，也能达到类似效果。此外，调整RAG配置虽能略微阻碍攻击，但最有效的组合却严重影响了系统功能。
>
> https://arxiv.org/abs/2408.05025

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.05025](https://arxiv.org/abs/2408.05025)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)