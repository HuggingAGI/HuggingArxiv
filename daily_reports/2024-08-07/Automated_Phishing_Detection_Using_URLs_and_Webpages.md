# 通过分析 URL 和网页内容，实现自动化钓鱼检测。
发布时间：2024年08月03日

`代码编写`
> Automated Phishing Detection Using URLs and Webpages
>
> 网络钓鱼检测，作为网络安全的关键任务，旨在识别并阻止欺诈性获取敏感信息的行为，保护个人与组织免受数据泄露与财务损失。本项目通过构建LLM代理框架，突破了传统基于静态参考的检测局限。该框架利用大型语言模型实时获取并应用在线信息，为精准的钓鱼检测提供动态参考。这一创新不仅提升了自动化安全措施的适应性与效率，还免除了对静态知识库的依赖。项目报告中，我们首先对现有解决方案进行了深入分析，进而设计了这一新框架。通过模拟LLM为代理，我们详细阐述了框架构建技术，并实施了概念验证与性能对比实验。实验结果表明，我们的方法准确率高达0.945，较现有方案DynaPhish高出0.445。同时，我们也指出了当前方法的局限，并提出了改进方向，以期进一步提升效果。总体而言，该框架有望提升现有基于参考的钓鱼检测方法的效能，并具备向实际应用转化的潜力。
>
> https://arxiv.org/abs/2408.01667

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/stat_3k_phishing.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/no_logo.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/fb.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/wrong_logo.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/knowledge_expansion.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/at_t.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/at_t_phishing.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/biktub.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.01667/updated_diagram.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.01667](https://arxiv.org/abs/2408.01667)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)